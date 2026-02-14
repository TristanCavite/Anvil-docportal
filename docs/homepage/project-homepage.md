<h2>Anvil</h2>
<p><strong>Target:</strong> <code>AB.010.001</code></p>

<table border="1" cellpadding="0" cellspacing="0" style="width: 90%; font-size: 12px;">
  <tr>
    <!--Left Sidebar - Site Map -->
    <td valign="top" style="width: 28%; padding: 10px;">
      <h3 style="margin-top:0;">Site Map</h3>
      <a href="">Homepage</a>
      <!--Authentication & Access Control-->
      <p style="margin:10px 0 6px;"><strong>1. Authentication &amp; Access Control</strong></p>
      <ul style="margin-top:0;">
        <li><a href="docs/authentication/authentication.md">Authentication (FR0.0)</a></li>
      </ul>
      <!-- User Account & Profile Management -->
      <p style="margin:10px 0 6px;"><strong>2. User Account &amp; Profile Management</strong></p>
      <ul style="margin-top:0;">
        <li><a href="docs/profile/view-profile.md">View Profile (FR1.0)</a></li>
        <li><a href="docs/profile/edit-profile.md">Edit Profile (FR1.0)</a></li>
      </ul>
      <!-- Listings -->
      <p style="margin:10px 0 6px;"><strong>3. Listings</strong></p>
      <ul style="margin-top:0;">
        <li><a href="docs/listings/browse-listings.md">Browse Listings (FR4.0)</a></li>
        <li><a href="docs/listings/search-filter.md">Search &amp; Filters (FR4.0)</a></li>
        <li><a href="docs/listings/view-listing-details.md">View Listing Details (FR4.0)</a></li>
        <li><a href="docs/listings/create-listing.md">Create Listing (FR2.0)</a></li>
        <li><a href="docs/listings/edit-listing.md">Edit Listing (FR2.0)</a></li>
        <li><a href="docs/listings/archive-listing.md">Archive Listing (FR2.0)</a></li>
      </ul>
      <!-- Orders / Reservation -->
      <p style="margin:10px 0 6px;"><strong>4. Orders / Reservations</strong></p>
      <ul style="margin-top:0;">
        <li><a href="docs/orders/reserve-item.md">Reserve Item (FR5.0)</a></li>
        <li><a href="docs/orders/accept-decline-reservation.md">Accept/Decline Reservation (FR5.0)</a></li>
        <li><a href="docs/orders/view-order-status.md">View Order Status (FR5.0)</a></li>
        <li><a href="docs/orders/update-order-status.md">Update Order Status (FR5.0)</a></li>
      </ul>
      <!-- Order Chat & Pickup Info-->
      <p style="margin:10px 0 6px;"><strong>5. Order Chat &amp; Pickup Info</strong></p>
      <ul style="margin-top:0;">
        <li><a href="docs/chat/order-chat.md">Order Chat (FR6.0)</a></li>
        <li><a href="docs/chat/pickup-details.md">Pickup/Delivery Details (FR6.0)</a></li>
      </ul>
      <!-- Notifications -->
      <p style="margin:10px 0 6px;"><strong>6. Notifications</strong></p>
      <ul style="margin-top:0;">
        <li><a href="docs/notifications/receive-notification.md">Receive Notifications (FR9.0)</a></li>
        <li><a href="docs/notifications/email-alerts.md">Email Alerts (FR9.0)</a></li>
      </ul>
      <!-- Reports & Enforcement -->
      <p style="margin:10px 0 6px;"><strong>7. Reports &amp; Enforcement</strong></p>
      <ul style="margin-top:0;">
        <li><a href="docs/reports/report-listing-user.md">Report Listing/User (FR8.0)</a></li>
        <li><a href="docs/reports/review-reports.md">Review Reports (FR8.0)</a></li>
        <li><a href="docs/reports/apply-sanctions.md">Warn/Suspend/Ban (FR8.0)</a></li>
      </ul>
      <!--Verification, Moderation, and Audit -->
      <p style="margin:10px 0 6px;"><strong>8. Verification, Moderation &amp; Audit</strong></p>
      <ul style="margin-top:0;">
        <li><a href="docs/admin/verify-seller.md">Verify Seller Accounts (FR7.0)</a></li>
        <li><a href="docs/admin/review-listings.md">Approve/Reject Listings (FR7.0)</a></li>
        <li><a href="docs/audit/view-audit-logs.md">View Activity Logs (FR10.0)</a></li>
      </ul>
    </td>
    <!-- Right Sidebar - Event and Scenario-->
    <td valign="top" style="width: 72%; padding: 10px;">
      <p><strong>Homepage (unauthorized)</strong></p>
      <img src="../assets/home_unauthorized.png" alt="Homepage Unauthorized" style="max-width:100%; border:1px solid #000;">
      <p><strong>Homepage (authorized)</strong></p>
      <img src="../assets/home_authorized.png" alt="Homepage Authorized" style="max-width:100%; border:1px solid #000;">
      <h2>Homepage</h2>
      <p>
        The Homepage is the main landing page where users can immediately see available surplus-food listings in Baybay City.
        It highlights basic listing details such as item name, price or free tag, pickup location, and time remaining before pickup
        deadline or expiry. Users who are not logged in can browse and view listing information, but actions that affect the system
        (such as reserving items, chatting, posting listings, and managing orders) require authentication.
      </p>
      <p>
        Once logged in, the homepage adapts to the user role. Buyers can access reservation and order tracking features. Sellers can
        access listing management and reservation responses. System administrators can access moderation, reporting, and activity logs.
        This setup keeps the homepage simple for browsing while ensuring protected actions are only available to authorized users.
      </p>
      <h2>Use Case Scenario</h2>
      <table border="1" cellpadding="6" cellspacing="0" style="width:100%; font-size:12px;">
        <tr>
          <th style="width: 22%;">Actor(s)</th>
          <td>Guest, Buyer, Seller, System Administrator</td>
        </tr>
        <tr>
          <th>Goal</th>
          <td>To browse available listings and navigate to the correct features based on login status and role permissions.</td>
        </tr>
        <tr>
          <th>Preconditions</th>
          <td>
            1. The user has access to the homepage URL.<br>
            2. The system has available listings to display (active or not yet expired).<br>
            3. The user may or may not be logged in.
          </td>
        </tr>
        <tr>
          <th>Main Scenario</th>
          <td>
            4. The user opens the homepage.<br>
            5. The system displays active listings with basic details and time remaining before expiry/pickup deadline.<br>
            6. The user uses search and filters to narrow down listings (category, price range, distance, time left).<br>
            7. The user selects a listing to view full details.<br>
            8. If the user attempts a protected action (reserve, chat, create listing, manage orders), the system requires the user to sign in.<br>
            9. After login, the system loads role-based navigation:
            <br>&nbsp;&nbsp;&nbsp;&nbsp;a. Buyer: reserve items and track order status.
            <br>&nbsp;&nbsp;&nbsp;&nbsp;b. Seller: create/manage listings and accept/decline reservations.
            <br>&nbsp;&nbsp;&nbsp;&nbsp;c. Admin: access moderation, reports, and audit logs.
          </td>
        </tr>
        <tr>
          <th>Outcome</th>
          <td><strong>Success:</strong> The user browses listings and is directed to allowed features based on authentication and role.</td>
        </tr>
      </table>
    </td>
  </tr>
  <tr>
    <td colspan="2" align="center">© 2026 Restora</td>
  </tr>
</table>
