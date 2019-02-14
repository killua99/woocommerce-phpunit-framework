# WooCommerce PHP Unit Framework

From the need of having a framework to work with Unit Test for project I decouple from the original woocommerce/woocommerce maininting the code untouched just modular.

## Intallation

`composer require killua99/woocommerce-phpunit-framework`

That should do.

## Usage

Just extend the class \WC_Unit_Test_Case to start working with the framework and using the creation helper `$this->product = WC_Helper_Product::create_simple_product();`
