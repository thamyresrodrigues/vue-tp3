<template>
  <div>
    <h1>Questao 4</h1>
    <h3>Digite o nome de uma cor para mudar a cor o quadrado:</h3>
    <input type="text" v-on:input="bgc.backgroundColor = $event.target.value"/>
    <div class="quadrado" v-bind:style="bgc"></div>
  </div>
</template>

<script>
export default {
    data() {
      return{
       bgc: {
			backgroundColor: ''
		}
    }
  }
};
</script>

<style>
.quadrado {
  margin-top: 10px;
  width: 100px;
  height: 100px;
  background: #000000;
}
</style>