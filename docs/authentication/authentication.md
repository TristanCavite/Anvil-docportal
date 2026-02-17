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
            <li><strong>Authentication (FR1.0)</strong></li>
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
            <li><a href="../notifications/notifications.md">Notifications &amp; Alerts (FR10.0)</a></li>
          </ul>
          <!--Activity Logging & Audit Trail-->
          <p style="margin:10px 0 6px;"><strong>11. Activity Logging &amp; Audit Trail</strong></p>
          <ul style="margin-top:0;">
            <li><a href="../audit/view-audit-logs.md">View Activity Logs (FR11.0)</a></li>
          </ul>
        </td>
    <!-- Right Sidebar - Authentication Content -->
    <td valign="top" style="width: 72%; padding: 10px;">
      <p><a href="../homepage/project-homepage.md">Homepage</a> &gt; <strong>Authentication (FR1.0)</strong></p>
      <p><strong>Authentication Screen (Login / Sign up / Forgot Password)</strong></p>
      <img src="/assets/Login.png" alt="Authentication Screen (mockup)" style="max-width:100%; border:1px solid #000;">
      <h2>Authentication &amp; Access Control (FR0.0)</h2>
      <p>
        This feature controls access to NeighborGoods by allowing users (buyers, sellers, and administrators) to register, sign in,
        sign out, and reset passwords. It ensures that protected actions—such as reserving items, creating/editing listings,
        accepting/declining reservations, starting order chats, and performing admin moderation—are only available to authenticated
        users based on role permissions. After a successful login, the system loads the correct navigation and capabilities for the
        user type (Buyer/Seller/Admin).
      </p>
      <h2>Use Case Scenario</h2>
      <table border="1" cellpadding="6" cellspacing="0" style="width:100%; font-size:12px;">
        <tr>
          <th style="width: 22%;">Actor(s)</th>
          <td>Guest, Buyer, Seller, System Administrator</td>
        </tr>
        <tr>
          <th>Goal</th>
          <td>To securely authenticate a user and grant role-based access to NeighborGoods features.</td>
        </tr>
        <tr>
          <th>Preconditions</th>
          <td>
            1. The user has access to the application URL.<br>
            2. For Sign in: the user has a registered account.<br>
            3. For Sign up: the user can provide required registration details.<br>
            4. The authentication service is available.
          </td>
        </tr>
        <tr>
          <th>Main Scenario</th>
          <td>
            1. The user opens the Authentication screen.<br>
            2. The user selects <strong>Sign up</strong> or <strong>Sign in</strong>.<br>
            3. If signing up, the user fills in the required details and chooses an account type (Buyer/Seller).<br>
            4. The system validates the input and creates a new account.<br>
            5. If signing in, the user enters email/username and password, then submits the form.<br>
            6. The system validates the credentials and starts a session.<br>
            7. The system redirects the user to the Homepage and loads role-based navigation and permissions.<br>
            8. If the user selects <strong>Logout</strong>, the system ends the session and returns the user to public browsing mode.<br>
            9. If the user selects <strong>Forgot Password</strong>, the system sends reset instructions and allows the user to set a new password.
          </td>
        </tr>
        <tr>
          <th>Alternative / Exception Flow</th>
          <td>
            A1. Invalid credentials: The system shows an error message and stays on the Sign in page.<br>
            A2. Duplicate account: The system informs the user that the email is already registered.<br>
            A3. Invalid/expired reset link: The system requests the user to generate a new password reset link.<br>
            A4. Missing/invalid fields: The system highlights required fields and blocks submission until valid.
          </td>
        </tr>
        <tr>
          <th>Outcome</th>
          <td><strong>Success:</strong> The user is authenticated and can access features allowed by their role.</td>
        </tr>
      </table>
    </td>
  </tr>

  <tr>
    <td colspan="2" align="center">© 2026 Restora</td>
  </tr>
</table>
