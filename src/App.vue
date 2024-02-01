
<script>

export default {
  name: 'App',
  components: {

  }
}
</script>

<template>
  <h1 class="text-center">Todo Web</h1>
> <!-- row che racchiude l'inserimento della task-->
    
    <div class="row offset-lg-2"> <!-- row dei 3 elementi-->
      <h1 >Add a new Task</h1>


      <form class="d-flex">
      <div class="col-lg-5 "> <!-- col Title-->
       
        <input class="w-100 form-control" type="text" placeholder="Task title" aria-label="Text input with dropdown button">
      </div>



      <div class="col-3"> <!-- col Category-->
        <select  class="form-control" name="category" id="category">

          <option value="business">Business</option>

          <option value="personal">Personal</option>

          <option value="hobby">Hobby</option>
        </select>
      </div>
      <div class="col-2"> <!-- col Date-->
        <input  class="w-100 form-control" type="date" name="task-date" id="task-date">
      </div>
      </form>
    </div>
  

    <div class="row offset-lg-2">   <!-- row per TXT e button-->
      <div class="col-10">
        <textarea class="w-100 form-control" rows="2" placeholder="Add a  description"></textarea>
      <input class="btn btn-primary w-100" type="button" value="Add Task">
      <hr>
      </div>
      
      
    </div>


    

  <div class="row  offset-lg-2 "> 
   
    <h3>List of Task</h3>

    <div class="col-1 d-flex justify-content-center"> <input class="" type="checkbox" ></div>

    <div class="col-8"><!-- COL PER TESTO E CATEGORIA-->

      <div class="row"><p>TITOLO E CATEGORIA</p></div>

      <div class="row"><p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean lorem urna, hendrerit quis blandit
          porttitor,
          feugiat id nisl. Duis vitae mi sed nisl aliquam pellentesque. Nulla interdum, turpis vel fringilla eleifend,
          metus mauris rhoncus ipsum, sit
          amet venenatis magna lectus ut urna. Curabitur eget viverra magna. Suspendisse tincidunt turpis id lectus
          tempor, vel vestibulum magna iaculis.
          Morbi quis vestibulum ante. Fusce nec orc</p></div>

    </div>
    <div class="col-1 d-grid gap-2">
      <button type="button" class="btn btn-secondary ">MODIFICA</button>

      <button type="button" class="btn btn-danger">ELIMINA</button>
    </div>

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


