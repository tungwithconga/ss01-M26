<template>
  <div class="main">
    <div v-for="n in 12" :key="n" class="cart">Cart</div>
  </div>
</template>

<script>
export default {
  name: 'Main'
};
</script>

<style scoped>
.main {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 10px;
  padding: 20px;
  background-color: #ffebee;
  flex-grow: 1;
}

.cart {
  background-color: white;
  padding: 20px;
  text-align: center;
  border: 1px solid #ccc;
  display: flex;
  justify-content: center;
  align-items: center;
  color:black;
}
</style>
