# [SHOPZILLA V.2: Online Shopping App with Flutter - (Android & iOS) Documents](https://github.com/AmirBayat0/ShopZilla/blob/main/README_v2.md)
![main](https://user-images.githubusercontent.com/91388754/228836513-7a95a3cf-2890-4048-bee8-33b8f553ce1a.jpg)

<img src="https://user-images.githubusercontent.com/91388754/228848738-0326280f-4366-4bc1-8fe7-0a1910df9e0e.png" width ="900"/>
 



# Overview:
ShopZilla is a comprehensive application template for an online shopping platform, which utilizes the FakeStoreApi as the application's backend. The application comes equipped with a wide range of features to enhance user experience, such as a user authentication page for logging in or registering a new account, a homepage for browsing all available products, a detailed product page for viewing essential product information such as prices and descriptions, and a search page for easily locating favorite products.

Additionally, the application includes an bottom navigation bar for seamless navigation between screens, a cart page for storing items that the user wants to buy, a payment page for easy and secure transactions, a favorites page for keeping track of the user's preferred products, a settings page for changing app settings like themes, a user profile details page for viewing the current user's information, an available users page, an adjustment page, and light and dark modes to cater to various preferences.

Moreover, the application is highly customizable, enabling developers to make modifications easily and efficiently. As a result, ShopZilla is an ideal platform for those who are interested in developing their own online shopping application or learning Flutter by analyzing authentic application source code. Developed using Flutter, the application is readily accessible for all developers, making the application an excellent learning tool for new and experienced developers alike.

API documentation: [Fake Store API](https://fakestoreapi.com/docs)

###

<br>

## App Source Code:

[Source Code](https://www.buymeacoffee.com/AmirBayat/e/127012)

<br>

## App Demo Video:
[App Preview Video](https://youtu.be/1m9AgUef4QY)

<br>

### Getting Started:
To execute the project, it is necessary to run the commands listed below.

## Development Setup

run the following commands:

```
flutter pub get
flutter run
```

## App Main Sections:
```
- Splash
- Onboard(x4)
- Login & Registration Screens
- Home Screen
- Welcome message
- Cart Screen
- Product Details Screen
- Available Users screen
- Adjustment screen
- User profile screen
- Search Screen
- Favorite Screen
- Settings
- Drawer
- Payment Screen(x4)
- Light / Dark Mode
- Custom BottomSheet / SnackBars / Dialogs
- Bottom Navigation
- Empty List Screens
- Offline user screen
- Contact with us
- And More...
```
## App Features:

### Authentications pages

    - Login section (All forms has been implemented with validation functions)
        - an icon for changing the theme
        - form for username
        - form for password
        - a button for login
        - a button for login with the Facebook account(just UI)
        - a button for login with the Google account(just UI)
        - a button for login
        - a text for navigating to the registration page if the user has not any account and wants to register a new account

    - Register section (All forms has been implemented with validation functions)
        - an icon for changing the theme
        - a form for First name
        - a form for Last name 
        - a form for Email name 
        - a form for Username 
        - a form for Password 
        - a form for City 
        - a form for Street 
        - a form for Number  
        - a form for Zip code  
        - a form for Phone  
        - a button for register new account
        - a text for navigating to the Login page if the user has an account and wants to Login

### Home page

    - Welcome text&dialog to the user
    - Icon for opening the drawer
    - search box for navigating to the search screen
    - AutoScrollable Banner/ PageView for showing Top products
    - List of Categories(All, electronics, jewelry, men's clothing, women's clothing)
    - List of Hot Sales Products
    - List of trending Products
    - List of Recently Viewed Products
    - Offline user screen, for Home

### Details Product page

    - Product image
    - Icon for adding to favorite
    - Product name and descriptions and price
    - A form for adding pa coupon
    - A button for adding the product to cart

### Search page

    - A Form for searching your favorite product you want
    - List of suggestions for products based on the top search list
    - Empty Screen for the time the product does not exist according to your search
    - You can navigate to your favorite product details, add it to your cart or mark it as a favorite after finding it by searching

### Animated Drawer

    - username and email and profile picture
    - List of, some options that you can navigate to.
    - ShopZilla on Github / open project repo on Github
    - A button for logout user

### My Cart page

    - Empty list page for the empty cart
    - user profile and address
    - List of products selected by the user for purchase
    - delete the product from the list by scrolling (ltr)
    - an Icon for deleting all products
    - bottom sheet for seeing details (adding coupon code, subtotal, delivery fee, Discount, Total price)
    - a Button for navigating to the payment page

### Payment page (x4)

    - Add card section
        - a form for cardholder name
        - a form for the card number
        - a form for expiration code
        - a form for security code
        - a switch button for setting the current filled data as default
        
    - Payment section
        - choose the payment card/ method (MasterCard, Visa, Discover, Paypal)
        
    - Checkout section
        - Shipping address
        - Delivery Details
        - Payment cart
        - promo code
        - final details(final price, subtotal, delivery, total)
        
     - Payment approved
        - a button for filling data from beginning
        - order number
        - button for back to home page

### Favorite List page

    - Empty list page for the empty Favorite list
    - a button for sorting list, based on(All, Low Price, High Price, Alphabet, Rating,Electronic, Jewelry, men's clothing, women's clothing)
    - an Icon for deleting all favorite products
    - an Icon for changing the method of showing products(grid, list)
    - delete the product from the list by scrolling (ltr)
    - an Icon for deleting all products
    - bottom sheet for seeing details (adding coupon code, subtotal, delivery fee, Discount, Total price)
    - a Button for navigating to the payment page

### Setting page

    - an icon for contacting with developer
    - an icon for sharing the app with people
    - user profile, full name, and email, by tapping on it you will navigate to user profile details
    - a list tile for changing the app theme
    - a list tile for changing app language(just UI)
    - a list tile for navigating to the available users page
    - a list tile for navigating to the adjustment page
    - a list tile for logout users from current account

### user profile details page

    - empty page for the time user is not logged in
    - on the top, user profile picture(user can add his profile pic from local storage or take a shot with camera)
    - some forms for the available information of the user
        - Name
        - Email address
        - Username
        - Password
        - Phone
        - Complete address(city, street,number, zip code)

### Available users page

    - Available users list for logging as them
        - user profile
        - username
        - user email
        - user password
        - current status

### Adjustment page

    - a list tile and switch button for enabling and disabling the intro screen
    - a list tile and switch button for enabling and disabling the welcome dialog
    - a list tile for showing user token (Log in)
    - a list tile for showing the user id (Register)
    - a list tile for showing payment info
        - cardholder name
        - card number
        - expiration code
        - security code

### Light&Dark Theme

    - different loading widget, primary color, and images while the user change the app theme

## Technologies:
 - Flutter
 -  Dart
 -  GetX

<br>


## My Socials:

- [INSTAGRAM](https://www.instagram.com/codewithflexz)
- [YOUTUBE](https://www.youtube.com/c/ProgrammingWithFlexZ)
- [GITHUB](https://github.com/AmirBayat0)
- [CONTACT ME](https://amirbayat.dev@gmail.com)
- [FIND MORE](https://zaap.bio/CodeWithFlexz)
