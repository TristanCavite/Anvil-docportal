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
        <li><a href="../listings/browse-listings.md">Browse Listings (FR4.0)</a></li>
        <li><a href="../listings/search-filter.md">Search &amp; Filters (FR4.0)</a></li>
        <li><a href="../listings/view-listing-details.md">View Listing Details (FR4.0)</a></li>
        <li><a href="../listings/create-listing.md">Create Listing (FR2.0)</a></li>
        <li><a href="../listings/edit-listing.md">Edit Listing (FR2.0)</a></li>
        <li><a href="../listings/archive-listing.md">Archive Listing (FR2.0)</a></li>
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
        <li><a href="review-reports.md">Review Reports (FR8.0)</a></li>
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
      <p><a href="../homepage/project-homepage.md">Homepage</a> &gt; <strong>Apply Sanctions</strong></p>
      <img src="" alt="Review Report Page" style="max-width:100%; border:1px solid #000;">
      <h2>Apply Sanctions (FR8.0)</h2>
      <p>
      The Apply Sanction feature enables administrators to enforce community guidelines by applying appropriate penalties to users who violate platform policies. This functionality allows moderators to take decisive action based on the severity of the violation, ensuring that the platform remains safe and trustworthy for all users. Admins can choose from a range of sanctions, such as content removal, warnings, temporary suspensions, or permanent bans, depending on the nature of the offense. The system logs all actions taken, providing a transparent and auditable trail that ensures accountability and consistency in moderation. By empowering administrators with clear, actionable tools, the Apply Sanction feature helps maintain order, deter future violations, and uphold the integrity of the community.
      </p>
      Beyond individual enforcement, the feature supports a fair and consistent moderation process by allowing admins to review the context of each violation before applying sanctions. This includes assessing the history of the user, the impact of the reported behavior, and any prior warnings. The system also notifies the affected user of the sanction, ensuring transparency and giving them the opportunity to appeal if necessary. This structured approach fosters trust in the moderation system, reduces ambiguity, and helps users understand the consequences of their actions. Ultimately, the Apply Sanction feature plays a critical role in maintaining a positive, respectful, and compliant environment where all users can engage confidently and safely.
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
          <td>To enable administrators to enforce community guidelines consistently and fairly by applying appropriate penalties to users who violate platform policies, ensuring a safe, trustworthy, and well-moderated environment for all users.</td>
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
              <li>The administrator reviews a report that has been flagged as a policy violation.</li>
              <li> The admin assesses the severity of the violation and reviews the user's history of previous violations or warnings.</li>
              <li>The admin selects the <strong>Apply Sanction</strong> option from the report details page.<br></li>
              <li>The system displays a sanction form with available options (e.g., warning, content removal, temporary suspension, permanent ban).</li>
              <li>The admin selects the appropriate sanction based on the violation severity and user history.<br>.</li>
              <li>The admin provides a reason or description for the sanction and submits the action.</li>
              <li>The system applies the sanction, logs the action in the audit trail, and notifies the affected user of the penalty and the reason.</li>
              <li>The user receives the notification and has the option to appeal the sanction if they believe it was unjust.</li>
              <li>The report status is updated to "Resolved" and the case is closed.</li>
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
