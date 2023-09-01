<template>
    <div class="hero-container">
        <p class="hero-text bold">Protect Your Future <br>Today</p>
        <p class="hero-text">Secure your assets with our trusted insurance brokering services. Get <br>
        peace of mind with AssurIvoire.</p>
    </div>
</template>

<style scoped>

.hero-container {
    background: linear-gradient(var(--primary-color), var(--secondary-color));
    display: flex;
    justify-content: center;
    flex-direction: column;
    text-align: start;
    padding: 8%;
}

.hero-text {
    color: white;
    font-size: 1.5em;
}

.bold {
    font-weight: 700;
    font-size: 3.5em;
}

.hero-btn {
    background-color: #E2CFEA;
    width: fit-content;
    border: none;
    border-radius: 15px;
    padding: 1%;
    font-size: 1.25em;
}

.hero-btn-container {
    display: flex;
    justify-content: center;
}

</style>