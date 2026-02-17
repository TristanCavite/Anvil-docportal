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
        <li><a href="report-listing-user.md">Report Listing/User (FR9.0)</a></li>
        <li><strong>Review Reports (FR9.0)</strong></li>
        <li><a href="apply-sanctions.md">Warn/Suspend/Ban (FR9.0)</a></li>
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
      <p><a href="../homepage/project-homepage.md">Homepage</a> &gt; <strong>Review Reports</strong></p>
      <img src="../../assets/img/review-reports.png" alt="Review Report Page" style="width:70%; aspect-ratio:16/9; object-fit:contain; background:#fff; border-radius:10px;" >
      <h2>Review Reports (FR9.0)</h2>
      <p>
        The Review Reports feature allows administrators to examine user-submitted reports and verify whether a listing or user violated platform policies. It displays key report details (reason, reported entity, context, and status) so admins can make consistent decisions. After reviewing, the admin can dismiss invalid reports or proceed to Apply Sanction for valid violations to maintain a safe and trustworthy community.
      </p>
      <h2>Use Case Scenario</h2>
      <p>
        <strong>Actor(s):</strong> Administrator<br>
        <strong>Goal:</strong> To review and validate user-submitted reports so the administrator can take appropriate action and maintain community standards.<br><br>
        <strong>Preconditions:</strong>
        <ol>
          <li>The administrator is logged in</li>
          <li>The system has at least one submitted report (pending/under review)</li>
        </ol>
        <strong>Main Scenario:</strong><br>
        <ol>
          <li>The administrator navigates to the <strong>Review Reports</strong> page from the admin menu</li>
          <li>The system displays a list of reports with key details (reported listing/user, reason, date submitted, and status)</li>
          <li>The administrator selects a report to open its full details</li>
          <li>The system displays the report context, evidence (if any), and related user/listing information</li>
          <li>The administrator evaluates whether the report violates platform policies</li>
          <li>If the report is valid, the administrator proceeds to <strong>Apply Sanction</strong> to enforce a penalty</li>
          <li>If the report is invalid or lacks evidence, the administrator selects <strong>Dismiss</strong> and provides a reason</li>
          <li>The system updates the report status to <strong>Resolved</strong> and records the decision in the activity log</li>
          <li>The system notifies the reporting user of the outcome</li>
        </ol>
        <strong>Alternative / Exception Flow:</strong><br>
        - A1) Report details cannot be loaded (network/server issue): The system shows an error and allows the administrator to retry.<br>
        - A2) Report is already resolved by another admin: The system refreshes the status and prevents duplicate actions.<br><br>
        <strong>Outcome:</strong> <strong>Success:</strong> The report is reviewed, a decision is recorded, and the reporting user is notified of the result.
      </p>
  </tr>
  <tr>
    <td colspan="2" align="center">© 2026 Restora</td>
  </tr>
</table>
