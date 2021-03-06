﻿## Description

Here used [Admin LTE](https://almsaeedstudio.com/preview) Dashboard integrated with [Laravel](https://laravel.com/) Framework 5.2 and also included Laravel Authentication.

## Installation Guide

Step 1:
```
git clone https://github.com/NinjaRasel/AdminLteWithLaravel.git
```
Step 2:

- Go to project directory and create .env file like as:
```
APP_ENV=local
APP_DEBUG=true
APP_KEY=SomeRandomString
APP_URL=http://localhost

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=homestead
DB_USERNAME=homestead
DB_PASSWORD=secret

CACHE_DRIVER=file
SESSION_DRIVER=file
QUEUE_DRIVER=sync

REDIS_HOST=127.0.0.1
REDIS_PASSWORD=null
REDIS_PORT=6379

MAIL_DRIVER=smtp
MAIL_HOST=mailtrap.io
MAIL_PORT=2525
MAIL_USERNAME=null
MAIL_PASSWORD=null
MAIL_ENCRYPTION=null
```
- Give database credential into .env file. Here give an example: 
```
DB_DATABASE=adminlte
DB_USERNAME=root
DB_PASSWORD=root
```
Step 3:

- Go to project directory and open CMD (for Windows users) or terminal (for Linux users) and run the given command:
```
composer install
```
If composer isn't installed in PC then go to this [link](https://getcomposer.org/) to install composer.

Step 4:
```
php artisan key:generate
```
- If any error occurs like as:

> [ErrorException]                                                             
  file_put_contents(/var/www/html/test/AdminLteWithLaravel/bootstrap/cache/se  
  rvices.php): failed to open stream: No such file or directory

Then create a directory named **cache** to – AdminLteWithLaravel/bootstrap/ and again run that given command.
 
Step 5:
```
php artisan migrate
```
Step 6:
```
php artisan db:seed
```
Step 7:
```
php artisan serve
```
- Now run from browser – http://localhost:8000
- Login Credential : 
```
admin@test.com
123456
```


## Contact

**Md Rasel Ahmed**

*Software Engineer* - [AppBajar](https://appbajar.com)

*Contact No*: +880 1521 224958

*Email*: ninja.rasel@gmail.com

*Facebook*: [facebook.com/ninja.rasel](https://facebook.com/ninja.rasel)

*Web*: [rasel.ninja](http://rasel.ninja)


