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
        <li><a href="review-reports.md">Review Reports (FR9.0)</a></li>
        <li><strong>Warn/Suspend/Ban (FR9.0)</strong></li>
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
      <p><a href="../homepage/project-homepage.md">Homepage</a> &gt; <strong>Warn/Suspend/Ban</strong></p>
      <img src="../../assets/img/apply-sanction.png" alt="Review Report Page" style="max-width:70%; border:1px solid #000;">
      <h2>Apply Sanctions (FR8.0)</h2>
      <p>
      The Apply Sanction feature enables administrators to enforce community guidelines by applying appropriate penalties to users who violate platform policies. This functionality allows moderators to take decisive action based on the severity of the violation, ensuring that the platform remains safe and trustworthy for all users. Admins can choose from a range of sanctions, such as content removal, warnings, temporary suspensions, or permanent bans, depending on the nature of the offense. The system logs all actions taken, providing a transparent and auditable trail that ensures accountability and consistency in moderation. By empowering administrators with clear, actionable tools, the Apply Sanction feature helps maintain order, deter future violations, and uphold the integrity of the community.
      </p>
      Beyond individual enforcement, the feature supports a fair and consistent moderation process by allowing admins to review the context of each violation before applying sanctions. This includes assessing the history of the user, the impact of the reported behavior, and any prior warnings. The system also notifies the affected user of the sanction, ensuring transparency and giving them the opportunity to appeal if necessary. This structured approach fosters trust in the moderation system, reduces ambiguity, and helps users understand the consequences of their actions. Ultimately, the Apply Sanction feature plays a critical role in maintaining a positive, respectful, and compliant environment where all users can engage confidently and safely.
      </p>
      <h2>Use Case Scenario</h2>
      <p>
        <strong>Actor(s):</strong> Administrator<br>
        <strong>Goal:</strong> To apply an appropriate sanction to a user who violated platform policies so enforcement is consistent and the community remains safe.<br><br>
        <strong>Preconditions:</strong>
        <ol>
          <li>The administrator is logged in</li>
          <li>A report has been reviewed and confirmed as a valid policy violation</li>
        </ol>
        <strong>Main Scenario:</strong><br>
        <ol>
          <li>The administrator opens a report with a confirmed violation</li>
          <li>The system displays the report details, evidence/context, and the reported user’s account information</li>
          <li>The administrator reviews the severity of the violation and checks the user’s prior warnings or sanctions</li>
          <li>The administrator selects <strong>Apply Sanction</strong></li>
          <li>The system displays available sanction options (e.g., warning, content removal, temporary suspension, permanent ban)</li>
          <li>The administrator selects the appropriate sanction and enters a reason/notes for the decision</li>
          <li>The administrator submits the sanction action</li>
          <li>The system applies the sanction, updates the user’s account status accordingly, and records the action in the activity log</li>
          <li>The system notifies the affected user of the sanction and the reason</li>
          <li>The system updates the related report status to <strong>Resolved</strong> and closes the case</li>
        </ol>
        <strong>Alternative / Exception Flow:</strong><br>
        - A1) User is already sanctioned for the same case: The system blocks duplicate action and shows the existing sanction details.<br>
        - A2) Invalid sanction selection (not allowed for the violation level): The system prompts the administrator to select a permitted sanction.<br>
        - A3) Action failed (network/server issue): The system shows an error message and allows the administrator to retry.<br><br>
        <strong>Outcome:</strong> <strong>Success:</strong> The sanction is applied, the action is logged, the user is notified, and the case is marked resolved.
      </p>
    </td>
  </tr>
  <tr>
    <td colspan="2" align="center">© 2026 Restora</td>
  </tr>
</table>
