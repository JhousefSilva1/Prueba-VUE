<template>
  <div class="hello">
   
    <p>
     probando el funcionamiento de la herramienta de Vue<br />
      check out the

      <img class="img1"
        src="https://red.computerworld.es/archivos/202101/glenn-carstens-peters-npxxwgq33zq-unsplash-1-.jpg"
        alt=""
      />
      <p>
      Esta es una imagen de prueba
      </p>




     
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
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

.img1 {
  width: 250px;
  height: 250px;
}
</style>
