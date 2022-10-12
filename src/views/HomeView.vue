<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">

    <button @click="goToDayBook" class="btn btn-primary">button1 </button>
    <button @click="goToDayBook" class="btn btn-success">button2 </button>
    <button @click="goToDayBook" class="btn btn-info">button3 </button>
     
  </div>
</template>

<script>
// @ is an alias to /src


export default {
  name: 'HomeView',
  components: {

  },
  methods:{
    goToDayBook(){
      this.$router.push({name:'no-entry'})
    }
  }
}
</script>
