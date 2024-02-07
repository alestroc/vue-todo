
<script>
// import "nome da usare nel file" from "path del file"
import AddTask from './screens/AddTask.vue'
import ListTask from './screens/ListTask.vue';

export default {
  name: 'App',

  data() {
    return {
      
    }
  },
  components: {
    //nomi importati da usare nel template
    AddTask,
    ListTask,
},

  methods: {
    
}
}

</script>

<template>
  <AddTask></AddTask>
  <ListTask>  </ListTask>
</template>






<!-- controllo form - dati inseriti
  <div>

    <pre>
      {{ JSON.stringify((formValues), null, 2)}}

    </pre>
  </div>
-->
