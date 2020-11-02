_English_

## 💻 Installation
You can clone this repository OR download the .zip

![](clone.png)

![](clone-zip.png)

When unzipping, it is necessary to run `composer` to install the dependencies and generate ***autoload***.

Go to the project folder, through the ***prompt / terminal*** and execute:
> composer install

Then just wait.

## 🛠 Configuration
All `configuration` and application files are inside the ***src*** folder.

The Database and URL settings are in the ***src / Config.php*** file

It is important to correctly configure the ***BASE_DIR*** constant:
> const BASE_DIR = '/**ProjectFolder**/public';

## 📈 Example usage
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

## 🗃 Release history

* 0.0.2
    * Finished project and studying the possibility of adding `new resources`
* 0.0.1
    * Work in `progress`

## 📝 Meta

Gabriel de Jesus – (https://www.gabrieldesenvolvedor.com/) – oi@gabrieldesenvolvedor.com

Distributed under the MIT License. See `LICENSE` for more information.

[https://github.com/devgabrieldejesus/mvc](https://github.com/devgabrieldejesus/)

## 🚀 Contributing

1. Fork it (<https://github.com/devgabrieldejesus/mvc/fork>)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request

---

_Português_

## 💻 Instalação
Você pode clonar este repositório OU baixar o .zip

![](clone.png)

![](clone-zip.png)

Ao descompactar, é necessário executar `composer` para instalar as dependências e gerar *** autoload ***.

Vá para a pasta do projeto, através do ***prompt / terminal*** e execute:
> composer install

Então espere.

## 🛠 Configuração

Todos os arquivos de `configuração` e aplicativos estão dentro da pasta *** src ***.

As configurações de banco de dados e URL estão no arquivo *** src / Config.php ***

É importante configurar corretamente a constante ***BASE_DIR***:

> const BASE_DIR = '/** ProjectFolder** / public';

## 📈 Exemplo de uso
Você deve acessar a pasta `public` do projeto.

O ideal é criar um ***alias*** específico no servidor que aponte diretamente para a pasta *pública*.

### MODELO de modelo
```php
<?php
namespace src\models;
use \core\Model;

class User extends Model {

}
```

## 🗃 Histórico de lançamento

* 0.0.2
     * Projeto finalizado e estudando a possibilidade de adicionar `novos recursos`
* 0.0.1
     * Trabalho em `progresso`

## 📝 Meta

Gabriel de Jesus – (https://www.gabrieldesenvolvedor.com/) – oi@gabrieldesenvolvedor.com

Distribuído sob a licença MIT. Veja `LICENSE` para mais informações.

[https://github.com/devgabrieldejesus/mvc](https://github.com/devgabrieldejesus/)

## 🚀 Contribuição

1. Fork it (<https://github.com/devgabrieldejesus/mvc/fork>)
2. Crie seu branch de recurso (`git checkout -b feature / fooBar`)
3. Faça commit de suas alterações (`git commit -am 'Add some fooBar'`)
4. Empurre para o branch (`git push origin feature / fooBar`)
5. Crie uma nova solicitação pull
