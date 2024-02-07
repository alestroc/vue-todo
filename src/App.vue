
<script>


export default {
  name: 'App',

  data() {
    return {
      formValues: {
        title: '',
        category: '',
        date: '',
        description: '',
      },
    }
  },
  components: {
  },

  methods: {
    submitForm() {
      console.log('Form submitted', this.formValues)}
  },
  mounted() {
    console.log('Component mounted.')
  }
}

</script>

<template>
  <div class="container">
    <h1 class="text-center">Todo Web</h1>
    <!-- row che racchiude l'inserimento della task-->
    <h2>Add a new Task</h2>
    <form @submit.prevent="submitForm">

    <div class="row "> <!-- row dei 3 elementi-->

      <!-- col Title-->
      <div class="col-lg-6 mt-2">

        <input v-model.trim.lazy="formValues.title" class=" form-control" type="text" placeholder="Task title">
      </div>

      <!-- col Category-->
      <div class="col-lg-3 mt-2">
        <select v-model.lazy="formValues.category" class="form-control" name="category" id="category" >

          <option value="business">Business</option>

          <option value="personal">Personal</option>

          <option value="hobby">Hobby</option>
        </select>
      </div>
      <!-- col Date-->
      <div class="col-lg-3 mt-2"> 
        <input v-model.lazy="formValues.date" class="form-control" type="date" name="task-date" id="task-date">
      </div>


      <div class="col-lg-12 mt-2">
        <textarea v-model.lazy="formValues.description" class=" form-control" rows="2" placeholder="Add a  description"></textarea>
      </div>
    </div>

    <button @click="submitForm" class="btn btn-primary w-100 py-4 mt-2" type="button" >Add a task</button>

  </form>

    <hr>

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
  </div>
</template>






<!-- controllo form - dati inseriti
  <div>

    <pre>
      {{ JSON.stringify((formValues), null, 2)}}

    </pre>
  </div>
-->
