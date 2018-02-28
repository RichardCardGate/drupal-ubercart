![CardGate](https://cdn.curopayments.net/thumb/200/logos/cardgate.png)

# CardGate module for Drupal 7 Ubercart

[![Total Downloads](https://img.shields.io/packagist/dt/cardgate/drupal-ubercart.svg)](https://packagist.org/packages/cardgate/drupal-ubercart)
[![Latest Version](https://img.shields.io/packagist/v/cardgate/drupal-ubercart.svg)](https://github.com/cardgate/drupal-ubercart/releases)
[![Build Status](https://travis-ci.org/cardgate/drupal-ubercart.svg?branch=master)](https://travis-ci.org/cardgate/drupal-ubercart)

## Support

This plugin supports Ubercart version **3.x** for Drupal 7.

## Preparation

The usage of this module requires that you have obtained CardGate security credentials.
Please visit [My Cardgate](https://my.cardgate.com/) and retrieve your Site ID and hash key, or contact your accountmanager.

## Installation

1. Download and unzip the uc_cardgate.zip file on your desktop.

2. Upload the **contents** of the zip file to your **Drupal modules** folder, which you can find here: **http://mywebshop.com/htdocs/sites/all/modules/**
(Replace **http://mywebshop.com** with the URL of your webshop, so the **uc_cardgate** folder will end up in the **modules folder**)


## Configuration

1. Go to the **Admin, Modules** section of your webshop
   
2. Scroll to the **Ubercart – Payment** section.

3. Checkmark the **Cardgate Payment Gateways module**.
   Scroll down and click **Save configuration**.
   
4. Go to the **admin** section of your webshop and select **Admin, Store, Payment methods**.

5. Click on the **CardGate settings** link.

6. Now enter the **Site ID**, and the **Hash Key** which you can find at **Sites** on [My Cardgate](https://my.cardgate.com/) 

7. Enter the **default language** used by your webshop, and click **Save configuration**.

8. At **Payment methods** checkmark all the payment methods that you wish to activate.
   Attention: Do **not** checkmark the **CardGate** payment method, this is only used for the settings.
   
9. Click **Save configuration**.
   
10. Go to [My Cardgate](https://my.cardgate.com/), choose **Sites** and select the appropriate site.

11. Go to **Connection to the website** and enter the **Callback URL**, for example:
    **http://mywebshop.com/?q=cart/cgp_response**
(Replace **http://mywebshop.com** with the URL of your webshop)

12. When you are **finished testing** make sure that you switch from **Test Mode** to **Live mode** at the **CardGate settings** and save it (**Save**).
    
## Requirements

No further requirements.