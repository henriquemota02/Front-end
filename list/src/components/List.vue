<template>
  <div>
    <ul id="lista">
      <li v-for="item in items" :key="item.message">
        {{ item.message }}
      </li>
    </ul>
  </div>
</template>

<script>
var example2 = new Vue({
  el: "lista",
  data: {
    parentMessage: "numero",
    items: [
      { message: "Afonso Miguel Pinto Vieira" },
      { message: "Diogo Augusto Rodrigues Livramento" },
      { message: "Diogo Filipe Romão Perestrelo" },
      { message: "Érica Rubina Brito Camacho" },
      { message: "Gonçalo Nuno Nóbrega Chaves" },
      { message: "Henrique Sousa Mota" },
      { message: "João Afonso Sardinha Reis" },
      { message: "João Nicolau Silva Pinto" },
      { message: "Luís António Ferro de Almeida" },
      { message: "Luís Gonçalo Costa Gonçalves" },
      { message: "Luís Manuel Alves Gomes" },
      { message: "Marcelo André Silva de Freitas" },
      { message: "Maria Gorete Freitas Leça" },
      { message: "Pedro Augusto Reynolds Vieira" },
      { message: "Rúben Dinarte Rodrigues Nascimento" },
      { message: "Tiago Ribeiro" },
      { message: "Tomás Tranquada Gomes Brazão" },
      { message: "Vítor Gonçalo Freitas Quintal" },
      { message: "Vítor Hugo Ferreira Rodrigues" },
    ],
  },
});
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
