# Woocommerce Global Coupons Plugin

Generate availability-restricted WooCommerce coupons and let customers to see&use coupons on My Account.

General structure: Global Coupons - Coupon Operations - Preview - Reports - Settings

Current restrictions: First Order, Required Number of Orders, Required Amount of Orders, Special For You, Required Number of Reviews, Activate Date Interval, Years of Membership

Usage: 

- Download the current version from release folder and upload it to wp-content/plugins using FTP or using Admin Panel -> Plugins -> Add New -> Upload Plugin, then extract there. 

or

- Download: https://wordpress.org/plugins/global-coupons-for-woocommerce/ 

or

- Wordpress Admin Panel -> Plugins -> Add New -> Search -> "Global Coupons for Woocommerce" -> Install -> Activate


You may also check the old versions from: https://wordpress.org/plugins/global-coupons-for-woocommerce/advanced/

-----

Version 1.0.0:

- Security maintenance: Securing inputs and outputs, providing unique function names, checking permissions and using nonces.
- Plugin is reviewed by the WordPress Plugin Review Team and now published on Wordpress Plugins.

Version 1.0.1:

- Requirements: To install and activate the Global Coupons for Woocommerce, first you need to install and activate the WooCommerce plugin.
- README and Requirements are updated.

Version 1.1.0:

- List the global coupons and count the activate coupons for users.
- Show the orders which any global coupons are used in by listing with the relevant coupon code.

Version 1.1.1 and 1.1.2:

- Small bug fixes.
- README and Description is updated for more detail.

Version 1.1.3:

- Despite any used global coupon cannot be used again by same user, it shows Active. This bug is solved now.

Version 1.2.0:

- Admin Settings section is added to provide translation/customization of strings in user-side.
- Small bug fixes.
- Responsive problem of coupon table in my account is solved.
- Table background color and text color of table header can be changed from settings now.

Version 1.2.1:

- If no Global Coupons are defined, then show a notification in Global Coupons page (admin-side), Preview page (admin-side) and My Account - Coupons page (user-side).
- Small bug fixes.

Version 1.2.2:
- Setting field for translating the "No Global Coupons Found" string text.
- My Account tabs issue about translation is solved and settings fields are added for tab names.
- Currency symbol is added to relevant global coupon conditions.

Version 1.2.3:
- New Feature: "You Have" part for showing the current situation of users depending on the condition of the global coupon.
- Relevant setting fields for You Have part.
- New Status: "Used".
- New translation setting fields for active, deactive and used statuses of global coupons.
- No Coupons Found message showing bug is fixed.
- Available Date Interval feature activeness bug is fixed.

Version 1.3.0
- New Restriction: “Required Years of Membership” for global coupons.
- Relevant setting fields for Years Of Membership restriction.
- Additional CSS.

Version 1.3.1
- Update the Woocommerce version.
- Update the Wordpress version.
-----

To-Do: 
- Live Preview Link *
- New Restriction: Birthday **
- Responsive CSS corrections for Settings page. *
- Combine Restrictions ***
