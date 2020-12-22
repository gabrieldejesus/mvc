# MVC

🧱 Structure MVC in PHP

<p align="left">
  <img alt="PRs welcome!" src="https://img.shields.io/static/v1?label=PRs&message=WELCOME&style=for-the-badge&color=4A90E2&labelColor=222222" />
     
   <img alt="Stars" src="https://img.shields.io/github/stars/gabrieldejesus/mvc?color=4A90E2&label=STARS&logo=3C424B&logoColor=3C424B&style=for-the-badge&labelColor=222222" />

   <img alt="Forks" src="https://img.shields.io/github/forks/gabrieldejesus/mvc?color=4A90E2&label=FORKS&logo=3C424B&logoColor=3C424B&style=for-the-badge&labelColor=222222" />

   <img alt="Issues" src="https://img.shields.io/github/issues/gabrieldejesus/mvc?color=4A90E2&label=ISSUES&logo=3C424B&logoColor=3C424B&style=for-the-badge&labelColor=222222" />

   <img alt="GitHub license" src="https://img.shields.io/github/license/gabrieldejesus/mvc?color=4A90E2&label=LICENSE&logo=3C424B&logoColor=3C424B&style=for-the-badge&labelColor=222222" />

  <a href="https://github.com/gabrieldejesus">
    <img alt="Follow gabrieldejesus" src="https://img.shields.io/static/v1?label=Follow&message=gabrieldejesus&style=for-the-badge&color=4A90E2&labelColor=222222" />
  </a>
</p>

## 📈 Example of use

With this structure it is possible to create sites and systems with an MVC structure (Model-View-Controller)

You must access the project's `public` folder.

Ideally, create a specific ***alias*** on the server that points directly to the *public* folder.

### MODEL model
```php
<?php
namespace src\models;
use \core\Model;

class User extends Model {

}
```

## 🛠 Getting started

Windows:

You can clone the repository through CMD (Command Prompt) just by typing:

```sh
git clone https://github.com/gabrieldejesus/mvc
```

or download the zip from the green button at the beginning of the repository

<img src="https://i.ibb.co/3mLnKMH/clone.png" alt="Download zip" border="0">

<img src="https://i.ibb.co/3M5CXKm/clone-zip.png" alt="Download zip" border="0">

## 💻 Configuration for development

When unzipping, it is necessary to run `composer` to install the dependencies and generate ***autoload***.

Go to the project folder, through the ***prompt / terminal*** and execute:
> composer install

Then just wait.

All `configuration` and application files are inside the ***src*** folder.

The Database and URL settings are in the ***src / Config.php*** file

It is important to correctly configure the ***BASE_DIR*** constant:
> const BASE_DIR = '/**ProjectFolder**/public';

## 🗃 Release history

- 0.1.0
  - Project finalized and studying the possibility of adding new resources
  - The first suitable lauch
- 0.0.1
  - Work in progress

## 📝 Meta

Gabriel de Jesus – [My portfolio](https://gabrieldesenvolvedor.com) – devgabrieldejesus@gmail.com

Distributed under the MIT License. See [LICENSE](LICENSE) for more information.

[https://github.com/gabrieldejesus/mvc](https://github.com/gabrieldejesus)

## 🚀 Contribution

1. Make the _fork_ of the project (<https://github.com/gabrieldejesus/mvc/fork>)
2. Create a _branch_ for your modification (`git checkout -b my-new-resource`)
3. Do _commit_ (`git commit -am 'Adding a new resource ...'`)
4. _Push_ (`git push origin my-new-feature`)
5. Create a new _Pull Request_

**After your pull request is merged**, you can safely delete your branch.

---
