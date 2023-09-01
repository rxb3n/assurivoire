<template>

<NavView/>
<HeroView/>
<BannerView/>
<DescriptionView/>
<ServicesView/>
<ReviewView/>
<ClientView/>
<LocationView/>
<FooterView/>

</template>

<script>
import NavView from './components/NavView.vue'
import HeroView from './components/HeroView.vue'
import DescriptionView from './components/DescriptionView.vue'
import ServicesView from './components/ServicesView.vue'
import ReviewView from './components/ReviewView.vue'
import FooterView from './components/FooterView.vue'
import LocationView from './components/LocationView.vue'
import BannerView from './components/BannerView.vue'

export default {
  name: 'App',
  components: {
    NavView,
    HeroView,
    DescriptionView,
    ServicesView,
    ReviewView,
    FooterView,
    LocationView,
    BannerView,
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto+Slab:wght@400;500;700&display=swap');

:root {
  --primary-color: #1F1F1F;
  --secondary-color: #242424;
}

body, h1, h2, h3, h4, h5, h6{
  margin: 0;
  padding: 0;
  font-family: 'Roboto Slab', serif;
}

</style>
