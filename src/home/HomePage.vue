<template>
  <div class="home">
    <div>
      <img class="robot" src="../assets/robot-home.png" aria-hidden="true">
    </div>
    <div class="get-started">
      <a href="">Get Started</a> building your first robot!
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomePage',

};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style >
body{
  background: linear-gradient(to bottom, #555,#999);
  background-attachment: fixed;
}

#app{
  font-family: 'Avenir',Helvetica, Arial, sans-serif;
}
main{
  margin: 0 auto;
  padding: 30px;
  background: white;
  width: 1024px;
  min-height:300px;
}

.home{
  text-align: center;
}

.robot{
  height: 300px;
}
</style>
