<template>
    <div style="width:50%" class="row">
        <div class="col-md-4">
            <h6>Total:</h6>
            <h6>Promo Code:</h6>
            <h6>Shipping:</h6>
            <div class="my-3 line w-120"></div>
            <h6>Subtotal</h6>
        </div>
        <div class="col-md-4">
            <h6>Rs {{totalPrice}}</h6>
            <h6>SWEETDISH</h6>
            <h6>Rs 50</h6>
            <div class="my-3 line w-60"></div>
            <h6>Rs {{totalPrice + 50}}</h6>
        </div>
    </div>
</template>

<script>
export default {
    name: "Summary",
    props:["totalPrice"]
}
</script>

<style scoped>
.line {
    height: 1px;
    border-bottom: 2px solid black;
}
.w-120{
    width: 120%;
}
.w-60{
    width: 60%;
}
</style>
