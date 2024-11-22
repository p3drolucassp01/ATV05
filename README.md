# Documentação da aula 07- 

## Informações Gerais
- **Data de Execução**: 21/11/2024
- **Aluno**: Pedro Lucas
# Configuração do Projeto com Reactstrap

## Passos Realizados

### 1. Configuração do React para usar o Reactstrap

Primeiro, configurei o projeto React para usar o Reactstrap, executando os seguintes comandos no terminal para instalar as dependências necessárias:

```bash
npm install reactstrap react react-dom
npm install --save bootstrap
npm install react-popper @popperjs/core
```

### 2. Configuração do Bootstrap
Em seguida, configurei o Bootstrap, adicionando a seguinte linha no arquivo src/index.js para importar o CSS do Bootstrap:

import 'bootstrap/dist/css/bootstrap.min.css';

### 3. Criação da Barra de Navegação
Para adicionar a barra de navegação, segui os seguintes passos:

Abri o arquivo src/App.js.
Apaguei o conteúdo entre as tags <header> e </header>.
Adicionei o seguinte código no lugar do conteúdo apagado:

<Navbar dark color="primary">
  <div className="container">
    <NavbarBrand href="/">Ristorante Con Fusion</NavbarBrand>
    <div>Aluno: Fulano de Tal</div>
  </div>
</Navbar>


### 4. Alteração do Nome
Por fim, alterei o nome dentro da <div> de "Aluno: Fulano de Tal" para "Aluno: Pedro Lucas". O código ficou da seguinte forma:

<Navbar dark color="primary">
  <div className="container">
    <NavbarBrand href="/">Ristorante Con Fusion</NavbarBrand>
    <div>Aluno: Pedro Lucas</div>
  </div>
</Navbar>

abre o arquivo README e atualizei com um resumo dos passos que foram feitos na atividade de hoje.

insire uma imagem mostrando o navbar com o seu nome como a imagem a seguir:


![imagem](img_navbar.png)