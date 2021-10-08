<template>
    <div><button class="button">Hello there</button></div>
</template>

<script>
     export default{
        name: 'Button',
    }
</script>

<style scoped>
    .button {
        border: none;
        color: white;
        background: grey;
        outline: none;
        height: 40px;
        width: 150px;
        border-radius: 50px;
        transition: all ease 0.3s;
    }
    .button:hover {
        background: red;
    }
</style>
