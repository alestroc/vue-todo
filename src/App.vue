
<script>

export default {
  name: 'App',
  components: {

  }
}
</script>

<template>
  <h1 class="text-center">Todo Web</h1>
  <div class="row"> <!-- row che racchiude l'inserimento della task-->
    <h1 >Add a new Task</h1>
    <div class="row"> <!-- row dei 3 elementi-->

      <div class="col-lg-6"> <!-- col Title-->

        <input class="w-100" type="text" placeholder="Task title">
      </div>

      <div class="col-3"> <!-- col Category-->
        <select  class="form-select" name="category" id="category">

          <option value="business">Business</option>

          <option value="personal">Personal</option>

          <option value="hobby">Hobby</option>
        </select>
      </div>
      <div class="col-3"> <!-- col Date-->
        <input type="date" name="task-date" id="task-date">
      </div>
    </div>


    <div class="row">   <!-- row per TXT e button-->
      <textarea class="w-100" rows="2" placeholder="Add a  description"></textarea>
      <input class="btn btn-primary w-100" type="button" value="Add Task">
    </div>
    <h3>List of Task</h3>
  </div>

  <div class="row"> 

    <div class="col"><!-- COL DEL CHECKBOX--></div>

    <div class="col"><!-- COL PER TESTO E CATEGORIA-->

      <div class="row"><!-- row per titolo e categoria--></div>

      <div class="row"><!--ROW PER TESTO TASK--></div>

    </div>
    <div class="col"><!--COL PER TASTI MODIFICA E ELIMINA--></div>

  </div>

</template>








<!--
<template>
  <div class="container">
    
    <div class="row ">
      

      <div class="col-12 ">

        


         div per input e select 

        


      </div>
    </div>

    <br>

    visualizzazione task
    <h3>List of Task</h3>
    <div class="row">
      <div class="col-12 d-flex ">


          <div class="d-flex align-items-center" style="width: 20%; ">
            <input type="checkbox" >

          </div>


          <div class="">

            <h4 class="">Categoria </h4>
            <h3>titolo</h3>
            <p> 'DATA' - lLorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean lorem urna, hendrerit quis blandit
            porttitor, orem ipsum dolor sit amet, consectetur adipiscing elit. Aenean lorem urna, hendre orem ipsum dolor sit amet, consectetur adipiscing elit. Aenean lorem urna, hendre
            orc</p>
          </div>

        
      </div>
    </div>
    <div class="row">
      <div class="col-8">

        <input type="checkbox">
        <span>[Categoria] <br>Task 1</span>
        <p> 'DATA' - lLorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean lorem urna, hendrerit quis blandit
          porttitor,
          feugiat id nisl. Duis vitae mi sed nisl aliquam pellentesque. Nulla interdum, turpis vel fringilla eleifend,
          metus mauris rhoncus ipsum, sit
          amet venenatis magna lectus ut urna. Curabitur eget viverra magna. Suspendisse tincidunt turpis id lectus
          tempor, vel vestibulum magna iaculis.
          Morbi quis vestibulum ante. Fusce nec orc</p>

      </div>
    </div>
    <div class="row">
      <div class="col-8">
        <h3>List of Task</h3>
        <input type="checkbox">
        <span>[Categoria] <br>Task 1</span>
        <p> 'DATA' - lLorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean lorem urna, hendrerit quis blandit
          porttitor,
          feugiat id nisl. Duis vitae mi sed nisl aliquam pellentesque. Nulla interdum, turpis vel fringilla eleifend,
          metus mauris rhoncus ipsum, sit
          amet venenatis magna lectus ut urna. Curabitur eget viverra magna. Suspendisse tincidunt turpis id lectus
          tempor, vel vestibulum magna iaculis.
          Morbi quis vestibulum ante. Fusce nec orc</p>

      </div>
    </div>
  </div>
</template> -->


