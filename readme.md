<p align="center"><img src="https://laravel.com/assets/img/components/logo-laravel.svg"></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel attempts to take the pain out of development by easing common tasks used in the majority of web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, yet powerful, providing tools needed for large, robust applications.

## Learning Laravel

Laravel has the most extensive and thorough [documentation](https://laravel.com/docs) and video tutorial library of any modern web application framework, making it a breeze to get started learning the framework.

If you're not in the mood to read, [Laracasts](https://laracasts.com) contains over 1100 video tutorials on a range of topics including Laravel, modern PHP, unit testing, JavaScript, and more. Boost the skill level of yourself and your entire team by digging into our comprehensive video library.

## Laravel Sponsors

We would like to extend our thanks to the following sponsors for helping fund on-going Laravel development. If you are interested in becoming a sponsor, please visit the Laravel [Patreon page](https://patreon.com/taylorotwell):

- **[Vehikl](https://vehikl.com/)**
- **[Tighten Co.](https://tighten.co)**
- **[British Software Development](https://www.britishsoftware.co)**
- [Fragrantica](https://www.fragrantica.com)
- [SOFTonSOFA](https://softonsofa.com/)
- [User10](https://user10.com)
- [Soumettre.fr](https://soumettre.fr/)
- [CodeBrisk](https://codebrisk.com)
- [1Forge](https://1forge.com)
- [TECPRESSO](https://tecpresso.co.jp/)
- [Pulse Storm](http://www.pulsestorm.net/)
- [Runtime Converter](http://runtimeconverter.com/)
- [WebL'Agence](https://weblagence.com/)

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](https://laravel.com/docs/contributions).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).



App Builder is a software for Creating Automated systems , you can create your own system without Writing line of code .. you have only to use the wizard step by step to build your system Modules and start using it , you can Build System Like [Library Management , School Management , HR , ERP ] System etc ..

AppBuilder Documentation

.0
AppBuilder v 2.2
App Builder
created: 24/07/2017
latest update: 13/08/2019
by: Ramy Ramadan
email: ramy_islam88@yahoo.com

What is This ?

App Builder is software for Creating Automated systems , you can create your own system without Writing line of code .. you have only to use the wizard  step by step to build your system Modules and start using it , you can Build System Like [Library Management , School Management , HR , ERP ] System etc ..

How Does it works ?

1-CRUD Builder :

Example To Create New System Module like "Library" : 

1- Go to CRUD Builder ⇒  Modules ⇒  Add New Module .
2-Write Module Name Like [ "Library" ] and Choose [Icon] for it to Be shown in left menu 
3-In Module Click on Configure beside module name To Add Fields to Your module . 
4-Add fields one by one for example i will add the following : 
a- Click on Add New field : 
-Book_First_Name as Database Field Name . 
-Book First Name as Label in form . 
-Choose the Type [string -integer -text ...etc ].
-Click on submit 
5-After Adding all fields required Click on Generate Module and wait seconds ..
6-you will find module Menu Item in left menu where you can go there and [ add/edit /delete ] your data .



2-Manage Users .
-	Add New User :
    - Click on Users => Add new user.
-	Edit User .
-	Click on edit beside every User .
3-Manage Permissions.
-	Add New Permissions :
    - Click on Users => Add new Permissions.
-	Edit User .
-	Click on edit beside every Permissions .
3-Manage Roles.
-	Add New Roles :
    - Click on Users => Add new Role.
-	Edit User .
-	Click on edit beside every Role .
4-User Profile :
-	You can Update your info of logged in user through this .

Features

1.	Login.
2.	User registration.
3.	ajax [add-edit-delete] users .
a.	[Add -edit ] role of user.
4.	ajax [add-edit-delete] roles.
a.	[Add -edit-remove] assigned permission to Role.
5.	ajax [add-edit-delete] permissions .
6.	ajax [add-edit-delete] files and folders .
a.	[create-edit-delete] Folders and subfolders .
b.	[add-edit-resize-crop] images .
c.	Adding as many files as user want .
7.	ajax [add-edit-delete] Module .
8.	ajax sorting by  any field .
9.	ajax search in all fields .
10.	ajax Paging .
11.	Export Data to CSV file ,copy data to clipboard ,print data .
12.	Edit User Data in Account settings . 
      
Main Advantages :
1.	Build In Laravel Framework v 5.7.
2.	Angular JS .
3.	Gentelella Admin Template .
4.	Bootstrap.
5.	Font Awesome.
6.	More .
Changelog :
1.	fix some issues in registration ,  users module.
2.	add API Support using laravel-passport .
3.	Social login .
4.	RTL support .
5.	Laravel version update .
6.	Reconfigure Modules .
Source & Credits :
Thanks so much To
Jquery.
Anugular 
Laravel 
Zizaco/Entrust
Laravel File Manager 
Gentelella Admin

App Builder Installation

1- First download zip file and Upload file to your server .
2-Extract file content to server .
3-Move all files in  AppBuilder Directory to your root server folder
example : public_html folder . [including .htaccess , .env ] it is better to do this by filezilla because some hosts don’t show this files by default .
4-Go to your Host and Create new database , you will need  the following in installation   Database Host : is IP of your host or it is local server , it is something like [ 127.0.0.1 ]
Database name : is Name of created database .
Database user name : Is the Database assigned User name who has full privileges on it Database password   : is the Password of Database User name on this database .
5- Go to your website URL EXAMPLE : www.website.com/install 
6-Put your database settings and The New User Account which you will Use .
7-Go to your www.yourwebsite.com/login to use the application .
That’s it 

