<template>
    <div class="nav-root">
        <div><h1>Isaak Adams</h1></div>
        <div><a href="#skills-root">Skills</a></div>
        <div><a href="#gallery-root">Projects</a></div>
    </div>
</template>

<script>
    export default {

    }
</script>

<style scoped>
    a {
        text-decoration: none;
        color: black;
    }

    a:hover {
        color: #EDEDE9;
    }

    .nav-root {
        display: flex;
        align-items: center;
        font-size: 1.5rem;
        padding: 10px;
        background-color: #D5BDAF;
    }

    .nav-root > h1 {
        font-family: 'Montserrat', sans-serif;
        font-weight: bold;
    }

    .nav-root > div {
        margin-left: 10px;
        margin-right: 10px;
    }
</style>