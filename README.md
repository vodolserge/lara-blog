## Laravel 7 - A simple blog

- Admin panel: CKEDITOR, CKFINDER 
- Users registration and authorization
- MySQL database

## Installation

Use the package manager [composer](https://getcomposer.org/) to install all PHP dependencies. Run it from root folder.

```bash
composer install
```

Use the package manager [npm](https://www.npmjs.com/) to install
all NPM dependencies. Run it from root folder.

```bash
npm install
```

## Usage

> #### /login
> You can register users. But now there are 2 users available: just for testing purposes.
> There are:
> 1. admin@admin.net: password - 12345
> 1. user@user.net: password - 12345

> #### /admin
> Admin panel - only if User Role is Admin.
If not, you should go to /login route.

## DB

MySQL server. Port: 3306

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
