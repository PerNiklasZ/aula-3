<template>
  <div class="container is-fluid">

    <b-navbar>
        <template #brand>
            <b-navbar-item tag="router-link" :to="{ path: '/' }">
                <img
                    src="data:image/png;base64,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"
                    alt="Lightweight UI components for Vue.js based on Bulma"
                >
            </b-navbar-item>
        </template>
        <template #start>
            <b-navbar-item tag="router-link" :to="{ path: '/' }">
                Home
            </b-navbar-item>
            <b-navbar-item tag="router-link" :to="{ path: '/produtos' }">
                Produtos
            </b-navbar-item>          
            <b-navbar-item tag="router-link" :to="{ path: '/produto1' }">
                Produto 1
            </b-navbar-item>                        
        </template>

        <template #end>
            <b-navbar-item tag="div">
                <div class="buttons">
                    <a class="button is-primary">
                        <strong>Cadastre-se</strong>
                    </a>
                    <a class="button is-light">
                        Login
                    </a>
                </div>
            </b-navbar-item>
        </template>
    </b-navbar>

    <Nuxt/>

    <footer class="footer">
      <div class="content has-text-centered">
        <p>
          <p>
            Grizzly Griptape Brasil - CNPJ:018.871.890/0001-72
          </p> 
          <p>
            Av. Professor Frederico Herman Jr, 296 - São Paulo/SP
          </p>
        </p>
      </div>
    </footer>      
    
  </div>
</template>

