<script setup lang="ts">

const openReadmeInEditor = () => fetch('/__open-in-editor?file=README.md')
</script>

<template>
    <div id="container">

    </div>
</template>

<style scoped>
#container {
    background: #41445A;
    box-shadow: 30px 30px 80px -7px #161B23;
    border-radius: 42px;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
    padding: 50px 100px 50px 100px;
}
</style>