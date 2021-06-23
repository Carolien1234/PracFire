<template>
  <button v-on:click="login()">
    Skaap
  </button>
</template>

<script>
export default {
  name: "Login",
  methods:{
    login(){
      this.$http.post().then((res)=>{
        console.log(res);
      });
    }
  }
}
</script>

<style scoped>

</style>