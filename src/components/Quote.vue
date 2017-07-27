<template>
    <div>
        <p>{{quote}}</p>
    </div>
</template>

<script>
export default {
    props: ['quote']
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
</style>