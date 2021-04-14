<template>
    <div>
       <h2>LOGO</h2>
       <a href="#">Menu</a>
       <a href="#">About Us</a>
       <a href="#">Contact</a>
       <a href="#">Jobs</a>
    </div>
</template>

<script>
    export default {
        name: "page-header"
    }
</script>

<style scoped>
div{
    display: grid;
    place-items: center;
    grid-auto-flow: column;
}

a{
    padding: 10px;
}


</style>