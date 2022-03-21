# Requirements
- PHP 8.1
- MySql
- Postman

# API Currency Source
- https://openexchangerates.org/api/currencies.json?app_id=68d594634873459082f9bd1229c32088

# Attached Files
### Attached file located in 'attachements' folder
- Postman API Collection


# Set up installation 

```
  - Clone this repository
  - Open terminal, go to project directory
  - Run composer install
  - Rename file .env.example to .env
  - Set up database configuration in .env
  - Run command php artisan key:generate
  - Run php artisan serve
  
```

# API Endpoints
### 1. End Point Register
![api_register](https://i.ibb.co/WcDPX89/api-register.png)
### 2. End Point Login
![api_login](https://i.ibb.co/BCVWDxb/api-login.png)
### 3. End Point Insert Currency
![api_insert_currency](https://i.ibb.co/RYMrwRc/insert-currency.png)
### 4. End Point Update Rate
![api_update_rate](https://i.ibb.co/Hr5NNTS/update-currency.png)
### 5. End Point All Currencies
![api_all_currencies](https://i.ibb.co/nrLWT9y/get-currency.png)
### 6. End Point Get Currency
![api_get_currency_by_code](https://i.ibb.co/FBn1v15/get-currency-by-code.png)
