# Magento 2 Payment Fee Extension
Payment Fee extension for Magento 2 allows adding extra charges for specific payment methods and displays them on the cart page, checkout page, invoice, and credit memo. Also, payment fees display in the sales email like new order, invoice, and credit memo. Admin can also set the payment fee in order creation from admin.According to the payment method, there are several options for counting payment fees by percentage price, fixed price, per row, and per item. The payment fee title and description are configurable from the admin. Payment fees can be disabled after a specified maximum order amount. You can set the payment fee is refundable or not from the configurations settings. You can also set a default payment fee which acts as an extra fee on order. Payment fees may also be restricted only to specific stores or customer groups. 

## Features

1. Enable or disable extension from the admin configuration.
2. Admin can add payment fees on specific payment methods. 
3. Supports major of common payment methods like Cash on Delivery, PayPal, etc.
4. Can add payment fees in: Percentage Price, Fixed Price, Per Row, Per Item
5. Admin can set custom payment fee title and description for easy understanding
6. Displays payment fee on the checkout page, Order page, and Sales Email
7. Enable or disable refund of payment fees on credit memo from admin configuration. 
8. Admin can disable payment fees on the maximum order amount by adding the max order amount from the admin configuration.
9. Multi-store support
10. Support tax calculation on payment fee
11. Allow admin to select tax class for the payment fee
12. Customer group restrictions
13. Admin can set the sort order of payment fee
14. Admin can choose the payment fee display type(Excluding Tax, Including Tax,Including and Excluding Tax)

## How to install Magento 2 Payment Fee
### 1. Download and install from Magento Marketplace
<a href="https://marketplace.magento.com/ultraplugin-module-paymentfee.html">Magento Marketplace Link</a>

### 2. Install via composer (GitHub)
Run the following command in Magento 2 root folder:

```
composer require ultraplugin/module-paymentfee
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy
```

## Extension Screenshots

<img src="https://github.com/ultraplugin/module-screenshots/blob/master/payment-fee/1.jpg"/>
<img src="https://github.com/ultraplugin/module-screenshots/blob/master/payment-fee/2.jpg"/>
<img src="https://github.com/ultraplugin/module-screenshots/blob/master/payment-fee/3.jpg"/>
<img src="https://github.com/ultraplugin/module-screenshots/blob/master/payment-fee/4.jpg"/>
<img src="https://github.com/ultraplugin/module-screenshots/blob/master/payment-fee/5.jpg"/>
