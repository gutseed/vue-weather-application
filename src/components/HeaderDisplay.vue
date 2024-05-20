<template>
  <header class="header">
    <h2>Weather Application</h2>
    <p>{{username}}님 반갑습니다!</p>
  </header>
</template>

<script>
export default {
    name: "HeaderDisplay", 
}
</script>

<style scoped>
.header{
    background: linear-gradient(45deg, #eb0808, #87c502);
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.header h2{
    color: #fff;
}
.header p{
    font-size:14px;
    color: #fff;
}

</style>