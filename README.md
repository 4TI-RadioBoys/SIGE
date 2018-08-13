# SIGE

*Sistema Integrado de Gerenciamento de Eventos*

[![License](https://img.shields.io/badge/license-Apache2.0-blue.svg)](https://github.com/4TI-RadioBoys/SIGE/blob/master/LICENSE)

***
## Instalando

Depende de:
* [Composer](https://getcomposer.org/download/)
* [PHP 5](http://php.net/downloads.php) (ou superior)


### Rodando
Instale as dependências do composer utilizando e inicie o servidor virtual:
```sh
composer install
php -S 0.0.0.0:8080 -t public
```
### Outras plataformas
Caso esteja utilizando Nginx, Apache ou outro servidor HTTP, aponte o `public_html` para a pasta `public` do projeto.
 
Não é necessário mover as outras pastas da raiz do projeto já que estas não serão acessadas pelo usuário.