# Online_examination
collage project
## Technology use:
* laravel framework ( php framework )
* composer ( php package manager )
* node.js

## Install requirements.

* composer
[download](https://getcomposer.org/download/)
* node.js
[download](https://nodejs.org/en/download/)
* laravel  <br/>
   CMD <br/>
   ```composer require laravel/install ```
## Creating new project in laravel
* ``` laravel new projectname ``` 

## Run project
* ```php artisan serve ``` must be inside project directory

## Create login feature on site
* ```composer require laravel/ui ``` 
* ```php artisan ui vui --auth ```  <br/>
close and rerun <br/>
```php artisan serve ``` 

## npm javasript package manager
* ``` npm install ```
* ``` npm run development ``` It compile laravel files <br/>
compiled file : - public/js/app.js <br/>
file create after compilation :-  : - reqources/js/app.js <br/>

## **Migration** command on laravel
_create database automatically_
1. create a file </br>
   ```database/database.sqlite``` 
2. edit .env file
* DB_CONNECTION = sqlite
* remove other DB_... variables
3. ``` php artisan migrate ```

## Editing web site ( front end )
* edit ``` resources/view/layouts/app.blade.php ```




