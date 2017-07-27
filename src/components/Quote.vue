<template>
    <div>
        <slot></slot>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
    div {
        background-color: beige;
        border: 1px solid #5e43cc;
        box-shadow: 1px 2px 5px #888888;
        padding: 30px;
        margin: 30px auto;
        text-align: center;
    }
    h2{
        color: red;
    }
</style>