<template>
    <div class="container">
        <div class="row">
            <h2>Главная</h2>

            <app-quote quote="Это прекрасная цитата!"></app-quote>

        </div>
    </div>
</template>

<script>
    import Quote from './components/Quote.vue';

    export default {
        components: {
            appQuote: Quote
        }
    }
</script>

<style>
    .row{
        background-color: bisque;
        padding: 10px;
        border: 1px solid #c6c4cb;
    }
</style>
