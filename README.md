# CheckoutCitiesDropdown-Magento2

# Overview

On the Checkout page, City Dropdown will appear so that the customer can easily and effortlessly select a city from the given list of available cities based on the selected country of his/her choice. Hence, there will be no need to enter the City Name in the text field. It will automatically display all the cities of the selected country. City Dropdown appears abruptly on country selection without any page loading or lag, creating an even more seamless experience for the customer. This dropdown will also be available on the customer shipping address and billing address in the customer address book section.
The City Dropdown extension is guaranteed to improve effective engagement with the customers. It makes it dynamic and more appealing along with providing a great user-friendly encounter that ultimately, enhances the final customer experience.


Here are some of the salient features for the extension:

```
1. AJAX-based technique to let the customers select any city from the available list of cities on the checkout page
2. Automatically updates the city dropdown on country selection without having to reload the page
3. Also available on customer address book section
4. AJAX call to cart, summary, and mini-cart to automatically update the price
5. Updates the city dropdown on country selection in real-time
6. A user-friendly and seamless way to select the city of choice

```

## Installation

### Magento® Marketplace

This extension will also be available on the Magento® Marketplace when approved.

### Manually

1. Go to Magento® 2 root folder

2. Require/Download this extension:

   Enter following commands to install extension.

   ```
   composer require rltsquare/checkout-cities-dropdown
   ```

   Wait while composer is updated.
   
   #### OR
   
   You can also download code from this repo under Magento® 2 following directory:
    
    ```
    app/code/RLTSquare/CitiesGrid
    ```    

3. Enter following commands to enable the module:

   ```
   php bin/magento module:enable RLTSquare_CitiesGrid
   php bin/magento setup:upgrade
   php bin/magento cache:clean
   php bin/magento cache:flush
   ```

4. If Magento® is running in production mode, deploy static content: 

   ```
   php bin/magento setup:static-content:deploy
   ```


## Requirements

1. This Magento® extension works on Magento 2.2 and 2.3 versions. Tested on versions 2.2.5 and above.

2. Tested on different themes specifically Ultimo, Porto and certain custom themes

For details, read our blog:
https://www.rltsquare.com/blog/checkout-city-dropdown-magento-2-extension/
