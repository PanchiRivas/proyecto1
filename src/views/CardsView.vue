<template>
  <div class="mt-5"> <!-- margin top = 5-->
    <b-button variant="success">Texto</b-button>
    <b-button variant="info">Texto</b-button>
    <b-button variant="danger">Texto</b-button>
    <b-button variant="primary">Texto</b-button>
    <b-button variant="warning">Texto</b-button>
    <b-button variant="dark">Texto</b-button>

    <b-row class="mt-5">
      <!--cols= dispositivos peque;os md= medianos lg = grandes-->
      <b-col cols="12" md="4">
        
        <b-card title="Card Title"
        img-src="https://picsum.photos/600/300/?image=25"
        img-alt="Image"
        img-top
        class="mb-2"> <!-- margin button = 2-->
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla tortor lectus, imperdiet vel ipsum vitae, sagittis laoreet magna.</p>
        <b-button variant="info" :to="{name: 'home'}">Home</b-button>
        </b-card>

      </b-col>
      <b-col cols="12" md="4">
        
        <b-card title="Card Title"
        img-src="https://picsum.photos/600/300/?image=25"
        img-alt="Image"
        img-top
        class="mb-2"> <!-- margin button = 2-->
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla tortor lectus, imperdiet vel ipsum vitae, sagittis laoreet magna.</p>
        <b-button variant="info" :to="{name: 'about'}">About</b-button>
        </b-card>

      </b-col>
      <b-col cols="12" md="4">
        
        <b-card title="Card Title"
        img-src="https://picsum.photos/600/300/?image=25"
        img-alt="Image"
        img-top
        class="mb-2"> <!-- margin button = 2-->
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla tortor lectus, imperdiet vel ipsum vitae, sagittis laoreet magna.</p>
        <b-button variant="info" :to="{name: 'grid'}">Grid</b-button>
        </b-card>

      </b-col>
    </b-row>
    

  </div>
</template>

<script>
/* eslint-disable */
export default {
    name:'Cards'
}
</script>

