# Documentação da aula 09- 

## Informações Gerais
- **Data de Execução**: 25/11/2024
- **Aluno**: Pedro Lucas
# Configuração do Projeto com Reactstrap

## Passos Realizados

# Exercício - Componentes do React - Parte 1

Neste exercício, adicionei um novo componente chamado `Menu` ao aplicativo React. O componente `Menu` exibe uma lista de pratos, onde cada prato é representado por uma imagem, nome, descrição, categoria e preço.

### Estrutura do Componente Menu

1. **useState:** O hook `useState` é usado para armazenar os dados dos pratos no estado local.
2. **Estrutura do Componente:** O componente `Menu` é renderizado utilizando o método `map` para iterar sobre os pratos e renderizar o layout de cada um.
3. **Uso do Reactstrap:** Utilizamos o componente `Media` do Reactstrap para formatar a exibição dos pratos de forma organizada, exibindo imagens e texto.

### Como funciona

1. Os dados dos pratos são armazenados no estado `dishes`.
2. Usei `map` para gerar o layout de cada prato com a imagem, nome e descrição.
3. A estrutura final é renderizada dentro de um container com um layout de lista.

### Estilo

No momento, o arquivo `App.css` foi limpo, mas o layout e estilo dos elementos são gerenciados pelo Reactstrap.

### Passos realizados

- **Passo 1:** Preparação das imagens:
  - Baixei e descompactei o arquivo `images.zip` contendo as imagens dos pratos.
  - As imagens foram movidas para a pasta `public/assets/images`.

- **Passo 2:** Criação do componente `MenuComponent.js`:
  - Criei o componente `Menu` que recebe os dados dos pratos e os renderiza na tela.
  - Utilizei o hook `useState` para armazenar os dados dos pratos.
  - Utilizei o componente `Media` do Reactstrap para formatar a exibição.

- **Passo 3:** Atualização do arquivo `App.js`:
  - Importei o componente `Menu` para o arquivo `App.js`.
  - Adicionei o componente `Menu` dentro do JSX para exibição.

- **Passo 4:** Limpeza do arquivo `App.css`:
  - O arquivo `App.css` foi limpo, já que a formatação está sendo gerenciada pelo Reactstrap ou poderá ser personalizada posteriormente.

- **Passo 5:** Commit no Git:
  - Adicionei e comitamos as alterações com a mensagem "Components Part 1".

### Resumo

- Criei um novo componente `Menu` em React para exibir uma lista de pratos.
- Usei o hook `useState` para gerenciar os dados dos pratos.
- Utilizei o `Media` do Reactstrap para formatar a exibição dos pratos.
- Modifiquei o arquivo `App.js` para incluir o componente `Menu`.
- Limpei o arquivo `App.css`.
- Commitei as alterações no Git com a mensagem "Components Part 1".






