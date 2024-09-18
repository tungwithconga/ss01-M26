<template>
  <div class="user-layout">
    <Header />
    <Navigation />
    <div class="content">
      <Menu />
      <Main />
      <Article />
    </div>
  </div>
</template>

<script>
import Header from './UserLayout/Header.vue';
import Navigation from './UserLayout/Navigation.vue';
import Menu from './UserLayout/Menu.vue';
import Main from './UserLayout/Main.vue';
import Article from './UserLayout/Article.vue';

export default {
  components: {
    Header,
    Navigation,
    Menu,
    Main,
    Article
  }
};
</script>

<style scoped>
.user-layout {
  display: flex;
  flex-direction: column;
  height: 100vh;
}

.content {
  display: flex;
  flex: 1;
}
</style>
