<h2>Anvil</h2>
<p><strong>Target:</strong> <code>AV.010.001</code></p>

<table border="1" cellpadding="0" cellspacing="0" style="width: 90%; font-size: 12px;">
  <tr>
    <!-- LEFT: SITE MAP -->
    <td valign="top" style="width: 28%; padding: 10px;">
      <h3 style="margin-top:0;">Site Map</h3>
      <a href="../homepage/project-homepage.md">Homepage</a>
      <p style="margin:10px 0 6px;"><strong>1. Authentication &amp; Access Control</strong></p>
      <ul style="margin-top:0;">
        <li><a href="../authentication/authentication.md">Authentication (FR0.0)</a></li>
      </ul>
      <p style="margin:10px 0 6px;"><strong>2. User Account &amp; Profile Management</strong></p>
      <ul style="margin-top:0;">
        <li><a href="../profile/view-profile.md">View Profile (FR1.0)</a></li>
        <li><a href="../profile/edit-profile.md">Edit Profile (FR1.0)</a></li>
      </ul>
      <p style="margin:10px 0 6px;"><strong>3. Listings</strong></p>
      <ul style="margin-top:0;">
        <li><a href="../listings/browse-listings.md">Browse Listings (FR4.0)</a></li>
        <li><a href="../listings/search-filter.md">Search &amp; Filters (FR4.0)</a></li>
        <li><a href="../listings/view-listing-details.md">View Listing Details (FR4.0)</a></li>
        <li><a href="../listings/create-listing.md">Create Listing (FR2.0)</a></li>
        <li><a href="../listings/edit-listing.md">Edit Listing (FR2.0)</a></li>
        <li><a href="../listings/archive-listing.md">Archive Listing (FR2.0)</a></li>
      </ul>
      <p style="margin:10px 0 6px;"><strong>4. Orders / Reservations</strong></p>
      <ul style="margin-top:0;">
        <li><a href="../orders/reserve-item.md">Reserve Item (FR5.0)</a></li>
        <li><a href="../orders/accept-decline-reservation.md">Accept/Decline Reservation (FR5.0)</a></li>
        <li><a href="../orders/view-order-status.md">View Order Status (FR5.0)</a></li>
        <li><a href="../orders/update-order-status.md">Update Order Status (FR5.0)</a></li>
      </ul>
      <p style="margin:10px 0 6px;"><strong>5. Order Chat &amp; Pickup Info</strong></p>
      <ul style="margin-top:0;">
        <li><a href="../chat/order-chat.md">Order Chat (FR6.0)</a></li>
        <li><a href="../chat/pickup-details.md">Pickup/Delivery Details (FR6.0)</a></li>
      </ul>
      <p style="margin:10px 0 6px;"><strong>6. Notifications</strong></p>
      <ul style="margin-top:0;">
        <li><a href="../notifications/receive-notification.md">Receive Notifications (FR9.0)</a></li>
        <li><a href="../notifications/email-alerts.md">Email Alerts (FR9.0)</a></li>
      </ul>
      <p style="margin:10px 0 6px;"><strong>7. Reports &amp; Enforcement</strong></p>
      <ul style="margin-top:0;">
        <li><a href="../reports/report-listing-user.md">Report Listing/User (FR8.0)</a></li>
        <li><a href="../reports/review-reports.md">Review Reports (FR8.0)</a></li>
        <li><a href="../reports/apply-sanctions.md">Warn/Suspend/Ban (FR8.0)</a></li>
      </ul>
      <p style="margin:10px 0 6px;"><strong>8. Verification, Moderation &amp; Audit</strong></p>
      <ul style="margin-top:0;">
        <li><a href="../admin/verify-seller.md">Verify Seller Accounts (FR7.0)</a></li>
        <li><a href="../admin/review-listings.md">Approve/Reject Listings (FR7.0)</a></li>
        <li><a href="../audit/view-audit-logs.md">View Activity Logs (FR10.0)</a></li>
      </ul>
    </td>
    <td valign="top" style="width: 72%; padding: 10px;">
      <p><a href="../homepage/project-homepage.md">Homepage</a> &gt; <strong>Authentication</strong></p>
      <p><strong>Login / Sign up Screen</strong></p>
      <img src="../assets/authentication.png" alt="Authentication Screen (mockup)" style="max-width:100%; border:1px solid #000;">
      <h2>Authentication &amp; Access Control (FR0.0)</h2>
      <p>
        This feature controls user access to the system by allowing buyers, sellers, and administrators to register, sign in, sign out,
        and recover accounts through password reset. It ensures that protected actions—such as reserving items, creating listings,
        responding to reservations, and performing moderation—are only available to verified and logged-in users based on their role.
        After successful login, the system loads the appropriate interface and permissions for the user type.
      </p>
      <h2>Use Case Scenario</h2>
      <table border="1" cellpadding="6" cellspacing="0" style="width:100%; font-size:12px;">
        <tr>
          <th style="width: 22%;">Actor(s)</th>
          <td>Guest, Buyer, Seller, System Administrator</td>
        </tr>
        <tr>
          <th>Goal</th>
          <td>To securely access the system and enable role-based features after authentication.</td>
        </tr>
        <tr>
          <th>Preconditions</th>
          <td>
            1. The user has access to the application URL.<br>
            2. The user has a registered account (for sign in) or valid details to create an account (for sign up).<br>
            3. The system authentication service is available.
          </td>
        </tr>
        <tr>
          <th>Main Scenario</th>
          <td>
            1. The user selects <strong>Sign up</strong> or <strong>Sign in</strong> from the application.<br>
            2. If signing up, the user provides required information and submits the registration form.<br>
            3. The system validates inputs and creates an account, then assigns a default role (buyer/seller) based on selection.<br>
            4. If signing in, the user enters email/username and password, then submits the form.<br>
            5. The system validates credentials and starts a user session.<br>
            6. The system redirects the user to the homepage and loads role-based navigation and permissions.<br>
            7. If the user selects <strong>Logout</strong>, the system ends the session and returns the user to public browsing mode.<br>
            8. If the user selects <strong>Forgot Password</strong>, the system sends a reset link/instructions and allows the user to set a new password.
          </td>
        </tr>
        <tr>
          <th>Alternative / Exception Flow</th>
          <td>
            A1. Invalid credentials: The system shows an error message and keeps the user on the login page.<br>
            A2. Duplicate account: The system informs the user that the email is already registered.<br>
            A3. Reset link expired/invalid: The system prompts the user to request a new password reset link.
          </td>
        </tr>
        <tr>
          <th>Outcome</th>
          <td><strong>Success:</strong> The user is authenticated and can access only the features allowed by their role.</td>
        </tr>
      </table>
    </td>
  </tr>

  <tr>
    <td colspan="2" align="center">© 2026 Restora</td>
  </tr>
</table>
