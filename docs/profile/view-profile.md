<h2>Anvil</h2>
<p><strong>Target:</strong> <code>AB.010.001</code></p>

<table border="1" cellpadding="0" cellspacing="0" style="width: 90%; font-size: 12px;">
  <tr>
    <!-- LEFT: SITE MAP (same format as homepage) -->
    <td valign="top" style="width: 28%; padding: 10px;">
      <h3 style="margin-top:0;">Site Map</h3>
      <a href="../homepage/homepage.md">Homepage</a>
      <p style="margin:10px 0 6px;"><strong>1. Authentication &amp; Access Control</strong></p>
      <ul style="margin-top:0;">
        <li><a href="../authentication/authentication.md">Authentication (FR0.0)</a></li>
      </ul>
      <p style="margin:10px 0 6px;"><strong>2. User Account &amp; Profile Management</strong></p>
      <ul style="margin-top:0;">
        <li><a href="../profile/view-profile.md"><strong>View Profile (FR1.0)</strong></a></li>
        <li><a href="../profile/edit-profile.md">Edit Profile (FR1.0)</a></li>
      </ul>
      <p style="margin:10px 0 6px;"><strong>3. Listings</strong></p>
      <ul style="margin-top:0;">
        <li><a href="../listings/browse-listings.md">Browse Listings (FR4.0)</a></li>
        <li><a href="../listings/search-filter.md">Search &amp; Filters (FR4.0)</a></li>
        <li><a href="../listings/view-listing-details.md">View Listing Details (FR4.0)</a></li>
        <li><a href="../listings/create-listing.md">Create Listing (FR2.0)</a></li>
        <li><a href="../listings/edit-listing.md">Edit Listing (FR2.0)</a></li>
        <li><a href="../listings/archive-listing.md">Archive Listing (FR2.0)</a></li>
      </ul>
      <p style="margin:10px 0 6px;"><strong>4. Orders / Reservations</strong></p>
      <ul style="margin-top:0;">
        <li><a href="../orders/reserve-item.md">Reserve Item (FR5.0)</a></li>
        <li><a href="../orders/accept-decline-reservation.md">Accept/Decline Reservation (FR5.0)</a></li>
        <li><a href="../orders/view-order-status.md">View Order Status (FR5.0)</a></li>
        <li><a href="../orders/update-order-status.md">Update Order Status (FR5.0)</a></li>
      </ul>
      <p style="margin:10px 0 6px;"><strong>5. Order Chat &amp; Pickup Info</strong></p>
      <ul style="margin-top:0;">
        <li><a href="../chat/order-chat.md">Order Chat (FR6.0)</a></li>
        <li><a href="../chat/pickup-details.md">Pickup/Delivery Details (FR6.0)</a></li>
      </ul>
      <p style="margin:10px 0 6px;"><strong>6. Notifications</strong></p>
      <ul style="margin-top:0;">
        <li><a href="../notifications/receive-notification.md">Receive Notifications (FR9.0)</a></li>
        <li><a href="../notifications/email-alerts.md">Email Alerts (FR9.0)</a></li>
      </ul>
      <p style="margin:10px 0 6px;"><strong>7. Reports &amp; Enforcement</strong></p>
      <ul style="margin-top:0;">
        <li><a href="../reports/report-listing-user.md">Report Listing/User (FR8.0)</a></li>
        <li><a href="../reports/review-reports.md">Review Reports (FR8.0)</a></li>
        <li><a href="../reports/apply-sanctions.md">Warn/Suspend/Ban (FR8.0)</a></li>
      </ul>
      <p style="margin:10px 0 6px;"><strong>8. Verification, Moderation &amp; Audit</strong></p>
      <ul style="margin-top:0;">
        <li><a href="../admin/verify-seller.md">Verify Seller Accounts (FR7.0)</a></li>
        <li><a href="../admin/review-listings.md">Approve/Reject Listings (FR7.0)</a></li>
        <li><a href="../audit/view-audit-logs.md">View Activity Logs (FR10.0)</a></li>
      </ul>
    </td>
    <!-- RIGHT: MEDIA + DESCRIPTION + USE CASE (same style as homepage) -->
    <td valign="top" style="width: 72%; padding: 10px;">
      <p><strong>View Profile (Buyer)</strong></p>
      <img src="../assets/view_profile_buyer.png" alt="View Profile Buyer" style="max-width:100%; border:1px solid #000;">
      <p><strong>View Profile (Seller)</strong></p>
      <img src="../assets/view_profile_seller.png" alt="View Profile Seller" style="max-width:100%; border:1px solid #000;">
      <h2>View Profile</h2>
      <p>
        The View Profile feature allows logged-in users to view their account and profile information, including their name,
        contact details, and location. This helps users confirm that their information is correct before coordinating any
        reservation or pickup.
      </p>
      <p>
        For buyers, the profile shows basic details that support communication and pickup coordination. For sellers, the profile
        also includes seller-specific details that support listing management and seller identification within the platform.
      </p>
      <h2>Use Case Scenario</h2>
      <table border="1" cellpadding="6" cellspacing="0" style="width:100%; font-size:12px;">
        <tr>
          <th style="width: 22%;">Actor(s)</th>
          <td>Buyer, Seller</td>
        </tr>
        <tr>
          <th>Goal</th>
          <td>To view saved profile information for coordination and verification purposes.</td>
        </tr>
        <tr>
          <th>Preconditions</th>
          <td>
            1. The user is logged in.<br>
            2. The user has an existing profile record in the system.
          </td>
        </tr>
        <tr>
          <th>Main Scenario</th>
          <td>
            1. The user opens the navigation menu and selects <strong>Profile</strong>.<br>
            2. The user selects <strong>View Profile</strong>.<br>
            3. The system displays the user’s profile information (name, contact details, and location).<br>
            4. If the user is a seller, the system also displays seller-specific details.<br>
            5. The user reviews the information and proceeds back to other features or chooses to edit their profile if needed.
          </td>
        </tr>
        <tr>
          <th>Outcome</th>
          <td><strong>Success:</strong> The user successfully views their profile details and confirms the information shown.</td>
        </tr>
      </table>
    </td>
  </tr>

  <tr>
    <td colspan="2" align="center">© 2026 NeighborGoods</td>
  </tr>
</table>
