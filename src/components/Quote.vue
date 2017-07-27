<template>
    <div>
        <div class="title">
            <slot name="title"></slot>
        </div>
        <hr>
        <div>
            <slot name="content"></slot>
        </div>
    </div>
</template>

<script>
    export default {}
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

    h2 {
        color: red;
    }

    .title {
        font-style: italic;
    }
</style>