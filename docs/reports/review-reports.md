<h2>Anvil</h2>
<p><strong>Target:</strong> <code>AV.010.001</code></p>

<table border="1" cellpadding="0" cellspacing="0" style="width: 90%; font-size: 12px;">
  <tr>
    <!--Left Sidebar - Site Map -->
    <td valign="top" style="width: 28%; padding: 10px;">
      <h3 style="margin-top:0;">Site Map</h3>
      <a href="../homepage/project-homepage.md">Homepage</a>
      <!--Authentication & Access Control-->
      <p style="margin:10px 0 6px;"><strong>1. Authentication &amp; Access Control</strong></p>
      <ul style="margin-top:0;">
        <li><a href="../authentication/authentication.md">Authentication (FR0.0)</a></li>
      </ul>
      <!-- User Account & Profile Management -->
      <p style="margin:10px 0 6px;"><strong>2. User Account &amp; Profile Management</strong></p>
      <ul style="margin-top:0;">
        <li><a href="../profile/view-profile.md">View Profile (FR1.0)</a></li>
        <li><a href="../profile/edit-profile.md">Edit Profile (FR1.0)</a></li>
      </ul>
      <!-- Listings -->
      <p style="margin:10px 0 6px;"><strong>3. Listings</strong></p>
      <ul style="margin-top:0;">
        <!-- FR4.0 -->
        <li><a href="../listings/browse-listings.md">Browse Listings (FR4.0)</a></li>
        <li><a href="../listings/search-filter.md">Search &amp; Filters (FR4.0)</a></li>
        <li><a href="../listings/view-listing-details.md">View Listing Details (FR4.0)</a></li>
        <!-- FR2.0 -->
        <li><a href="../listings/create-listing.md">Create Listing (FR2.0)</a></li>
        <li><a href="../listings/edit-listing.md">Edit Listing (FR2.0)</a></li>
        <li><a href="../listings/archive-listing.md">Archive Listing (FR2.0)</a></li>
        <!-- FR3.0 (ADDED) -->
        <li><a href="../listings/auto-soldout-expiry.md">Auto Sold-out &amp; Expiry Handling (FR3.0)</a></li>
      </ul>
      <!-- Orders / Reservation -->
      <p style="margin:10px 0 6px;"><strong>4. Orders / Reservations</strong></p>
      <ul style="margin-top:0;">
        <li><a href="../orders/reserve-item.md">Reserve Item (FR5.0)</a></li>
        <li><a href="../orders/accept-decline-reservation.md">Accept/Decline Reservation (FR5.0)</a></li>
        <li><a href="../orders/view-order-status.md">View Order Status (FR5.0)</a></li>
        <li><a href="../orders/update-order-status.md">Update Order Status (FR5.0)</a></li>
      </ul>
      <!-- Order Chat & Pickup Info-->
      <p style="margin:10px 0 6px;"><strong>5. Order Chat &amp; Pickup Info</strong></p>
      <ul style="margin-top:0;">
        <li><a href="../chat/order-chat.md">Order Chat (FR6.0)</a></li>
        <li><a href="../chat/pickup-details.md">Pickup/Delivery Details (FR6.0)</a></li>
      </ul>
      <!-- Notifications -->
      <p style="margin:10px 0 6px;"><strong>6. Notifications</strong></p>
      <ul style="margin-top:0;">
        <li><a href="../notifications/receive-notification.md">Receive Notifications (FR9.0)</a></li>
        <li><a href="../notifications/email-alerts.md">Email Alerts (FR9.0)</a></li>
      </ul>
      <!-- Reports & Enforcement -->
      <p style="margin:10px 0 6px;"><strong>7. Reports &amp; Enforcement</strong></p>
      <ul style="margin-top:0;">
        <li><a href="reports-listing-user.md">Report Listing/User (FR8.0)</a></li>
        <li><strong>Review Reports (FR8.0)</strong></li>
        <li><a href="apply-sanctions.md">Warn/Suspend/Ban (FR8.0)</a></li>
      </ul>
      <!--Verification, Moderation, and Audit -->
      <p style="margin:10px 0 6px;"><strong>8. Verification, Moderation &amp; Audit</strong></p>
      <ul style="margin-top:0;">
        <li><a href="../admin/verify-seller.md">Verify Seller Accounts (FR7.0)</a></li>
        <li><a href="../admin/review-listings.md">Approve/Reject Listings (FR7.0)</a></li>
        <li><a href="../audit/view-audit-logs.md">View Activity Logs (FR10.0)</a></li>
      </ul>
    </td>
    <!-- Right SideBar - Content -->
    <td valign="top" style="width: 72%; padding: 10px;">
      <p><a href="../homepage/project-homepage.md">Homepage</a> &gt; <strong>Review Reports</strong></p>
      <img src="../../assets/img/review-reports.png" alt="Review Report Page" style="max-width:100%; border:1px solid #000;">
       <h2>Review Reports (FR8.0)</h2>
      <p>
      The Review Report feature serves as a comprehensive administrative tool that empowers platform administrators to thoroughly examine, assess, and verify user-submitted reports with precision and efficiency. This critical functionality enables admins to systematically investigate flagged content, user behavior, and potential policy violations, allowing them to make informed decisions that help maintain the platform's integrity and ensure the application runs smoothly without causing unnecessary disruptions or disturbances to the broader user community. 
      </p>
      By providing administrators with detailed insights into reported issues, including context, timestamps, and relevant user interactions, this feature facilitates swift and appropriate action against violations while protecting innocent users from false accusations. This feature is absolutely essential for maintaining robust community standards, fostering a positive user experience, and ensuring a safe, trustworthy, and welcoming platform where all users can interact with confidence. The streamlined review process not only reduces response times but also ensures consistency in enforcement across the platform, acting as the backbone of content moderation that helps create an environment where quality interactions flourish and problematic behavior is promptly addressed, ultimately contributing to the long-term success and sustainability of the platform.
      </p>
      <h2>Use Case Scenario</h2>
      <table border="1" cellpadding="6" cellspacing="0" style="width:100%; font-size:12px;">
        <tr>
          <th style="width: 22%;">Actors(s)</th>
          <td>
            <ol style="padding-left: 0; margin-left: 10; list-style-type: decimal;">
              <li>Administrator</li>
            <ol>
          </td>
        </tr>
        <tr>
          <th>Goal</th>
          <td>It enable administrators to efficiently verify user reports, maintain community standards, and ensure a safe, trustworthy platform by promptly addressing violations and minimizing user disruptions.</td>
        </tr>
        <tr>
          <th>Preconditions</th>
          <td>
            <ol  style="padding-left: 0; margin-left: 10; list-style-type: decimal;">
              <li>The administrator is logged in</li>
              <li>The administrator has internet connection</li>
            </ol>
          </td>
        </tr>
        <tr>
          <th>Main Scenario</th>
          <td>
            <ol style="padding-left: 0; margin-left: 10; list-style-type: decimal;">
              <li>The administrator navigates to the <strong>Review Reports</strong> section from the navigation menu.</li>
              <li>The system displays a list of pending reports, including details such as the reported content, user, reason for the report, and status.</li>
              <li>The admin selects a report to review and examines the content, user behavior, and context.<br></li>
              <li>The admin assesses whether the report violates community guidelines based on the platform's policies.</li>
              <li> If the report is valid, the admin proceeds to the <strong>Apply Sanction</strong> feature to take action.</li>
              <li> If the report is invalid or lacks sufficient evidence, the admin selects <strong>Dismiss</strong> and provides a reason.</li>
              <li> The system updates the report status to "Resolved" and notifies the user who submitted the report.</li>
              <li>The admin may continue reviewing additional reports or close the review session.</li>
            </ol>
          </td>
        </tr>
      </table>
  </tr>
  <tr>
    <td colspan="2" align="center">© 2026 Restora</td>
  </tr>
</table>
