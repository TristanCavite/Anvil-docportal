<h2>Anvil</h2>
<p><strong>Target:</strong> <code>AB.010.001</code></p>

<table border="1" cellpadding="0" cellspacing="0" style="width: 100%; font-size: 12px; table-layout:fixed;">
  <tr>
    <!-- LEFT: SITE MAP (BASED ON FR TABLE) -->
    <td valign="top" style="width: 28%; padding: 10px;">
      <h3 style="margin-top:0;">Site Map</h3>
      <strong>Homepage</strong>
      <!--Authentication & Access Control-->
      <p style="margin:10px 0 6px;"><strong>1. Authentication &amp; Access Control</strong></p>
      <ul style="margin-top:0;">
        <li><a href="../authentication/authentication.md">Authentication (FR1.0)</a></li>
      </ul>
      <!--User Account & Profile Management-->
      <p style="margin:10px 0 6px;"><strong>2. User Account &amp; Profile Management</strong></p>
      <ul style="margin-top:0;">
        <li><a href="../profile/view-profile.md">View Profile (FR2.0)</a></li>
        <li><a href="../profile/edit-profile.md">Edit Profile (FR2.0)</a></li>
      </ul>
      <!--Listing Creation & Management-->
      <p style="margin:10px 0 6px;"><strong>3. Listing Creation &amp; Management</strong></p>
      <ul style="margin-top:0;">
        <li><a href="../listings/create-listing.md">Create Listing (FR3.0)</a></li>
        <li><a href="../listings/edit-listing.md">Edit Listing (FR3.0)</a></li>
        <li><a href="../listings/archive-listing.md">Archive Listing (FR3.0)</a></li>
      </ul>
      <!--Auto Sold-out & Expiry Handling-->
      <p style="margin:10px 0 6px;"><strong>4. Auto Sold-out &amp; Expiry Handling</strong></p>
      <ul style="margin-top:0;">
        <li><a href="../listings/auto-soldout-expiry.md">Auto Sold-out / Expiry Handling (FR4.0)</a></li>
      </ul>
      <!--Buyer Browsing, Search, and Filters-->
      <p style="margin:10px 0 6px;"><strong>5. Buyer Browsing, Search, &amp; Filters</strong></p>
      <ul style="margin-top:0;">
        <li><a href="../browse/browse-listings.md">Browse Listings (FR5.0)</a></li>
        <li><a href="../browse/search-filter.md">Search &amp; Filters (FR5.0)</a></li>
      </ul>
      <!--Reservation & Order oordination-->
      <p style="margin:10px 0 6px;"><strong>6. Reservation &amp; Order Coordination</strong></p>
      <ul style="margin-top:0;">
        <li><a href="../orders/reserve-item.md">Reserve Item (FR6.0)</a></li>
        <li><a href="../orders/accept-decline-reservation.md">Accept/Decline Reservation (FR6.0)</a></li>
        <li><a href="../orders/update-order-status.md">Update Order Status (FR6.0)</a></li>
      </ul>
      <!--In-order Chat & Pickup Information-->
      <p style="margin:10px 0 6px;"><strong>7. In-order Chat &amp; Pickup Information</strong></p>
      <ul style="margin-top:0;">
        <li><a href="../chat/order-chat.md">Order Chat (FR7.0)</a></li>
        <li><a href="../chat/pickup-details.md">Pickup Details (FR7.0)</a></li>
      </ul>
      <!--Seller Verification & Listing Moderation-->
      <p style="margin:10px 0 6px;"><strong>8. Seller Verification &amp; Listing Moderation</strong></p>
      <ul style="margin-top:0;">
        <li><a href="../admin/verify-seller.md">Verify Seller Accounts (FR8.0)</a></li>
        <li><a href="../admin/review-listings.md">Approve/Reject Listings (FR8.0)</a></li>
      </ul>
      <!--Reporting & Enforcement-->
      <p style="margin:10px 0 6px;"><strong>9. Reporting &amp; Enforcement</strong></p>
      <ul style="margin-top:0;">
        <li><a href="../reports/report-listing-user.md">Report Listing/User (FR9.0)</a></li>
        <li><a href="../reports/review-reports.md">Review Reports (FR9.0)</a></li>
        <li><a href="../reports/apply-sanctions.md">Warn/Suspend/Ban (FR9.0)</a></li>
      </ul>
      <!--Notifications & Email Alerts-->
      <p style="margin:10px 0 6px;"><strong>10. Notifications &amp; Email Alerts</strong></p>
      <ul style="margin-top:0;">
        <li><a href="../notifications/notifications.md">Notifications &amp; Alerts (FR10.0)</a></li>
      </ul>
      <!--Activity Logging & Audit Trail-->
      <p style="margin:10px 0 6px;"><strong>11. Activity Logging &amp; Audit Trail</strong></p>
      <ul style="margin-top:0;">
        <li><a href="../audit/view-audit-logs.md">View Activity Logs (FR11.0)</a></li>
      </ul>
    </td>
    <!-- Right Sidebar - Event and Scenario-->
    <td valign="top" style="width: 72%; padding: 10px;">
      <p><strong>Homepage</strong></p>
      <p><strong>Homepage (unauthorized)</strong></p>
      <img src="/assets/Unauthorized.png" alt="Homepage Unauthorized" style="max-width:100%; border:1px solid #000;">
      <p><strong>Homepage (authorized)</strong></p>
      <img src="/assets/Authorized.png" alt="Homepage Authorized" style="max-width:100%; border:1px solid #000;">
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
            1. The user opens the homepage.<br>
            2. The system displays active listings with basic details and time remaining before expiry/pickup deadline.<br>
            3. The user uses search and filters to narrow down listings (category, price range, distance, time left).<br>
            4. The user selects a listing to view full details.<br>
            5. If the user attempts a protected action (reserve, chat, create listing, manage orders), the system requires the user to sign in.<br>
            6. After login, the system loads role-based navigation:
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
