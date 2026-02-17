<h2>Anvil</h2>
<p><strong>Target:</strong> <code>AV.010.001</code></p>

<table border="1" cellpadding="0" cellspacing="0" style="width: 100%; font-size: 12px;  table-layout: fixed;">
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
            <li><a href="../profile/view-profile.md">View Profile (FR2.0)</a></li>
            <li><a href="../profile/edit-profile.md">Edit Profile (FR2.0)</a></li>
          </ul>
          <!--Listing Creation & Management-->
          <p style="margin:10px 0 6px;"><strong>3. Listing Creation &amp; Management</strong></p>
          <ul style="margin-top:0;">
            <li><a href="create-listing.md">Create Listing (FR3.0)</a></li>
            <li><a href="edit-listing.md">Edit Listing (FR3.0)</a></li>
            <li><strong>Archive Listing (FR3.0)</strong></li>
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
    <!-- Right SideBar - Content -->
    <td valign="top" style="width: 72%; padding: 10px;">
      <p><a href="../homepage/project-homepage.md">Homepage</a> &gt; <strong>Archive Listing (FR3.0)</strong></p>
      <h3 style="margin-top:0;">Archive Listing (FR3.0)</h3>
      <h2>Archive Listing (FR3.0)</h2>
      <p>
        The Archive Listing feature allows sellers to remove a listing from public browsing without permanently deleting it. Archived listings are hidden from buyers and cannot be reserved, but the record is retained for reference, reporting, and activity logs. This helps sellers manage old, incorrect, or no-longer-offered items while keeping history intact.
      </p>
      <h2>Use Case Scenario</h2>
      <p>
        <strong>Actor(s):</strong> Seller<br>
        <strong>Goal:</strong> To archive an existing listing so it is no longer visible or reservable by buyers while keeping the listing record for history and tracking.<br><br>
        <strong>Preconditions:</strong>
        <ol>
          <li>The seller is logged in</li>
          <li>The listing exists and belongs to the seller</li>
          <li>The listing is not already archived</li>
        </ol>
        <strong>Main Scenario:</strong><br>
        <ol>
          <li>The seller opens the Listings page and selects a listing to manage</li>
          <li>The system displays the listing details and management options</li>
          <li>The seller selects <strong>Archive Listing</strong></li>
          <li>The system shows a confirmation prompt to prevent accidental archiving</li>
          <li>The seller confirms the action</li>
          <li>The system updates the listing status to <strong>Archived</strong> and records the action in the activity log</li>
          <li>The system hides the listing from Browse/Search results and blocks new reservations</li>
          <li>The system displays a confirmation message and moves the listing to the archived section (if available)</li>
        </ol>
        <strong>Alternative / Exception Flow:</strong><br>
        - A1) Listing has an active reservation/order: The system blocks archiving and prompts the seller to complete/cancel the active transaction first.<br>
        - A2) Archive failed (network/server issue): The system shows an error message and allows the seller to retry.<br><br>
        <strong>Outcome:</strong> <strong>Success:</strong> The listing is archived, removed from public view, and preserved in the system for tracking and reference.
      </p>
    </td>
  </tr>
  <tr>
    <td colspan="2" align="center">© 2026 Restora</td>
  </tr>
</table>
