# ReactJS challenge: concepts
Desafio bootcamp GoStack - Conceitos de React

Neste repositório encontra-se a parte de desenvolvimento front-end da API, relacionada ao mesmo projeto da aplicação back-end
escrito em NodeJS do repositório nodejs-challenge-concepts. Para testar este código, primeiramente é necessário ter o servidor NodeJS
do código citado anteriormente online.

Ao clonar o repositório para a máquina local, acesse a pasta do projeto pelo terminal e digite `yarn` para instalar os pacotes e
respectivas dependências. 


## A aplicação

Esta simples aplicação adiciona repositórios à página em tempo real, sem a necessidade de atualizar a página, aplicando os conceitos 
do ReactJS de estado, imutabilidade e SPA (Single Page Application).

- Ao pressionar o botão "Adicionar", é gerado um repositório
- Cada repositório gerado (a partir de uma string concatenada com a data gerada pelo método `Date.now()`) é armazenado em um array de 
objetos (JSON) dentro da API
- Todo repositório gerado possui com ele um botão de "Remover", para excluir tanto da interface quanto da API o objeto do array.

## Testando a aplicação

- Para testar, execute o servidor node do outro repositório, conforme citado anteriormente, através do `yarn dev` ou gerenciador de pacotes
de sua preferência
- Com o servidor online, na pasta do projeto front-end execute o comando no terminal `yarn start` (start= 'react-scripts start')
- Execute no terminal `yarn test` para rodar os testes automatizados
