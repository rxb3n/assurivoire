<template>
    <div class="serv-container">
        <p class="big bold" id="services">Our Services</p>

        <div class="serv-wrapper">

            <div class="serv-card">
                <img class="serv-img" src="../assets/serv1.jpg" alt="">
                <p class="bold">Vehicle Insurance</p>
                <p>Comprehensive coverage for your vehicles, ensuring <br>
                peace of mind on the roads.</p>
            </div>

            
            <div class="serv-card">
                <img class="serv-img" src="../assets/serv2.jpg" alt="">
                <p class="bold">Property Insurance</p>
                <p>Protect your valuable assets with our customized <br>property insurance solutions.</p>
            </div>

            
            <div class="serv-card">
                <img class="serv-img" src="../assets/serv3.webp" alt="">
                <p class="bold">Health Insurance</p>
                <p>Affordable health insurance plans to safeguard your well- <br>being and cover medical expenses.</p>
            </div>

        </div>

    </div>

</template>


<style scoped>

#services {
    text-align: start;
    padding-left: 3%;
}
.serv-container {
    padding: 5%;
    background-color:var(--secondary-color);
    color: white;
}

.serv-wrapper {
    background-color:var(--secondary-color);
    display: flex;
    justify-content: space-around;
}


.serv-img {
    border-radius: 18px;
    height: 40dvh;
    width: 25dvw;
}

.bold {
    font-size: 1.5em;
}

.big {
    font-size: 2.5em;
}


@media screen and (max-width: 1000px) {
    .serv-wrapper {
        display: flex;
        justify-content: space-around;
        flex-wrap: wrap;
    }

    .serv-img {
        width: 90%;
    }
}

</style>