<script>
  export default {
    data(){
      return{
        title: 'HELLO VITE'
      }
    }
  }
</script>

<template>
  <div>
    <div class="big-big circle">
      <div class="big circle">
        <div class="circle">
          <h1>{{ title }}</h1>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>

h1{
  text-align: center;
  color: #b65552;
  font-size: 7rem;
  line-height: 1.1;  
}

.circle{
  width: 400px;
  height: 400px;
  border-radius: 50%;
  background-color: #fff5bb;
  display: flex;
  justify-content: center;
  align-items: center;
}

.circle.big{
  width: 500px;
  height: 500px;
  background-color: #c44e4e; 
}

.circle.big-big{
  width: 600px;
  height: 600px;
  background-color: #ffb95f;
}

</style>
