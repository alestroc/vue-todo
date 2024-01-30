
<script>

export default {
  name: 'App',
  components: {

  }
}
</script>


<template>
  <div class="container">

    <div class="row">
      <h1>Todo Web</h1>

      <div class="col-6 new_task">
        <h3>Add a new Task</h3> 
        <form action="">
          <input type="text" placeholder="Task title">
          <select name="category" id="category">
            <option value="business">Business</option>
            <option value="personal">Personal</option>
            <option value="hobby">Hobby</option>
          </select>

          <textarea cols="30" rows="2" placeholder="Add a  description"></textarea>
          <input type="submit" value="Add Task">

        </form>
      </div>
    </div>

    <div class="row">
      <div class="col-6">
        <h3>List of Task</h3> <br>
        <input type="checkbox"> 
        <span>[Categoria]  <br>Task 1</span>
        <p> 'DATA' -  lorem e qualcosa del genere</p>

      </div>
    </div>
  </div>
</template>





