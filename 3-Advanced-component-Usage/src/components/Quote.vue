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
    export default {
        
    }
</script>

<style scoped>
    div {
        border: 1px solid #ccc;
        box-shadow: 1px 1px 2px #000;
        padding: 30px;
        text-align: center;
    }
    h1 {
        color: red;
    }
</style>