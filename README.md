[**Forum for discussion**](https://onlineexamination.createaforum.com/index.php) <br/>
[**Video**]()
# Online_examination
collage project
## Technology use:test
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
   ```composer require laravel/installer ```
## Creating new project in laravel
* ``` laravel new projectname ``` 

## Edit title 
1. edit resources/views/welcome.blade.php [screenshot](screenshots/change_title.png)

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
file create after compilation :-  : - resources/js/app.js <br/>

## **Migration** command on laravel and create database
_migrate create database automatically_
1. create a file </br>
   ```database/database.sqlite``` 
2. edit .env file [screenshot](screenshots/set_env.png)
* DB_CONNECTION = sqlite
* remove other DB_... variables
3. ``` php artisan migrate ``` [screenshot](screenshots/migrate.png)

## Editing web site ( front end )
* edit ``` resources/view/layouts/app.blade.php ``` <br/>

[Feedback](https://forms.gle/12pF2caPSDd8ZLm56)



