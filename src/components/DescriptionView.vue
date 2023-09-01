<template>
    <div class="description-container">
        <div class="desc-wrapper">
        <p class="bold">About us</p>
        <p class="description-text">
            AssurIvoire is a leading insurance broker based in Abidjan, Côte d'Ivoire. 
            With our extensive industry knowledge and expertise, 
            we provide tailored insurance solutions to individuals and businesses across the region. 
            Our team of experienced professionals is committed to delivering exceptional service 
            and ensuring that our clients receive the best coverage for their specific needs. 
            At AssurIvoire, we take pride in our strong relationships with top insurance providers, 
            allowing us to offer a wide range of policies at competitive prices. 
            Whether you are looking for personal insurance or 
            comprehensive coverage for your business, 
            you can trust AssurIvoire to provide reliable and 
            efficient insurance solutions.
        </p>
    </div>
        
    </div>
</template>


<style scoped>

.description-container {
    background-color: var(--secondary-color);
    display: flex;
    justify-content: space-around;
    padding: 5%;
    font-size: 20px;
    color: white;
}

.desc-wrapper {
    display: flex;
    text-align: start;
    flex-direction: column;
}

.bold {
    font-size: 2em;
}

@media screen and (max-width: 1000px) {
    .description-container {
        display: flex;
        flex-direction: column;
    }

}

</style>