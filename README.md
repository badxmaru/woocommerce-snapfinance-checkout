# WooCommerce Snapfinance Checkout

## Description

Snap Finance’s WooCommerce checkout plugin offers a quick and easy way to enable your WooCommerce powered eCommerce store to offer Lease to Buy finance options.  You can install it as you would any other plugin to your store and start enabling financing to your customers today.

You will need a Snap Finance Merchant Account to get selling with Snap Finance, please submit a request here: https://tinyurl.com/snapinquiry

## Installation

**Note** Always keep a backup of your existing WooCommerce installation including Mysql Database, before installing a new plugin.

### From WordPress Admin

1.  Download the zip from Github.
2.  Login to WordPress admin and go to Add New Plugin.
3.  Then click on Upload Plugin and select the downloaded zip and click Install Now.
4.  Find Snap Finance Checkout in your Plugin list and click Activate.
5.  Proceed to Plugin Configuration.

### Manual Installation

1.  Pull the code from the repository and upload it to a subdirectory in your `<wordpress-root>/wp-content/plugins`folder.
2.  Login to WordPress admin and find Snap Finance Checkout in your Plugins.
3.  Activate the plugin.
4.  Proceed to Plugin Configuration.

## Plugin Configuration

1.  Login to WordPress admin and open WooCommerce Settings.
2.  Click on payment tab and then on ‘Snap Finance’ plugin.

    1.  Enable/Disable – Tick to enable the module.
    2.  Title – Title you want to display at checkout page
    3.  Description – Enter appropriate description to display at checkout.
    4.  Environment: Select the environment for plugin whether it is sandbox or production. You need to enter Client ID and Secret Key according to selected  environment, found in your developer account at https://developer.snapfinance.com/
    5.  Client ID – Enter Client ID which you will receive from your developer account 
    6.  Client Secret Key – Enter Client Secret Key which you will receive from your developer account
    7.  Click save, customers will now see the Snap Finance button in your check out pages.

3.  Order Complete Api Callback

    1.  After processing orders, merchants must complete orders from the Woocommerce Orders page
    2.  This will get Application Status from Snap Finance.


## Changelog

### 1.0.0

-   Change in plugin description.

-   Change in endpoint API calls.

-   Access token encoded in url.

-   Change in javascript url.

-   Read only field for plugin title and description.

-   Updating cache of the plugin during the change of client id and seceret id. 

-   Change in Plugin description.

-   Updated validation message in parameters of plugin setting.

-   Updated code for better cache management of client id and client seceret key.
-   Updated product array price that was submitted in js.

### 1.0.1
-  Updated plugin structure according to WordPress marketplace standards
.
-  Resolved Internet explorer button rendering issue.

-  Other bug fixes.

### 1.0.2
-  Changes in JS inherited from Snap SDK.
-  Minor bug fixes.

### 1.0.3
-  Updated error handling condition which checks if woocommerce is installed or not.
-  Updated JavaScript code for better functionality.

### 1.0.4
-  Updated Steps for checkout.
-  Added validation to check token is generated before checkout or not.
-  Minor bug fixes on UI.

### 1.0.5
-  Removed Checkout button settings.

### 1.0.6
-  Changes in the logic for API calls made to snap server.
