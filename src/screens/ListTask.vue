<template>
     <h3>List of Task</h3>


<div class="row">


  <div class="col-1 d-flex justify-content-center"> <input class="" type="checkbox"></div>
<!-- COL PER TESTO E CATEGORIA-->
  <div class="col-9">

      <p>TITOLO E CATEGORIA</p>

      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean lorem urna, hendrerit quis blandit
        porttitor,
       
        Morbi quis vestibulum ante. Fusce nec orc</p>

  </div>
  <div class="col-2 ">
    <button type="button" class="w-100 btn btn-secondary mb-2">MODIFICA</button>

    <button type="button" class="w-100 btn btn-danger">ELIMINA</button>
  </div>

</div>

</template>

<script>
// export che serve per importare il componente in app.vue
export default{
    name: 'ListTask',
}

</script>