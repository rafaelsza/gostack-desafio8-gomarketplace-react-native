# GoMarketplace com React Native

Desafio n°8 do bootcamp GoStack, onde tivemos que desenvolver um front-end mobile utilizando React Native e TypeScript.

### Funcionalidades:

- Listar todos os produtos retornados de uma fake API.
- Incluir e remover produtos no carrinho.
- Alterar a quantidade a comprar na tela do carrinho.

### Utilizado:

- React Native
- react-native-vector-icons: para colocar ícones nos botões.
- Axios: para realizar a conexão com um back-end fake. (Um arquivo JSON com dados de produtos)
- Android Studio e dependências: para utilizar um emulador e rodar o app nele.

## Para utilizar em sua máquina:

**Necessário ter instalado o
[NodeJS](https://nodejs.org/en/download) e um ambiente de desenvolvimento mobile para utilização de emulador.**

> No projeto foi utilizado o
[yarn](https://yarnpkg.com/getting-started/install)
como gerenciador de pacotes, mas caso queira utilizar o npm basta substituír os comandos que começam com yarn por npm.

> No projeto foi utilizado o
[Android SDK](https://developer.android.com/studio)
para utilização de um emulador Android, mas você pode utilizar o que for de sua preferência, incluindo ambiente para desenvolvimento iOS.

Clone o projeto:
```
git clone https://github.com/rafaelsza/gostack-desafio8-gomarketplace-react-native.git
```

Entrar na pasta raíz:
```
cd gostack-desafio8-gomarketplace-react-native
```

Então executar yarn para instalar as dependências do projeto:
```
yarn
```

Inicie o back-end fake:
```
yarn json-server server.json -p 3333
```

Agora execute (com o emulador aberto):

Android:
```
yarn android
```

iOS:
```
yarn ios
```

Pronto! O app já estará rodando em seu emulador.
