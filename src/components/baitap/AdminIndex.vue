<template>
  <div class="admin-layout">
    <Header />
    <div class="content">
      <Menu />
      <Main />
    </div>
    <Footer />
  </div>
</template>

<script>
import Header from "./Adminindex/Header.vue"
import Menu from "./Adminindex/Menu.vue"
import Main from "./Adminindex/Main.vue"
import Footer from "./Adminindex/Footer.vue"
export default {
  components: {
    Header,
    Menu,
    Main,
    Footer
  }
};
</script>

<style scoped>
.admin-layout {
  display: flex;
  flex-direction: column;
  height: 100vh;
  width: 1300px;
}

.content {
  display: flex;
  flex: 1;
}

footer {
  margin-top: auto;
}
</style>
