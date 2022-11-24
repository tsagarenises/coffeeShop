<template>
  <div>
    <HeaderTemplate/>
    <SliderComponent />
    <HomePage />
    <FooterComponent/>

  </div>
</template>
<script>
import HomePage from './components/HomePage.vue'
import HeaderTemplate from './components/HeaderTemplate.vue'
import SliderComponent from './components/SliderComponent.vue'
import FooterComponent from './components/FooterComponent.vue'

export default {
  name: 'App',
  components:{
    HomePage, HeaderTemplate, SliderComponent, FooterComponent
  },
  
}
</script>

