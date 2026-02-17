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
      <img src="../../assets/img/report-listing-user.png" alt="Report Listing Page" style="max-width:70%; border:1px solid #000;">
      <h2>Reports Listing User (FR8.0)</h2>
      <p>
      The Report Listing Feature enables users to easily file reports about content or behavior that violates community guidelines, ensuring a safe and trustworthy platform for all. Users can access the reporting functionality through a simple interface, where they can select the type of issue (e.g., hate speech, spam, harassment, misinformation), provide a brief description, and submit the report. This feature empowers users to take an active role in maintaining community standards by flagging inappropriate content or behavior, contributing to a more respectful and secure environment. The process is designed to be intuitive and accessible, encouraging users to report issues promptly and confidently.
      </p>
      Once a report is submitted, users can view the status of their report through the Report Listing Feature, which provides transparency and reassurance. The system displays the current status of each report—such as "Pending," "Under Review," or "Resolved"—along with any updates or actions taken by administrators. This visibility helps users feel heard and informed, fostering trust in the platform’s moderation process. By giving users control over reporting and keeping them updated, the feature strengthens community engagement and promotes a culture of shared responsibility in maintaining a safe and positive online experience.
      </p>
      <h2>Use Case Scenario</h2>
      <p>
        <strong>Actor(s):</strong> Buyer, Seller<br>
        <strong>Goal:</strong> To submit a report about a listing or user so administrators can review potential violations and the reporter can track the report status.<br><br>
        <strong>Preconditions:</strong>
        <ol>
          <li>The user is logged in</li>
          <li>The user can access the listing or user profile to be reported</li>
        </ol>
        <strong>Main Scenario:</strong><br>
        <ol>
          <li>The user navigates to the listing or user profile they want to report</li>
          <li>The user selects the <strong>Report</strong> option</li>
          <li>The system displays a report form with available reasons and an optional description field</li>
          <li>The user selects a report reason and enters supporting details (optional)</li>
          <li>The user submits the report</li>
          <li>The system validates the input and creates a report with status <strong>Pending</strong></li>
          <li>The system confirms submission and notifies administrators that a new report is available for review</li>
          <li>The user views the report status in the Report Listing page (e.g., Pending, Under Review, Resolved)</li>
          <li>If the report is resolved, the system notifies the user of the outcome</li>
        </ol>
        <strong>Alternative / Exception Flow:</strong><br>
        - A1) Duplicate report for the same content/user: The system warns the user and prevents duplicate submission (or links to the existing report).<br>
        - A2) Missing required fields (reason/details if required): The system highlights the field and blocks submission until corrected.<br>
        - A3) Submission failed (network/server issue): The system shows an error message and allows the user to retry.<br><br>
        <strong>Outcome:</strong> <strong>Success:</strong> A report is submitted successfully, tracked in the system, and visible to the user for status updates.
      </p>
    </td>
  </tr>
  <tr>
    <td colspan="2" align="center">© 2026 Restora</td>
  </tr>
</table>
