<template>
  <!-- <div id="nav">
    <router-link to="/">Home</router-link> |
    <router-link to="/login">Login</router-link> |
    <router-link to="/publish/task">Publish Task</router-link>
  </div>
  <router-view/> -->
  <div class="docker">
    <span class="docker__item docker__item--active">
      <div class="iconfont">&#xe6ac;</div>
      <div class="docker__title">Home</div>
    </span>
    <span class="docker__item">
      <div class="iconfont">&#xe685;</div>
      <div class="docker__title">Publish</div>
    </span>
    <span class="docker__item">
      <div class="iconfont">&#xe6e9;</div>
      <div class="docker__title">Contact</div>
    </span>
    <span class="docker__item">
      <div class="iconfont">&#xe658;</div>
      <div class="docker__title">My</div>
    </span>
  </div>
</template>

<style lang="scss">
.docker{
  display: flex;
  position: absolute;
  padding: 0 .18rem;
  left: 0;
  bottom: 0;
  width: 100%;
  height: .53rem;
  border-top: 1px solid #F1F1F1;
  background-color: orange;
  &__item {
    flex: 1;
    text-align: center;
    .iconfont {
      margin: .07rem 0 .02rem 0;
      font-size: .22rem;
    }
    &--active {
      color: #1FA4FC;
    }
  }
  &__title {
    font-size: 20px;
    margin-top: -.09rem;
    transform: scale(0.5, 0.5);
    transform-origin: center top;
  }

}

.docker__item {

}
.docker__title {
  font-size: 20px;
  margin-top: -.09rem;
  transform: scale(0.5, 0.5);
  transform-origin: center top;
}

.docker__item--active {
  color: #1FA4FC;
}
/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
} */
</style>
