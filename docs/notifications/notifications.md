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
        <li><a href="../reports/report-listing-user.md">Report Listing/User (FR9.0)</a></li>
        <li><a href="../reports/review-reports.md">Review Reports (FR9.0)</a></li>
        <li><a href="../reports/apply-sanctions.md">Warn/Suspend/Ban (FR9.0)</a></li>
      </ul>
      <!--Notifications & Email Alerts-->
      <p style="margin:10px 0 6px;"><strong>10. Notifications &amp; Email Alerts</strong></p>
      <ul style="margin-top:0;">
        <li><strong>Notifications &amp; Alerts (FR10.0)</strong></li>
      </ul>
      <!--Activity Logging & Audit Trail-->
      <p style="margin:10px 0 6px;"><strong>11. Activity Logging &amp; Audit Trail</strong></p>
      <ul style="margin-top:0;">
        <li><a href="../audit/view-audit-logs.md">View Activity Logs (FR11.0)</a></li>
      </ul>
    </td>
    <!-- RIGHT: KEEP YOUR REVISIONS OR OTHER CONTENT -->
    <td valign="top" style="width: 72%; padding: 10px;">
      <p><a href="../homepage/project-homepage.md">Homepage</a> &gt; <strong>Notifications &amp; Alerts (FR10.0)</strong></p>
      <h3 style="margin-top:0;">Notifications &amp; Alerts (FR10.0)</h3>
      <h2>Notifications &amp; Alerts (FR10.0)</h2>
      <p>
        The Notifications &amp; Alerts feature informs users about important platform updates and actions that require attention. The system sends in-app notifications (and email alerts when applicable) for events such as reservation requests, reservation decisions (accepted/declined), order status updates, report outcomes, and account-related updates. This helps users respond on time and stay updated without repeatedly checking the platform.
      </p>
      <h2>Use Case Scenario</h2>
      <p>
        <strong>Actor(s):</strong> Buyer, Seller, Administrator<br>
        <strong>Goal:</strong> To deliver timely notifications to users so they are aware of important actions and status updates within the platform.<br><br>
        <strong>Preconditions:</strong>
        <ol>
          <li>The user is logged in (for in-app notifications)</li>
          <li>A triggering event occurs (e.g., reservation request, order status change, report action)</li>
          <li>The user has notification access enabled (and a valid email if email alerts are used)</li>
        </ol>
        <strong>Main Scenario:</strong><br>
        <ol>
          <li>A system event triggers a notification (e.g., new reservation request, reservation accepted/declined, order status updated)</li>
          <li>The system creates a notification record and assigns it to the target user(s)</li>
          <li>The system displays the notification in the user’s Notifications panel (with unread status)</li>
          <li>If configured, the system sends an email alert containing a brief summary and link to the related page</li>
          <li>The user opens the Notifications panel and selects a notification to view details</li>
          <li>The system redirects the user to the related page (order, listing, report, or account page)</li>
          <li>The system marks the notification as read after it is opened</li>
        </ol>
        <strong>Alternative / Exception Flow:</strong><br>
        - A1) Email delivery failed (invalid email/server issue): The system logs the failure and continues to provide the in-app notification.<br>
        - A2) User is offline: The notification remains queued/unread and is shown once the user logs in.<br><br>
        <strong>Outcome:</strong> <strong>Success:</strong> The user receives the notification and can access the related information or action promptly.
      </p>
    </td>
  </tr>
  <tr>
    <td colspan="2" align="center">© 2026 Anvil</td>
  </tr>
</table>
