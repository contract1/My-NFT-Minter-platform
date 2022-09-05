

A versão completa do código encontra-se na branch `main`

## Como iniciar o projeto

Dentro do diretório principal, você pode executar:

### `npm install`

Instala todas as dependências do projeto dentro da pasta "node_modules"


### `Criar um aquivo .env para as variáveis de ambiente`

Esse arquivo deve conter as seguintes inforações advindas do Piñata & Alchemy

```
REACT_APP_PINATA_KEY = "xxxxxxx"

REACT_APP_PINATA_SECRET = "xxxxxxxxxxxxxxx"

REACT_APP_BEARER_KEY = "xxxxxxxxxx"

REACT_APP_ALCHEMY_KEY = "xxxxxxxxxx"
```

#
### `truffle migrate`

Cria as ABI's do projeto dentro da pasta `src/abis`.\
It correctly bundles React in production mode and optimizes the build for the best performance.

Lembrando que para a aplicação rodar corretamente, é necessário ter uma Blockchain local rodando com Ganache

Tenha mais informações sobre o [Ganache](https://trufflesuite.com/ganache/).

#
### `npm start`

Inicia a aplicação no modo de desenvolvimento.\
Acesse [http://localhost:3000](http://localhost:3000) para visualizar a página no seu browser.

#

### `truffle console`

**Atenção: para acessar os métodos do nosso SmartContract e realizar testes no console do Truffle é necessário rodar um `truffle migrate`.**

Modo interativo para testar métodos do nosso contrato
