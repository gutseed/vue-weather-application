<template>
  <div>
    <ul class="weather-list">
        <WeatherItem v-for="weather in weatherList" :key="weather.code" :weather="weather"/>
    </ul>
  </div>
</template>

<script>
import WeatherItem from './WeatherItem.vue'
export default {
    name: "WeatherList", 
    components:{
        WeatherItem, 
    },
    props: {
        weatherList: Array 
    }
}
</script>

<style scoped>
.weatherList{
    display: grid;
    margin-top: 1em;
    grid-template-columns: repeat (5,1fr);
    grid-gap: 1em ;

}
</style>