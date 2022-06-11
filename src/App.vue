<template>
  <div id="app">
    <b-navbar toggleable="lg" type="dark" variant="success">
      <b-container>
        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle> <!--boton responsive-->
        <b-navbar-brand href="#">Vue tutorial</b-navbar-brand>
        
        <b-collapse id="nav-collapse" is-nav> <!--cuando se active el boton responsive se activa esto-->

          <b-navbar-nav>
            <!--b-nav-itam incluye Router-->
            <b-nav-item :to="{name: 'home'}" exact>Home</b-nav-item> 
            <b-nav-item :to="{name: 'about'}">About</b-nav-item>
            <b-nav-item :to="{name: 'grid'}">Grid</b-nav-item>
            <b-nav-item :to="{name: 'cards'}">Cards</b-nav-item>
         </b-navbar-nav>

        </b-collapse>

      </b-container>
    </b-navbar>

      <b-container>
        <router-view/>

      </b-container>

    
    
  </div>
</template>

<style>
#app{
  text-align: center;
}
</style>
