<template>
  <div>
    <FooterUp />
    <FooterDown />
  </div>
</template>

<script>
import FooterUp from './FooterUp.vue';
import FooterDown from './FooterDown.vue';

export default {
  name: 'FooterComp',
  components:{
    FooterUp,
    FooterDown,
  }
}
</script>

<style scoped lang="scss">

</style>