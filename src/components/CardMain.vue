<template>
  <div class="card">
    <div>
      <img :src="comics.thumb" alt="copertina">
      <h4>{{comics.series}}</h4>
    </div>    
  </div>
</template>

<script>
export default {
  name: 'MainBlack',

  props:{
  comics: Object,
  }
}
</script>

<style lang="scss">

.card{
  width: calc(100%/6);
  padding-top: 2rem;
}
</style>