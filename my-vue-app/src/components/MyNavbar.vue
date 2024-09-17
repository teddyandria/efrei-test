<script>
export default {
    name: "MyNavbar",
}
</script>

<template>
    <div class="hello">
        <ul class="navbar">
            <li><a href=""></a>Home</li>
            <li><a href=""></a>Catalog</li>
            <li><a href=""></a>About Us</li>
            <li><a href=""></a>Contact</li>
        </ul>
    </div>
</template>

<style scoped>
.navbar {
    display: flex;
    justify-content: space-around;
    list-style-type: none;
    background-color: bisque;
    padding: 15px;
}

.headTitle {
    text-align: center;
}
</style>