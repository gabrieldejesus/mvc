## Installation
You can clone this repository OR download the .zip

When unzipping, it is necessary to run `composer` to install the dependencies and generate * autoload *.

Go to the project folder, through the **prompt / terminal** and execute:
> composer install

Then just wait.

## Configuration
All `configuration` and application files are inside the * src * folder.

The Database and URL settings are in the * src / Config.php * file

It is important to correctly configure the * BASE_DIR * constant:
> const BASE_DIR = '/**ProjectFolder**/public';

## Usage
You must access the project's *public* folder.

Ideally, create a specific ***alias*** on the server that points directly to the *public* folder.

## MODEL model
```php
<?php
namespace src\models;
use \core\Model;

class User extends Model {

}
```

## Release history

* 0.0.2
    * Finished project and studying the possibility of adding `new resources`
* 0.0.1
    * Work in `progress`

## Meta

Gabriel de Jesus – (https://www.gabrieldesenvolvedor.com/) – contato@gabrieldesenvolvedor.com

Distributed under the MIT License. See `LICENSE` for more information.

[https://github.com/devgabrieldejesus/mvc](https://github.com/devgabrieldejesus/)

## Contributing

1. Fork it (<https://github.com/devgabrieldejesus/mvc/fork>)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request
