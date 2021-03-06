# Magento 2 Redirect Customer to the particular page after Logging in successfully
This is an awesome module, It allows the Administration redirect the Customer to the particular page after Logging in successfully.

##Features of this extension:

###Frontend:
- Redirect Customer to the particular page after Logging in successfully
- Apply to multi websites

###Backend:
- Update the landing page and redirect Customer to this page after Logging in successfully

##Introduction installation:

###1 - Installation Magento 2 Redirect Customer
#### Manual Installation
Install Redirect Customer for Magento2
 * Download the extension
 * Unzip the file
 * Create a folder {Magento root}/app/code/PHPCuong/RedirectCustomer
 * Copy the content from the unzip folder


#####Using Composer

```
composer require phpcuong/magento2-redirect-customer

```

###2 - Enable Extension
 * php bin/magento module:enable PHPCuong_RedirectCustomer
 * php bin/magento setup:upgrade
 * php bin/magento setup:static-content:deploy

###3 - Settings
Log into your Magento Admin Panel, goto Stores -> Configuration -> Customers -> Customer Configuration

Expand the Login Options section. Then, do the following:

#### - To activate redirect Customer, set Redirect Customer to Account Dashboard after Logging in to “No.”
#### - Type URL valid into the field Redirect Customer to the particular page after Logging in successful

When complete, tap Save Config.

###4 - Clear all the cache
* php bin/magento cache:clean

###5 - Test and see results

##Video how to install and use this extension
https://www.youtube.com/watch?v=nQQjRVp5rS0

##ScreenShot

![ScreenShot](https://github.com/php-cuong/magento2-redirect-customer/blob/master/Screenshot/screenshot.png?raw=true)

