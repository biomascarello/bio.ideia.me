# Site da Tânia

O site é dividido em:

* [app.coffee](app/coffee/app.coffee) arquivo principal da programação
* [tania.coffee](app/coffee/tania.coffee) dados da Tânia.
* [florest.coffee](app/coffee/florest.coffee) animação do rodapé da página
* [app/views](app/views/) ficam as templates de cada parte específica (contato e contrate-me)

# Instalando dependências

Este site foi iniciado a partir da ferramenta yeoman usando a template angular.
Para isso é necessário instalar as seguintes dependências:

* NPM - Node package management
* Bower
* Yeoman

Instalar o npm + bower + yeoman e o grunt.

    npm install bower yeoman grunt
    cd bio.ideia.me
    npm install
    bower install

# Para rodar localmente

    grunt serve

# Para fazer o deploy

    grunt deploy

Para fazer o deploy é necessário configurar o usuário e host corretamente.

Se você clonar e usar como exemplo não esqueça de alterar os dados do usuário e host no [Gruntfile.js](Gruntfile.js).

Desenvolvido por [@jonatas](http://github.com/jonatas). [ideia.me](http://ideia.me) eu [invent.to](http://invent.to).
