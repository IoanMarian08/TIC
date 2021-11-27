<template id="body">
  <div>
    <img id="imgHome" alt="Vue logo" src="./assets/logoaplicatie.png" />
    <HelloWorld msg="Bine ai venit pe E-lectron Components" />
  
    <div id="btnHome">
      <button>Acceseaza aplicatia</button>
      <button id="loginbtn">Login</button>
    </div>
  </div>
</template>


<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
  },
};
</script>


<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

button {
  background-color: #41B783;
  border: none;
  border-radius: 5px;
  padding: 10px 40px;
  font-size: 16px;
  cursor: pointer;
}

button:hover {
  filter: brightness(125%);
}

#imgHome {
  width: 25%;
}

#btnHome {
  display: flex;
  flex-direction: column;
  width: 10%;
  margin: auto;
}

#loginbtn {
  margin-top: 5px;
}


</style>
