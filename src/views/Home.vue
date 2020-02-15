<template>
  <div class="home">
    <img alt="Fuk U Gonna Do? Fite Me?" src="../assets/logo.png" width=350/>
    <h1 class="bigText">Huh? Huh?</h1>
    <div class="press">
    <router-link class="take-picture-button mdl-button mdl-js-button mdl-button--fab mdl-button--colored" to="/camera">
      <img class="press" alt="camera" src="../assets/camera.jpg" width=128/>
    </router-link>
  </div>
  </div>
</template>

<style lang="scss" scoped>
.bigText {
  font-size: 50pt;
}
.press {
  margin-top: 20px;
}
</style>
