<script>
  export default {
    data(){
      return{
        title: 'HELLO VITE',
        description: 'ViteJS è uno strumento di compilazione e un server di sviluppo locale. Semplifica lo sviluppo front-end delle moderne applicazioni web ricaricando dinamicamente i moduli del codice per evitare di ricompilare l\'intera applicazione.'
      }
    }
  }
</script>

<template>
  <div>
    <div class="big-big circle">
      <div class="big circle">
        <div class="circle flex-col">
          <h1>{{ title }}</h1>
          <p>{{ description }}</p>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>

h1{
  text-align: center;
  color: #b65552;
  font-size: 5rem;
  line-height: 1.1;  
  margin-bottom: 10px;
  margin-top: 10px;
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

p{
  text-align: center;
  margin-top: 0;
  font-size: 15px;
  width: 300px;
}

</style>
