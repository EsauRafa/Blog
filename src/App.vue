<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <header>
    <img src="./assets/etec.png" width="150" height="60">
  </header>
  
  <div class="posts">
    <figure style="text-align: center;">
      <br>
    <img src="./assets/post1.jpg" width="550" height="300" >
    </figure>
    <div>
      <h2 class="titulo">
        Desenvolvendo em SQL
      </h2>
      <h3 class="descricao">
        Aqui veremos muito sobre como podemos utilizar o SQL
      </h3>
      <h3 class="autor">Esau Rafael</h3>
    </div>
  </div>

  <div class="posts">
    <figure style="text-align: center;">
      <br>
    <img src="./assets/post2.jpg" width="550" height="300" >
    </figure>
    <div>
      <h2 class="titulo">
        Aulas Funcionais de JavaScript
      </h2>
      <h3 class="descricao">
        Participe da série de JavaScript(JS) e aprimore suas habilidades
      </h3>
      <h3 class="autor">Esau Rafael</h3>
    </div>
  </div>

  <div class="posts">
    <figure style="text-align: center;">
      <br>
    <img src="./assets/post3.jpg" width="550" height="300" >
    </figure>
    <div>
      <h2 class="titulo">
        Fundamentos do PHP 7
      </h2>
      <h3 class="descricao">
        Como podemos instalar e configurar para começar a utiliza-lo 
      </h3>
      <h3 class="autor">Esau Rafael</h3>
    </div>
  </div>
</template>

<style scoped>
header {
  line-height: 1.5;
}
.imgem{
  margin: 10px 10px 10px 10px;
}
.titulo{
  color: black;
  font-style:italic;
  margin: 0px 10px 0px 10px;
}
.descricao
{
  margin: 0px 10px 0px 10px;
}
.posts{
  background-color: gray;
  width: 600;
  height: 10000;
  margin: 0px 0px 15px 0px;
}
.autor{
  text-align: right;
  font-style: oblique;
  margin: 6px 10px 4px 10px
}
</style>
