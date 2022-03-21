# Requirements
- PHP 8.1
- MySql
- Postman

# API Currency Source
- https://openexchangerates.org

# Attached Files
### Attached file located in 'attachements' folder
- Postman API Collection


# Set up installation 

```
  - Clone this repository
  - Open terminal, go to project directory
  - Run composer install
  - Rename file .env.example to .env
  - Create new database
  - Set up database configuration in .env
  - Run command php artisan migrate
  - Run command php artisan key:generate
  - Run php artisan serve
  
```

# API Endpoints
### 1. End Point Register


This endpoint serves for user registration to access api, users are required to fill their name, email and password.

![api_register](https://i.ibb.co/WcDPX89/api-register.png)
### 2. End Point Login

This endpoint is used for user login, so user get token to be able to access api.

![api_login](https://i.ibb.co/BCVWDxb/api-login.png)
### 3. End Point Insert Currency

This endpoint serves to get a list of currencies from external api (https://openexchangerates.org), and save the data to the database.To access this endpoint, users are required to include their token.

![api_insert_currency](https://i.ibb.co/RYMrwRc/insert-currency.png)
### 4. End Point Update Currency Rate

This endpoint serves to update the exchange rate of each currency based on usd. To access this endpoint, users are required to include their token.

![api_update_rate](https://i.ibb.co/Hr5NNTS/update-currency.png)


### 5. End Point Get All Currencies

This endpoint is used to see a list of all available currencies. To access this endpoint, users are required to include their token.

![api_all_currencies](https://i.ibb.co/nrLWT9y/get-currency.png)


### 6. End Point Get Currency

This endpoint serves to get updated currency exchange rates based on currency codes. To access this endpoint, users are required to include their token.

![api_get_currency_by_code](https://i.ibb.co/FBn1v15/get-currency-by-code.png)
