=== HoneyBadger.IT ===
Contributors: @honeybadgerit
Tags: woocommerce order management, wc order statuses, wc emails, wc variable product images, wc suppliers, wc split orders, wc combine orders, wc invoices, wc custom pdfs, wc custom emails, suppliers, supplier orders, create orders
Donate link: https://honeybadger.it
Requires at least: 5.0
Tested up to: 6.4
Requires PHP: 5.4
Stable tag: 1.0.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

WC Order Management System including custom order statuses, emails, attachments, split orders, combine orders, variant image gallery, PDF Invoices, manage suppliers, manage sub products, create WC orders, create supplier orders, employee acounts with privileges and many other features are available on the HoneyBadgerIT platform, all you need to do is install the plugin and create an account.

== Description ==
HoneyBadger.IT is an online management system for your Woocommerce shop. This plugin is used for the communication between your site and the HoneyBadger IT platform. The communication between the parts use Oauth2 protocol for authorization and the Wordpress REST API v2 for data transfer. All communications are done over HTTPS, you would need a valid SSL certificate installed or you could use self signed certificate.

Demo Account: https://my.honeybadger.it User: demo@honeybadger.it Password: D3m0HoneyB:123

Free and Securely make your workflow easier without giving away your data. HoneyBadger.IT does not store your shop data, it acts only as a front end for your shop with multiple functionalities, what is stored is data that you add on the platform, in example supplier details, sub product details etc

With this plugin you can:

1. Create Custom Order Statuses, edit the current and newly created custom order statuses emails
2. Create Custom Emails to send to your customers
3. Create Custom PDF attachments to send to your customers, including PDF Invoices
4. Add image gallery to your product variations without using any third party image gallery software
5. Create sub products
6. Manage your orders
7. Create new orders
8. Split orders
9. Combine / Merge orders
10. Create Suppliers for your products and sub products
11. Associate / link products and sub products with your suppliers
12. Create Supplier orders
13. Have multiple accounts for your staff with different permissions for the system
14. Many other features

To connect your Woocommerce shop with the HoneyBadger.IT platform you need to install the plugin and set your account from the Status page, you will just need a valid email address.

HoneyBadger.IT aims to create the best environment for your online shop and company. We want to make your workflow easier and provide tools for your website and your business to be more productive. Using the HoneyBadger.IT platform will save you server resources, meaning the workload of the management part of your business is split between the platform and your server.

== Installation ==
1. Upload the HoneyBadger.IT plugin folder to the /wp-content/plugins/ directory
2. Activate the plugin through the Plugins menu in WordPress
3. Configure the plugin
4. Log in to the platform
5. Enjoy

== Frequently Asked Questions ==
= I d not have a valid SSL Certificate can I still use the plugin and platform? =
Yes, you would need to have at least a self signed SSL certificate and set curl_ssl_verify to no in settings.
= Does it work with Wordpress Multisite? =
Yes it does work with WP Multisite
= The WP REST API seams to do not work, what to do? =
Make sure that the API is public and not restricted by any other plugin which requires users to be logged in to be used.
= Does it work under Windows? =
We did not test it, it should work, let us know.
= I have uninstalled the plugin by accident and now I get an error message when I try to set it up, what to do? =
Login to the platform and go to the Account page as the main user, there you will find Oauth2 credentials that you need to add in the plugin tools page and continue with the setup process.
= What data is stored and where? =
Well, some data is saved to your server and some data is saved on the platform, be careful if you uninstall the plugin because everything stored on your server will be lost. Have a look at the features page on the honeybadger.it website to see each functionality and where data is stored

== Screenshots ==
1. Status page
2. Account creation
3. Platform dashboard

== Dependencies ==
1. Woocommerce
2. cURL, used to communicate with the platform
3. OpenSSL, if you are using a self signed SSL Certificate

== Changelog ==
= 1.0.0 =
First release, hopefully it is useful for the WP and WC community and many more releases will come.