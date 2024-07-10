# QuickPay Gateway Compatability with Hyvä Checkout

## Installation

1. Install [QuickPay_Gateway](https://github.com/QuickPay/magento-v2)
2. Install Compatability Module by running
```bash
composer require magebitcom/magento2-hyva-checkout-quickpay-gateway
```
3. Enable Module
```bash
bin/magento module:enable Magebit_CheckoutQuickPayPayment && bin/magento setup:upgrade
```

