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
        <li><a href="reserve-item.md">Reserve Item (FR6.0)</a></li>
        <li><strong>Accept/Decline Reservation (FR6.0)</strong></li>
        <li><a href="update-order-status.md">Update Order Status (FR6.0)</a></li>
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
    <!-- Right SideBar - Content -->
    <td valign="top" style="width: 72%; padding: 10px;">
      <p><a href="../homepage/project-homepage.md">Homepage</a> &gt; <strong>Accept/Decline Reservation (FR6.0)</strong></p>
    <h3 style="margin-top:0;">Accept/Decline Reservation (FR6.0)</h3>
    <h2>Accept/Decline Reservation (FR6.0)</h2>
    <p>
      The Accept/Decline Reservation feature allows the seller to respond to a buyer’s reservation request for a listed item. If accepted, the system confirms the reservation and updates the order status so both parties can proceed with pickup coordination. If declined, the system rejects the request, notifies the buyer, and keeps the listing available for other buyers if applicable.
    </p>
    <h2>Use Case Scenario</h2>
    <p>
      <strong>Actor(s):</strong> Seller<br>
      <strong>Goal:</strong> To approve or reject a buyer’s reservation request so the system can update the reservation status and notify both parties.<br><br>
      <strong>Preconditions:</strong>
      <ol>
        <li>The seller is logged in</li>
        <li>The buyer has submitted a reservation request for an item listing</li>
        <li>The listing is still available and not expired/archived</li>
      </ol>
      <strong>Main Scenario:</strong><br>
      <ol>
        <li>The seller opens the Orders/Reservations section to view pending requests</li>
        <li>The system displays reservation details (buyer, item, quantity, and request time)</li>
        <li>The seller selects <strong>Accept</strong> or <strong>Decline</strong></li>
        <li>If <strong>Accept</strong> is chosen, the system confirms the reservation and updates the status to <strong>Accepted</strong></li>
        <li>If <strong>Decline</strong> is chosen, the system rejects the reservation and updates the status to <strong>Declined</strong></li>
        <li>The system notifies the buyer of the seller’s decision</li>
        <li>The system reflects the updated status in both the buyer and seller order views</li>
      </ol>
      <strong>Alternative / Exception Flow:</strong><br>
      - A1) Listing becomes unavailable (sold out/expired) before action: The system blocks the action and informs the seller that the request can no longer be processed.<br>
      - A2) Action failed (network/server issue): The system shows an error message and allows the seller to retry.<br><br>
      <strong>Outcome:</strong> <strong>Success:</strong> The reservation is accepted or declined, the status is updated, and the buyer is informed of the result.
    </p>
    </td>
  </tr>
  <tr>
    <td colspan="2" align="center">© 2026 Restora</td>
  </tr>
</table>
