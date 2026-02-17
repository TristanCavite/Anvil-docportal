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
        <li><strong>Auto Sold-out / Expiry Handling (FR4.0)</strong></li>
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
    <!-- RIGHT: KEEP YOUR REVISIONS OR OTHER CONTENT -->
    <td valign="top" style="width: 72%; padding: 10px;">
      <p><a href="../homepage/project-homepage.md">Homepage</a> &gt; <strong>Auto Sold-out / Expiry Handling (FR4.0)</strong></p>
      <h3 style="margin-top:0;">Auto Sold-out / Expiry Handling (FR4.0)</h3>
      <h2>Auto Sold-out / Expiry Handling (FR4.0)</h2>
      <p>
        The Auto Sold-out / Expiry Handling feature automatically updates a listing’s availability to prevent buyers from reserving items that are no longer valid. When a listing reaches zero remaining quantity, the system marks it as <strong>Sold Out</strong>. When the pickup deadline or expiry time is reached, the system marks the listing as <strong>Expired</strong> and removes it from active browsing and reservation flows.
      </p>
      <h2>Use Case Scenario</h2>
      <p>
        <strong>Actor(s):</strong> System, Seller, Buyer<br>
        <strong>Goal:</strong> To automatically update listing status (Sold Out/Expired) so only available and valid listings are shown and reservable.<br><br>
        <strong>Preconditions:</strong>
        <ol>
          <li>A listing exists with defined quantity and/or expiry/pickup deadline</li>
          <li>The listing is currently active (not archived)</li>
          <li>The system is able to evaluate listing quantity and time conditions</li>
        </ol>
        <strong>Main Scenario:</strong><br>
        <ol>
          <li>The system monitors active listings for quantity changes and expiry deadlines</li>
          <li>When reservations reduce the remaining quantity to zero, the system updates the listing status to <strong>Sold Out</strong></li>
          <li>When the expiry time or pickup deadline is reached, the system updates the listing status to <strong>Expired</strong></li>
          <li>The system hides sold-out/expired listings from Browse and Search results</li>
          <li>The system blocks new reservation attempts for sold-out/expired listings and shows an appropriate message</li>
          <li>If configured, the system notifies the seller (and affected buyers) about the status change</li>
        </ol>
        <strong>Alternative / Exception Flow:</strong><br>
        - A1) Status update failed (network/server issue): The system logs the error and retries the update until successful.<br>
        - A2) Listing is manually archived before expiry: The system treats the listing as inactive and skips automated status changes.<br><br>
        <strong>Outcome:</strong> <strong>Success:</strong> Listings are automatically marked sold out or expired, preventing invalid reservations and keeping browsing results accurate.
      </p>
    </td>
  </tr>
  <tr>
    <td colspan="2" align="center">© 2026 Anvil</td>
  </tr>
</table>
