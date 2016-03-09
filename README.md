![Sense Logo](sense-marca.png)

# Sense Web #


Projeto que roda no lado do cliente (Front-End), e utiliza AngularJs para implementar o design pattern MVC. Permite a visualização de indicadores e gráficos para gestão de negócios em tempo real. Se alimenta de JSON utilizando a especificação de sistemas RESTful. A versão em produção do projeto se encontra nas tags mais atuais do branch master utilizando integração contínua.

Clone o projeto do gitlab para sua máquina utilizando no terminal o comando (requer uma *ssh-key*):

    git clone git@gitlab.infoway-pi.com.br:sense/sense-web.git

É utilizado a metodologia de desenvolvimento **```Git Branching Model```** e **```Continuous Integration```**

## Funcionalidades #

* Gera uma bandeja de indicadores com suas respectivas janelas e situações.
* Permite filtrar, ordenar e agrupar indexáveis na bandeja.
* Gera  gráficos para cada indicador na bandeja.

## Getting Started #

Para começar a desenvolver para o projeto siga os seguintes procedimentos:

### Requerimentos
| Tecnologia | Versão | Utilidade |
|------------|------------|------------|
| [SenseWeb](www.com) | versão 3.0.0 | Controllers que farão a ligação com o banco de daos e o core |
| [Apache Tomcat](www.com) | >= versão 8.0.0 | Para criar um servidor local com o SenseWeb3 |
| [MySql](www.com) | >= version 3.0.0 | Gerenciar e manter o banco de dados local |
| [Java](www.com) | >= version 8.0.0 | Rodar o SenseWeb |
| [NodeJS](www.com) | >= version 5.6.0 | Gerenciar módulos importantes do projeto |
| [Npm](www.com) | >= version 0.10.52 | Gerir dependencias gerais do projeto |
| [Bower](www.com) | >= version 3.1.7 | Gerir bibliotecas front-end do projeto |

### Dependências

* AngularJS
 - Implementa o padrão MVC e SinglePage
 - Versão  4.9.0
* D3
  - Gera os gráficos da aplicação
  - Versão 3.0.0 ou acima
* Grunt
  - Automatiza tarefas
  - Versão 0.4.5 ou acima
* Karma
  - Roda os testes unitário com jasmine
  - Versão 0.4.0 ou acima
* Jasmine
  - Implementa teste e specs unitárias
  - Versão 0.4.0 ou acima
* Protractor  
  - Implementa teste e specs de interface (requer selenium webdriver)
  - Versão 0.4.0 ou acima

### Configuração do Ambiente

Com todos os requerimentos instalados você  precisa execturar os seguintes comando no terminal:

    npm install

e depois:

    bower install

### Build

Para buildar seu projeto você deve executar o seguinte comando no terminal.

    grunt build

Para previsualizar e rodar localmente seu projeto execute no terminal:   

    grunt serve

### Rodando os testes

A tabela abaixo mostra os tipos de testes no projeto, bibliotecas usadas e comando no terminal para executá-lo:

| Teste | Biblioteca | Comando |
|-------|------------|---------|
|Unitário| [Jasmine](www.com) |   **```grunt unit-test```** |
|Interface| [Protractor](www.com) | **```webdriver-manager start```** and other terminal **```grunt e2e-test```** |
|Performance| [PageSpeed](www.com) | **```grunt pagespeed```** |
|Estático| [JSHint](www.com) | **```grunt jshint```**|

Para rodar todos os testes de uma vez execute:

    grunt test

## Links

* [Documentação](http://www.sense.com)
* [Guidelines](http://www.sense.com)

## Contribuidores
Para contribuir, por favor, verifique nossas [guidelines](contributing.md).

* [@radames](http://github.com/radames-armageddon) **```radames@infoway-pi.com.br```**
* ~~[@jefferson](http://github.com/) **```jeff@infoway-pi.com.br```**~~
* ~~[@jackson](http://github.com/) **```jackson@infoway-pi.com.br```**~~
* ~~[@campanhã](http://github.com/) **```matheus@infoway-pi.com.br```**~~

------------
#### Licença [Generic](http://license.com)&copy;
