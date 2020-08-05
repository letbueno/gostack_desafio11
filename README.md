![68747470733a2f2f73746f726167652e676f6f676c65617069732e636f6d2f676f6c64656e2d77696e642f626f6f7463616d702d676f737461636b2f6865616465722d6465736166696f732e706e67](https://user-images.githubusercontent.com/50913322/87230209-c2d41600-c384-11ea-9339-71a8deacfccc.png)


<h1 align="center">:rocket: Desafio 11 do Nível 06 do Bootcamp GoStack 11.0 - GoRestaurant Mobile :rocket:</h1>

A proposta deste desafio era testar os conhecimentos do módulo Fundamentos do React Native. Onde consistia em implementar front-end da aplicação fake API disponibilizada dentro do template, para realizar pedidos de pratos de comida na aplicação GoRestaurant.

### Funcionalidades Implementadas :bookmark_tabs:
- Listar os pratos de comida API fake. :heavy_check_mark:
- Listar a categoria dos pratos de comida da API fake. :heavy_check_mark:
- Filtrar pratos de comida pela busca ou seleção de categoria. :heavy_check_mark:
- Listar pedidos da API Fake. :heavy_check_mark:
- Realizar um pedido. :heavy_check_mark:


### Como Rodar a Aplicação :desktop_computer:
Eu utilizei o [Android Studio](https://developer.android.com/studio) para emular um dispositivo Android para este projeto. 

- No terminal, clone o projeto:

```
https://github.com/letbueno/gostack_desafio11/
```

- Instale as dependências:
```
yarn
```
- Para executar a Fake API:
```
yarn json-server server.json -p 3333
```
- Para executar a aplicação:
```
yarn start
```

```
yarn android
```

### Rotas da Aplicação :mag_right:

**`/foods`** : Retorna todos os pratos de comida cadastrados na API.

**`/foods/:id`** : Retorna um prato de comida específico baseado no **`id`** passado como parâmetro para a rota.

**`/categories`** : Retorna as categorias cadastradas na API.

**`/orders`** : Retorna todos os pedidos realizados cadastrados na API.

**`/favorites`** : Retorna todos os pratos de comida favoritos cadastrados na API.



### Passo a Passo com imagens	:technologist:
#### Página inicial do GoRestaurant
![telainicialGoRestaurant](https://user-images.githubusercontent.com/50913322/89428515-d9b32180-d712-11ea-9bd3-7f21a6f0ff9c.jpg)


#### Página Cardápio
![telaprincipalGoRestaurant](https://user-images.githubusercontent.com/50913322/89428734-1aab3600-d713-11ea-88c7-eecd5d9366bc.jpg)


#### Página Detalhes do Prato de Comida
![telacomidaGoRestaurant](https://user-images.githubusercontent.com/50913322/89429418-e5531800-d713-11ea-8800-8637544e68ad.jpg)


#### Página Meus Favoritos
![telafavoritaGoRestaurant](https://user-images.githubusercontent.com/50913322/89429001-6067fe80-d713-11ea-93ca-3c7a96e8e12b.jpg)



### Como Rodar os Testes? :desktop_computer:
Os testes foram desenvolvidos pela Rocketseat, para testar se as funcionalidades seguem os parâmetros indicados:
- Listar todos os pratos de comida. :heavy_check_mark:
- Filtrar os pratos de comida por categoria. :heavy_check_mark:
- Filtrar os pratos de comida pelo nome no campo de busca. :heavy_check_mark:
- Permitir navegar para a página de detalhes sobre o prato de comida. :heavy_check_mark:
- Permitir listar todos os pratos de comida que estão marcados como "favorito". :heavy_check_mark:
- Permitir listar todos os pedidos realizados. :heavy_check_mark:
- Permitir listar todos os dados específicos sobre um prato de comida. :heavy_check_mark:
- Permitir acrescentar ou retirar quantidades de prato de comida ao pedido. :heavy_check_mark:
- Impedir que a quantidade de pratos de comida pedidos seja menor que 1. :heavy_check_mark:
- Permitir acrescentar ou retirar quantidades itens extras ao um prato de comida. :heavy_check_mark:

Para rodar o teste:
```
yarn test
```
### Dependências e Tecnologias :books: 

- [React Native](https://reactnative.dev)
- [Javascript](https://devdocs.io/javascript/)
- [Typescript](https://www.typescriptlang.org/docs/home.html)
- [Styled Components](https://styled-components.com/docs)
- [Axios](https://github.com/axios/axios)

### Participante: 
|Name|E-mail|Course|
| -------- | -------- | -------- |
|Leticia Bueno Martins|leticia.bueno.martins@gmail.com|Bootcamp GoStack 11.0|

---

Feito com :heart: by Leticia

