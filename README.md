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
