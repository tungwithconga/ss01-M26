<template>
   <div class="card">
        <div class="card-image">
            Image
        </div>
        <div class="card-content">
            <h3>Title</h3>
        </div>
        <div class="card-action">
            <button>Add to cart</button>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}

.card {
    width: 200px;
    border: 1px solid #ccc;
    border-radius: 10px;
    overflow: hidden;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    text-align: center;
}

.card-image {
    background-color: #888;
    padding: 40px;
    color: white;
    font-size: 18px;
}

.card-content {
    padding: 20px;
    background-color: white;
    color:black;
}

.card-action {
    padding: 20px;
    background-color: #f9f9f9;
    border-top: 1px solid #ccc;
}

button {
    padding: 10px 20px;
    background-color: white;
    border: 1px solid #ccc;
    border-radius: 5px;
    cursor: pointer;
}

button:hover {
    background-color: #c88989;
}

</style>