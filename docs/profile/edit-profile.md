<h2>Anvil</h2>
<p><strong>Target:</strong> <code>AB.010.001</code></p>

<table border="1" cellpadding="0" cellspacing="0" style="width: 90%; font-size: 12px;">
  <tr>
    <!-- LEFT: SITE MAP -->
    <td valign="top" style="width: 28%; padding: 10px;">
      <h3 style="margin-top:0;">Site Map</h3>
      <a href="../homepage/homepage.md">Homepage</a>
      <p style="margin:10px 0 6px;"><strong>1. Authentication &amp; Access Control</strong></p>
      <ul style="margin-top:0;">
        <li><a href="../authentication/authentication.md">Authentication (FR0.0)</a></li>
      </ul>
      <p style="margin:10px 0 6px;"><strong>2. User Account &amp; Profile Management</strong></p>
      <ul style="margin-top:0;">
        <li><a href="../profile/view-profile.md">View Profile (FR1.0)</a></li>
        <li><a href="../profile/edit-profile.md"><strong>Edit Profile (FR1.0)</strong></a></li>
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
    <!-- RIGHT: MEDIA + DESCRIPTION + USE CASE -->
    <td valign="top" style="width: 72%; padding: 10px;">
      <p><strong>Edit Profile (Buyer)</strong></p>
      <img src="../assets/edit_profile_buyer.png" alt="Edit Profile Buyer" style="max-width:100%; border:1px solid #000;">
      <p><strong>Edit Profile (Seller)</strong></p>
      <img src="../assets/edit_profile_seller.png" alt="Edit Profile Seller" style="max-width:100%; border:1px solid #000;">
      <h2>Edit Profile</h2>
      <p>
        The Edit Profile feature allows logged-in users to update their personal information such as name, contact details,
        and location. Keeping this information updated supports smoother communication and pickup coordination, especially when
        buyers and sellers need to confirm meetup details.
      </p>
      <p>
        Buyers can update profile fields used for reservation and pickup coordination. Sellers can update the same basic fields
        and maintain seller-specific details that help identify their listings and ensure consistent information when responding
        to buyer reservations.
      </p>
      <h2>Use Case Scenario</h2>
      <table border="1" cellpadding="6" cellspacing="0" style="width:100%; font-size:12px;">
        <tr>
          <th style="width: 22%;">Actor(s)</th>
          <td>Buyer, Seller</td>
        </tr>
        <tr>
          <th>Goal</th>
          <td>To update profile information so account details remain accurate for listing and pickup coordination.</td>
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
            2. The user selects <strong>Edit Profile</strong>.<br>
            3. The system displays editable fields (name, contact details, location).<br>
            4. The user updates one or more fields.<br>
            5. The user clicks <strong>Save</strong>.<br>
            6. The system validates the input and updates the profile record.<br>
            7. The system shows a confirmation message and displays the updated profile information.
          </td>
        </tr>
        <tr>
          <th>Outcome</th>
          <td><strong>Success:</strong> The user’s profile is updated and saved, and the new details are reflected in the account.</td>
        </tr>
      </table>
    </td>
  </tr>

  <tr>
    <td colspan="2" align="center">© 2026 NeighborGoods</td>
  </tr>
</table>
