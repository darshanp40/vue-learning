<template>
    <div class="container">
        <div class="row">
            <div class="col-xs-12">
               <app-quote>
                   <h1 slot="title">A Quote</h1>
                   <p slot="content">A wonderful quote</p>
               </app-quote>
            </div>
        </div>
    </div>
</template>

<script>
    import Quote from './Components/Quote.vue'
    export default {
        components: {
            appQuote: Quote
        }
    }
</script>

<style>
</style>
