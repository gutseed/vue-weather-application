<template>
  <HeaderDisplay />
  <WeatherContent />
</template>

<script>
import HeaderDisplay from './components/HeaderDisplay.vue'
import WeatherContent from './components/weather/WeatherContent.vue'

export default {
  name: 'App',
  components: {
    HeaderDisplay,
    WeatherContent,

  },
}
</script>

<style>

</style>
