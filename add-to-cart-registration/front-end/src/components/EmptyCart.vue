<template>
<div style="text-align:center;" class="container my-5">
    <img src="../assets/shopping-cart.svg" alt="shopping-cart" width="200px">
    <div class="mt-4">
        <h4 class="orange-red fw-600">Your cart is empty</h4>
        <h5 class="darkblue fw-600">You can go to home page to view more food items.</h5>
    </div>
</div>
</template>

<script>
export default {
    name:"EmptyCart"
}
</script>

<style scoped>
.orange-red{
    color: orangered;
}
.darkblue{      
    color: darkblue;
}

.fw-600{
    font-weight: 600;
}
</style>