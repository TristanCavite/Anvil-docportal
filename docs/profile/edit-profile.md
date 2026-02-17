<h2>Anvil</h2>
<p><strong>Target:</strong> <code>AV.010.001</code></p>

<table border="1" cellpadding="0" cellspacing="0" style="width: 100%; font-size: 12px; table-layout:fixed;">
  <tr>
    <!-- LEFT: SITE MAP (BASED ON FR TABLE) -->
    <td valign="top" style="width: 28%; padding: 10px;">
      <h3 style="margin-top:0;">Site Map</h3>
      <a href="../homepage/project-homepage.md">Homepage</a>
      <!--Authentication & Access Control-->
      <p style="margin:10px 0 6px;"><strong>1. Authentication &amp; Access Control</strong></p>
      <ul style="margin-top:0;">
        <li><a href="../authentication/authentication.md">Authentication (FR1.0)</a></li>
      </ul>
      <!--User Account & Profile Management-->
      <p style="margin:10px 0 6px;"><strong>2. User Account &amp; Profile Management</strong></p>
      <ul style="margin-top:0;">
        <li><a href="view-profile.md">View Profile (FR2.0)</a></li>
        <li><strong>Edit Profile (FR2.0)</strong></li>
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
    <!-- RIGHT: MEDIA + DESCRIPTION + USE CASE -->
    <td valign="top" style="width: 72%; padding: 10px;">
      <p><a href="../homepage/project-homepage.md">Homepage</a> &gt;<strong>Edit Profile (FR2.0)</strong></p>
      <p><strong>Edit Profile (Buyer)</strong></p>
      <img src="../../assets/img/buyer-profile-edit.png" alt="Edit Profile - Buyer (mockup)" style="width:70%; aspect-ratio:16/9; object-fit:contain; background:#fff; border-radius:10px;" >
      <p><strong>Edit Profile (Seller)</strong></p>
      <img src="../../assets/img/seller-profile-edit.png" alt="Edit Profile - Seller (mockup)" style="width:70%; aspect-ratio:16/9; object-fit:contain; background:#fff; border-radius:10px;" >
      <h2>Edit Profile (FR1.0)</h2>
      <p>
        The Edit Profile feature allows logged-in users to update profile information such as name, contact details, and location.
        This supports smoother coordination during reservations and pickup/delivery arrangements. For sellers, it also supports
        maintaining seller-specific details so buyers can reliably identify who posted the listing and how to contact them.
      </p>
      <h2>Use Case Scenario</h2>
      <p>
        <strong>Actor(s):</strong> Buyer, Seller<br>
        <strong>Goal:</strong> To update profile information so account details remain accurate for communication and pickup coordination.<br><br>
        <strong>Preconditions:</strong>
        <ol>
          <li>The user is logged in</li>
          <li>The user has an existing profile record in the system</li>
        </ol>
        <strong>Main Scenario:</strong><br>
        <ol>
          <li>The user opens the navigation menu and selects <strong>Profile</strong>.</li>
          <li>The system displays the user profile page.</li>
          <li>The user clicks <strong>Edit Profile</strong>.</li>
          <li>The system displays editable fields (name, contact, location, and seller-specific fields if the user is a seller).</li>
          <li>The user updates one or more fields.</li>
          <li>The user clicks <strong>Save</strong>.</li>
          <li>The system validates the input and updates the profile record.</li>
          <li>The system displays a confirmation message and shows the updated profile information.</li>
        </ol>
        <strong>Alternative / Exception Flow:</strong><br>
        - A1) Invalid input (e.g., empty required field): The system highlights the field and blocks saving until corrected.<br>
        - A2) Save failed (network/server issue): The system shows an error message and keeps the user on the edit page to retry.<br><br>
        <strong>Outcome:</strong> <strong>Success:</strong> The user’s profile is saved and the updated details are reflected across the account.
    </td>
  </tr>

  <tr>
    <td colspan="2" align="center">© 2026 NeighborGoods</td>
  </tr>
</table>
