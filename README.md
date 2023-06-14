## Checklist - e-commerce store:

1. Visuals: header, footer, content area, breadcrumbs, links, fonts, color (if designs are provided)
2. Functional: 
     - Category (sub category) page:
        - add product to the cart
        - paggination (if presented)
        - product Quick view overlay (if presented) - change product images, select color, set random quantity, add to cart
        - filters (if presented)
        - products listing sorting (if presented)
     - Product page:
        - all product images are visible (no broken ones) and can be selected (zoomed)
        - quantity can be choosen by plus and minus signs or by entering manualy a number in the field
        - add to cart button - on click, product is added to the cart (displayed in cart overview - if presented); the cart icon on top shows the nuber of the products
      - Cart page: 
        - change the quantity of the product. Changes are immediately applied or via button
        - remove of the product - chages are applied immediately
        - add a discount code - discount is displayed immediately under (or above) the total price
        - select delivery method (if presented)
      - Checkout
         - check form field validation - type of accepted symbols and error messages
         - select delivery method
         - click on order button leads to inforation page (with order details)
         - confirmation email is sent - check email layour and information 
         - user can place an order with or without a profile (if presented as an option)
      - Login:
          - check login form (visual and functional)
          - check if Password reset link is presented
      - Password reset:
          - on email enter and email is sent (if email is presented on website database)
          - email contains a password reset link; on click leads to page, where user can enter new passoword; on save user it taken to user profile
      - Create new profile:
          - form field validation - type of accepted symbols and error messages
          - check if after registration user is taken to the user profile section
          - check if confirmation message is received
          - check if user can add adress
          - check if user can add paymen method

During the testing the browser console is monitored for errors.
		
Testing is performed on latest versions of Chrome, Firefox, Microsoft Edge (on Windows), Safari (on Mac), Mobile and Tablet (Browserstack real devices or on physical devices - if available).

Go to [Issues](https://github.com/peter-angelov/ls/issues) to see the submited bugs and suggestions.
