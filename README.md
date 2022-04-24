
# Delivery App

Aplicativo fullstack de delivery de bebidas alcoolicas com API construída no padrão REST.


## Funcionalidades
A role do seu login determina qual "fluxo" o aplicativo deverá seguir.

**Você tambem pode ver o aplicativo funcionando clicando [aqui.](https://bebidas-express-hk.netlify.app/login)**

### Usuário comprador
- O comprador precisa estar registrado no banco de dados para acessar o app - o cadastro pode ser feito com um botão na tela de login.
- No aplicativo, o usuário pode adicionar qualquer quantidade de qualquer bebida no carrinho e em seguida finalizar o pedido com seu endereço.
- Você pode ver detalhes de todos os seus pedidos como o total, status dos pedidos e detalhes dos produtos.
![Demo comprador](assets/readme/customer_demo.gif)
### Usuário vendedor
- Os produtos disponíveis estão salvos em um banco de dados atrelado a cada um dos vendedores.
- O vendedor pode ver uma listagem dos pedidos e manipular o status de cada um deles.
![Demo comprador](assets/readme/seller_demo.gif)

### Usuário administrador
- O administrador é capaz de excluir usuários existentes e cadastrar novos usuários.
![Demo comprador](assets/readme/eer.png)

### Relações do banco de dados
![Relacões](assets/readme/customer_demo.gif)


## Tecnologias
#### Frontend
- [react](https://github.com/facebook/react/)
- [redux-toolkit](https://github.com/reduxjs/redux-toolkit)

#### Backend
- [nodejs](https://nodejs.org/en/)
- [sequelize](https://github.com/sequelize/sequelize)
- [express](https://github.com/expressjs/express)
- [my-sql](https://www.mysql.com)
- [mongodb](https://github.com/mongodb/mongo)
- [mongoose](https://github.com/Automattic/mongoose)
- [jwt](https://github.com/auth0/node-jsonwebtoken)


## Apêndice

O deploy foi desenvolvido em duas versões:
 - mongodb + mongoose na branch `principal`
 - mysql + sequelize na branch `mysql-sequelize`



## Autores

- Marcos - [@marcosebsilva](https://github.com/marcosebsilva)
- Mari - [@mariananogueirab ](https://github.com/mariananogueirab)
- Mayu - [@mayusatori](https://github.com/mayusatori)
- Romano - [@rafaelromanoz](https://github.com/rafaelromanoz)
