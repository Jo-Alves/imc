<template>
  <div id="app">
    <div class="card-imc">
      <div class="row"><input placeholder="Altura" maxlength="10" autofocus/></div>
      <div class="row"><input placeholder="Massa" maxlength="10"/></div>
      <button class="calc">Calcular</button>
      <p><b>IMC: </b></p>
      <p><b>OBS: </b></p>
  </div>
  </div>
</template>

<script>

export default {
  name: 'App',
}
</script>

<style>
*{
  box-sizing: border-box;
  color: white;
  font-size: 20px;
  margin:0;
  padding: 0;
  letter-spacing: 1px;
}
#app {
  background-color: #ccc;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  
}
.card-imc{  
  background-color: rgb(116, 116, 182);
  box-shadow: 8px 8px 2px rgb(88, 88, 136);
  width: 350px;
  border-radius: 10px;
  padding: 20px;
}

input{
  padding: 5px;
  width: 100%;
  text-align: right;
  border: none;
  outline: none;
  margin-bottom: 2px;
  background: none;
}

input::placeholder{
  color: black
}


.row{
  border-bottom: 2px solid #ccc;
  margin-bottom: 10px;
}

.calc{
  margin-top: 10px;
  border: none;
  outline: none;
  padding: 10px 15px;
  background-color: brown;
  color: white;
  width: 300px;
  border-radius: 5px;
  cursor: pointer;
}
p{
  text-align: left;
  margin-top: 20px;
}
</style>
