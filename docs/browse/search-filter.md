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
        <li><a href="browse-listings.md">Browse Listings (FR5.0)</a></li>
        <li><strong>Search &amp; Filters (FR5.0)</strong></li>
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
    <p><a href="../homepage/project-homepage.md">Homepage</a> &gt; <strong>Search &amp; Filters (FR5.0)</strong></p>
    <h3 style="margin-top:0;">Search &amp; Filters (FR5.0)</h3>
    <h2>Search &amp; Filters (FR5.0)</h2>
    <p>
      The Search &amp; Filters feature helps buyers quickly find relevant listings by allowing them to search by keywords and refine results using filter options. Users can narrow listings based on category, location, availability status, pickup schedule/time, and other listing attributes supported by the platform. This improves browsing efficiency and helps buyers discover listings that match their needs.
    </p>
    <h2>Use Case Scenario</h2>
    <p>
      <strong>Actor(s):</strong> Buyer<br>
      <strong>Goal:</strong> To search and filter listings so the buyer can quickly find items that match their preferences and pickup constraints.<br><br>
      <strong>Preconditions:</strong>
      <ol>
        <li>The buyer is on the Browse Listings page</li>
        <li>There are active listings available in the system</li>
        <li>The platform has search and filter options enabled</li>
      </ol>
      <strong>Main Scenario:</strong><br>
      <ol>
        <li>The buyer navigates to the Browse Listings page</li>
        <li>The system displays the search bar and available filter controls</li>
        <li>The buyer enters a keyword in the search bar (e.g., item name or category)</li>
        <li>The buyer selects one or more filters (e.g., category, location, pickup schedule, availability)</li>
        <li>The system applies the search and filters and refreshes the listing results</li>
        <li>The buyer reviews the filtered results and selects a listing to view details</li>
        <li>The buyer adjusts filters as needed to refine results further</li>
      </ol>
      <strong>Alternative / Exception Flow:</strong><br>
      - A1) No results found: The system shows a “No listings found” message and suggests clearing or adjusting filters.<br>
      - A2) Search failed (network/server issue): The system shows an error message and allows the buyer to retry.<br><br>
      <strong>Outcome:</strong> <strong>Success:</strong> The buyer successfully narrows listings and finds an item that matches their needs.
    </p>
  </td>
  </tr>

  <tr>
    <td colspan="2" align="center">© 2026 Anvil</td>
  </tr>
</table>
