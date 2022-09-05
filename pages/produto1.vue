<template>
  <div>
    <div class="columns mt-4">
      <div class="column">
        <figure class="image">
                    <img src="https://cdn.shopify.com/s/files/1/0419/5758/9147/products/GMA2001P01-682_670x.png?v=1608035048">
        </figure>
      </div>
      <div class="column">
        <p class="title">
          CAMISETA GRIZZLY OG BEAR TEE - GMA2001P01
        </p>
        <p class="subtitle">
          Camiseta usada frequentemente por skatistas
        </p>
      </div>
      <div class="column">
        <p class="subtitle mt-3">
          R$ 119,91
        </p>
        <template>
          <section>
            <b-button @click="clickMe">Adicionar ao carrinho</b-button>
          </section>
        </template>

      </div>
    </div>
    <p>
      CAMISETA GRIZZLY OG BEAR TEE - GMA2001P01
100% ALGODÃO
    </p>
    <p class="mt-5">
      <b-field label="Adicione um comentário"
            :label-position="labelPosition">
            <b-input maxlength="200" type="textarea"></b-input>
        </b-field>
    </p>
    <section class="section">
      <p>
        Produtos relaciona
      </p>
      <div class="columns">
        <div class="column">
          <figure class="image">
            <img src="https://cdn.shopify.com/s/files/1/0419/5758/9147/products/GMB2035A07_BLACK_01_670x.jpg?v=1625518925">
        </figure>
        </div>
        <div class="column">
          <figure class="image">
            <img src="https://cdn.shopify.com/s/files/1/0419/5758/9147/products/GMC2101P27_BLACK_01_670x.jpg?v=1655513217">
        </figure>
        </div>
        <div class="column">
          <figure class="image">
            <img src="https://cdn.shopify.com/s/files/1/0419/5758/9147/products/GMC2101P03_BLACK_01_670x.jpg?v=1655515489">
        </figure>
        </div>
      </div>
    </section>
  </div>
</template>