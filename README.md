# Happy
<p align="center">O Happy é a aplicação desenvolvida na Next Level Week 3</p>

![happy](https://user-images.githubusercontent.com/24916872/96924760-80dd6480-1489-11eb-88d8-6d89fdcab757.png)

## Clonando o Repositório

```
# Clone o repositório
$ git clone https://github.com/felipescunha/nlw3.git
```

## Gerenciador de pacotes Yarn

Foi utilizado Yarn como gerenciador de pacotes caso você não o tenha instalado: [Install Yarn](https://classic.yarnpkg.com/en/docs/install)


## Instalando as dependências o repositório

```
$ cd backend && yarn && cd ..

$ cd web && yarn && cd ..

$ cd mobile && yarn
```

## Rodando as migrations

```
# Entrar na pasta backend e executar o comando abaixo
$ yarn typeorm migration:run
```

###  Importante!
- Para renderizar o mapa, crie uma conta no [mapbox](https://account.mapbox.com/auth/signup/?route-to=%22https://account.mapbox.com/%22) é gratuita e não precisa de cartão de crédito.
- Renomeie o arquivo .env.example para .env dentro da /web.
- Altere o valor do da varivel pelo token gerado no mapbox:
```
REACT_APP_MAPBOX_TOKEN=INSIRA_SUA_CHAVE_DO_MAPBOX_AQUI
```

## Rodando a aplicação

### Backend
```

$ yarn dev
```

### Web

```
$ yarn start
```

### Mobile (utilizado simulador IOS)

```
$ yarn start
```

## Tecnologias

- Node.js
- Express
- ReactJS
- React Native
- Expo
- TypeORM / SQLite
- Typescript
