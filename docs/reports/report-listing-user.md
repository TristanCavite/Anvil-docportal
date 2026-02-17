<h2>Anvil</h2>
<p><strong>Target:</strong> <code>AV.010.001</code></p>

<table border="1" cellpadding="0" cellspacing="0" style="width: 90%; font-size: 12px;">
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
        <li><strong>Report Listing/User (FR9.0)</strong></li>
        <li><a href="review-reports.md">Review Reports (FR9.0)</a></li>
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
      <p><a href="../homepage/project-homepage.md">Homepage</a> &gt; <strong>Report Listing</strong></p>
      <img src="../../assets/img/report-listing-user.png" alt="Report Listing Page" style="max-width:100%; border:1px solid #000;">
      <h2>Reports Listing User (FR8.0)</h2>
      <p>
      The Report Listing Feature enables users to easily file reports about content or behavior that violates community guidelines, ensuring a safe and trustworthy platform for all. Users can access the reporting functionality through a simple interface, where they can select the type of issue (e.g., hate speech, spam, harassment, misinformation), provide a brief description, and submit the report. This feature empowers users to take an active role in maintaining community standards by flagging inappropriate content or behavior, contributing to a more respectful and secure environment. The process is designed to be intuitive and accessible, encouraging users to report issues promptly and confidently.
      </p>
      Once a report is submitted, users can view the status of their report through the Report Listing Feature, which provides transparency and reassurance. The system displays the current status of each report—such as "Pending," "Under Review," or "Resolved"—along with any updates or actions taken by administrators. This visibility helps users feel heard and informed, fostering trust in the platform’s moderation process. By giving users control over reporting and keeping them updated, the feature strengthens community engagement and promotes a culture of shared responsibility in maintaining a safe and positive online experience.
      </p>
      <h2>Use Case Scenario</h2>
      <table border="1" cellpadding="6" cellspacing="0" style="width:100%; font-size:12px;">
        <tr>
          <th style="width: 22%;">Actors(s)</th>
          <td>
            <ol style="padding-left: 0; margin-left: 10; list-style-type: decimal;">
              <li>Buyer</li>
              <li>Seller</li>
            <ol>
          </td>
        </tr>
        <tr>
          <th>Goal</th>
          <td>To empower users to easily file reports about inappropriate content or behavior, while providing transparency and visibility into the status of their reports, thereby fostering a safe, trustworthy, and community-driven platform.</td>
        </tr>
        <tr>
          <th>Preconditions</th>
          <td>
            <ol  style="padding-left: 0; margin-left: 10; list-style-type: decimal;">
              <li>The user is logged in</li>
              <li>The user has internet connection</li>
            </ol>
          </td>
        </tr>
        <tr>
          <th>Main Scenario</th>
          <td>
            <ol style="padding-left: 0; margin-left: 10; list-style-type: decimal;">
              <li>The user navigates to the content or profile they wish to report.</li>
              <li>The user selects the <strong>Report</strong> option, typically found in a menu or as a button on the content or user profile.</li>
              <li> The system displays a report form where the user can select the reason for the report (e.g., hate speech, harassment, misinformation, spam).</li>
              <li>The user provides additional details, such as a brief description of the issue, and submits the report.</li>
              <li>The system confirms the report submission and displays a message indicating that the report has been sent to administrators for review.</li>
              <li>The user can view the status of their report through the Report Listing Feature, which shows the current status (e.g., "Pending," "Under Review," "Resolved").</li>
              <li>If the report is resolved, the user receives a notification or update about the outcome.</li>
              <li>The user may choose to file additional reports if needed.</li>
            </ol>
          </td>
        </tr>
      </table>
    </td>
  </tr>
  <tr>
    <td colspan="2" align="center">© 2026 Restora</td>
  </tr>
</table>
