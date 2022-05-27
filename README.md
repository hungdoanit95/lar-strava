<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>
* composer create-project --prefer-dist laravel/laravel:^(version) Laravel_Role_Permission
* Migration <Create table>:
  - Create:  
  php artisan make:migration create_name_table
  - Run:
  php artisan migrate
* Controller:
  php artisan make:Controller ControllerName
* Model:
   php artisan make:Model ModelName
* Seeder <Create Data for Table>:
  php artisan make:Seeder SeederName
* Factory <Pattern for Seeder>:
  php artisan make:Factory FactoryName

*** Summed: php artisan make:model NameModel --all

