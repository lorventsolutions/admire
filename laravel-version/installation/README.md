# Installation

## Laravel 8.x Installation

The zip file contains all laravel files integrated with Admire, however you need to perform following steps to get vendors etc.

### Minimum Requirements

For laravel 8.x , the minimum version of php required is `7.3` and

the following php extensions are required

* PHP &gt;= 7.3
* OpenSSL PHP Extension
* PDO PHP Extension
* Mbstring PHP Extension
* Tokenizer PHP Extension
* XML PHP Extension
* Ctype PHP Extension
* JSON PHP Extension

### Get Composer packages

`composer install`

### permissions

```text
chmod -R 775 storage

chmod 775 bootstrap/cache
```

If you are on linux/ mac you can run below command to chown it.

```text
chown -R www-data /var/www
```

### compile assets

> If you don't have good knowledge on nodejs and npm, you can skip this step however this step is recommonded if you want to modify the template as per your needs.

Make sure you have [nodejs](https://nodejs.org) installed in your system with minimum version `8.9.0`,

you can check installed version by running `node -v` command in terminal.

If you are having older version, please install latest version from [nodejs.org](http://nodejs.org/)

 **Install Required global packages** 

`npm install -g npm bower`

 **Install local packages** 

`npminstall`

 **Get bower components** 

`bower install`

 **Note:** If bower gives warning that you are running as administrator, please run the command `bower install --allow-root`

 **move assets to desired locations** 

`npm run dev`

## Congratulations

open your website and it should be fully working now :\)

