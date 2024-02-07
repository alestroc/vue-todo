


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
  <div>
    <ul>
  <li v-for="task in taskList" :key="task.id">
     -  {{ task.id }} - {{ task.title }} - {{ task.category }} - {{ task.date }} - {{ task.description }} 
</li>
</ul>
  </div>

</template>

<script>
// export che serve per importare il componente in app.vue
// name è il nome del componente che verrà usato in app.vue
export default {
  name: 'ListTask',
  data() {
    return {
      taskList: [
        {
          id: 1,
          title: 'Task 1',
          category: 'Work',
          date: '2021-10-01',
          description: 'This is the first task'
        },
        {
          id: 2,
          title: 'Task 2',
          category: 'Home',
          date: '2021-10-02',
          description: 'This is the second task'
        },
        {
          id: 3,
          title: 'Task 3',
          category: 'Hobby',
          date: '2021-10-03',
          description: 'This is the third task'
        }
      ]
    }

  },

}

</script>