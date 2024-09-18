<template>
  <div class="block">
    <div class="block1">Box</div>
    <div class="block2">Box</div>
    <div class="block3">Box</div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.block{
    display:flex;
}
.block1{
    width: 200px;
    height: 200px;
    background-color: red;
    display: flex;
    justify-content: center;
    align-items: center;
    margin:20px;
}
.block2{
    width: 200px;
    height: 200px;
    background-color: rgb(17, 23, 203);
    display: flex;
    justify-content: center;
    align-items: center;
    margin:20px;
}
.block3{
    width: 200px;
    height: 200px;
    background-color: rgb(3, 244, 27);
    display: flex;
    justify-content: center;
    align-items: center;
    margin:20px;
}
</style>