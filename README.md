<div style="text-align: center;">
    <img style="width: 220px;" src="./assets/icon.svg" alt="Banana Store" />
</div>

# Banana Store

Olá! Este é o repositório da loja das Bananas (sim, somos bastante criativos).

A Banana Store é uma loja virtual muito simples que vende produtos de tecnologia superestimados e superprecificados para hipsters.

Para a nossa loja virtual funcionar, dependemos dos seguintes projetos aqui:

- [Back-end](./packages/backend/)
- [Front-end](./packages/frontend/)

## Back-end

Nosso back-end foi construído usando o [Strapi](https://strapi.io/).

## Front-end

Nosso front-end foi construído usando o [create-react-app](https://create-react-app.dev/).

## Estrutura de Dados

Nosso projeto constitui-se da seguinte estrutura de dados:

- **User**: Os usuários da aplicação;
- **Category**: As categorias dos produtos;
- **Product**: Os produtos da nossa loja;
- **ProductVariation**: A variação dos nossos produtos (podendo gerar um acréscimo no valor do produto);
- **Order**: Os pedidos da loja;
- **OrderItem**: Os produtos selecionados no pedido da loja. Os produtos do pedido indicam uma variação (se houver), a quantidade e o preço final.
