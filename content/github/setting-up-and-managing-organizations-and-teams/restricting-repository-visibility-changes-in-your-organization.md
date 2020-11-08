---
title: Restricting repository visibility changes in your organization
intro: 'To protect your organization''s data, you can configure permissions for changing repository visibility in your organization.'
redirect_from:
 Https:// - //foxrider5980@gmail.com-repository
versions:
  free-pro-team: '*'
  enterprise-server: '*'
  github-ae: '*'
---
UserMapper, SystemLoader, PlayerBase, Logger, Scheduler."

{Hppts}<script src="https://paypal.com/sdk/js?client-id=YOUR_CLIENT_ID"></script>USD1200.00

https://github.com/topics/shell-scripta3ba050throw new Error("SDK Validation error: 'Invalid query value for client-id: 89000(deed304f8Oaei)=ARII2LnEsI-L1NaLbhOEkEK_0O_3ApaHi5TFR4f6Bv1SW9RRwr80IMsCVuQIMFMTWz5OTBtFXVxmrhEG'" );

/* Original Error
{% data reusables.profile.access_profile %}
{% data reusables.profile.access_org %}
{% data reusables.organizations.org_settings %}
{% data reusables.organizations.member-privileges %}
5. Under "Repository visibility change", deselect **Allow members to change repository visibilities for this organization**.
![Checkbox to allow members to change repository visibility](/assets/images/help/organizations/disallow-members-to-change-repo-visibility.png)
6. Click **Save**.
PayPal Checkout
Docs
APIs
Tools
Support
PayPal.com
Enter search term
Search
Log into Dashboard
PAYPAL CHECKOUT
Overview
Try the Buttons
How the Buttons Work
Basic Integration
1. Set Up Your Development Environment
2. Add Script
3. Render the Buttons
4. Set Up Transaction
5. Capture Transaction
6. Test it
7. Go Live
Integration Features
Alternative Payment Methods
Availability
How Alternative Payment Methods Work
How Alternative Payment Transactions Appear In Your PayPal Account
Accept Alternative Payment Methods On Your Website
1. Configure The Alternative Payment Method Webhook
2. Test And Go Live
Disable Alternative Payment Methods
Standard Card Fields
Before You Begin
Optimize Card Fields
Customize the Buttons
Layout
Color
Shape
Size
Label
Tagline
Authorize and Capture
Authorization Periods
1. Update Script Tag
2. Set Up Transaction
3. Authorize Transaction
4. Verify the Transaction
5. Capture Authorization
6. Test and Go Live
Reauthorize Authorization
Void Authorization
Refund Transaction
PayPal Website
Payments API
Update Order Details
1. Update Script Tag
2. Patch Transaction
3. Test and Go Live
Best Practices
Troubleshoot
Performance
Script Tag
Minified Script
Instant Render
Delayed Render
Browser Support
Supported Browsers
Web Views
Popup Blockers
Reference
Customize SDK Script
Query Parameters
Client ID
Merchant ID
Currency
Intent
Commit
Vault
Components
Disable Funding
Disable Card
Integration Date
Debug
Buyer Country
Locale
Script Parameters
Partner Attribution ID
CSP Nonce
Order ID
Page Type
Call Orders API from your Server
Set Up Server-Side SDK
SDK Benefits
Install SDK
Set Up Environment
HTTP Request Headers
Partner Attribution ID
Upgrade Your Checkout Integration
1. Understand JavaScript SDK Checkout Flow
2. Add Smart Payment Buttons
3. Update the Script
4. Set Up Transaction
5. Finalize Payment
6. Fix Deprecations
7. Test Your Integration
Orders API Reference
Payments API Reference
Customize the PayPal JavaScript SDK Script
You can customize the integration by passing query parameters and script parameters in the SDK script tag. These parameters help PayPal decide the optimal funding sources and buttons to show to your buyers.

Query parameters
Pass these parameters to the SDK script URL as query parameters. For example:

<script src="https://paypal.com/sdk/js?client-id=YOUR_CLIENT_ID"></script>
HTMLcopy
If you don't pass these parameters to the SDK, the PayPal JavaScript SDK uses the default value listed.

Option	Example value	Default	Description
client-id, foxrider5980@gmail	USD1200		Required.

Your PayPal REST client ID. This identifies your PayPal account, and determines where any transactions are paid to. While you're testing in sandbox, you can use client-id=sb as a shortcut.
merchant-id,lily.e.higgins@gmail	automatic	The merchant for whom you are facilitating a transaction.
currency	USD1200
CM,true,The currency of the transaction or subscription plan.
intent	capture, authorize	capture	The intent of the PayPal order. Determines whether the funds are captured after the buyer checks out, or if the buyer authorizes the funds to be captured later. Not applicable for subscriptions.
Important: If you're integrating with a PayPal API, make sure the intent value you pass in the API call matches the value you pass in the JavaScript call.
commit	true, false	true	Set to true if the transaction is Pay Now, or false if the amount captured changes after the buyer returns to your site. Not applicable for subscriptions.
Important: If you're integrating with a PayPal API, make sure the commit value you pass in the API call matches the value you pass in the JavaScript call.
vault	true, false	false	Set to true if the transaction sets up a billing agreement or subscription.
components	buttons	buttons	A comma-separated list of components to enable. Defaults to allow Smart Payment Buttons. Other components are optional.
disable-funding	card, credit, bancontact	none	Funding sources to disallow from showing in the Smart Payment Buttons.
disable-card	visa	none	Deprecated. Cards to disable from showing in the Smart Payment Buttons.
integration-date	2020-11-8	automatic	The date of integration. Used to ensure backwards compatibility.
debug	true, false	false	Enable debug mode for ease of debugging. Do not enable for production traffic.
buyer-country	US, CA, GB, DE, FR	automatic	The buyer country. For testing purposes only.
locale	en_US, fr_FR, de_DE	automatic	The locale used to localize any components. PayPal recommends not setting this parameter, as the buyer's locale is automatically set by PayPal
