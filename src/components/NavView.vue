<template>
    <div class="nav-container">

        <div class="nav-title">
            <h1>AssurIvoire</h1>
        </div>

        <div class="nav-socials">
            <img src="../assets/facebook.png" height="48">
            <img src="../assets/insta.png" height="48">
            <img src="../assets/twitter.png" height="48">
        </div>

    </div>
</template>


<style scoped>

.nav-container {
    display: flex;
    justify-content: space-around;
    background-color: var(--primary-color);
    height:10dvh;
    align-items: center;
    top: 0;
    position: sticky;
}

.nav-socials {
    width: 20dvw;
    display: flex;
    justify-content: space-around;
    filter: invert();
}

.nav-socials img {
    height: 4dvh;
}

.nav-title {
    text-align: center;
    font-size: 1.15em;
    color: white;
}


</style>