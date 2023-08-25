# Aula 01
## Instalação Angular

### Instalar as depedencias de ambiente para o Angular

  * Node: https://nodejs.org/
  * Git: https://git-scm.com/downloads

### Verifique se as instalações estão corretas com os comandos:

`node -v`
`npm -v`
`git --version`

### Instale o Angular cli globalmente com o NPM

`npm install -g @angular/cli`

Verifique se o angular foi instalado com o comando `ng version`

### Crie um novo projeto Nestjs com o cli instalado

`ng new project-name` substitui project-name pelo nome do seu projeto. Lembrando que faremos uma SPA com angular

### Acessando e configurando

Acesse a pasta do projeto com `cd project-name` e rode o comando para iniciar o Angular em modo de desenvolvimento com o comando `npm run start`.

Você pode acessar e ver a aplicação rodando em http://localhost:4200

Vamos utilizar a biblioteca do Material Design para o Angular. Para adicionar essa lib ao projeto rode o comando `ng add @angular/material`. Após isso voce deve dar uma boa navegada nos componentes do **Angular Material** atraves [deste link](https://material.angular.io/components/categories). Navegue um pouco para conhecer os componentes de listagem, tabelas, botões, etc.

O Angular Material fará algumas modificações no projeto:
* Adição das depenências do projeto ao **package.json**
* Adição da fonte **Roboto** ao **index.html**
* Adição da lib de ícones do **Material Design** ao **idnex.html**
* Adição de alguns estilos CSS globais:
  * Remoção das margens do body
  * Ajuste da largura: 100% no html e no body
  * Ajuste da fonte Roboto como fonte padrão da aplicação
