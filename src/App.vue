<template>
  <div id="app">
    <header>
      <nav>
        <ul>
          <li class="nav-item">
            <img src="./assets/build-a-bot-logo.png" class="logo" alt="">
            Build a bot
          </li>
          <li>
          </li>
          <li></li>
          <li></li>
        </ul>
      </nav>
    </header>
   <main>
     <!-- <HomePage msg="Welcome to Your Vue.js App"/> -->
     <RobotBuild />
    </main>

  </div>
</template>

<script>
// import HomePage from './home/HomePage.vue';
import RobotBuild from './build/RobotBuild.vue';

export default {
  name: 'App',
  components: {
    // HomePage,
    RobotBuild,
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

header {
  background-color: #999;
  width: 1084px;
  margin: 0 auto;
}
ul {
  padding: 3px;
  display: flex;
  list-style-type: none
}
.nav-item {
  display: inline-block;
  padding: 5px 10px;
  font-size: 22px;
  border-right: 1px solid #bbb;
}
.logo {
  vertical-align: middle;
  height: 30px;
}

</style>
