<template>
  <div class="bg-footer-down z-index">
    <div class="width-80 flex-center">
      <!-- BUTTON SIGN IN -->
      <div>
        <button>SIGN-UP NOW!</button>
      </div>

      <!-- SOCIALS -->
      <div class="flex-center padding-l-1">
        <h2>FOLLOW US</h2>
        <img src="../assets/img/footer-facebook.png" alt="logo facebook">
        <img src="../assets/img/footer-twitter.png" alt="logo twitter">
        <img src="../assets/img/footer-youtube.png" alt="logo youtube">
        <img src="../assets/img/footer-pinterest.png" alt="logo pinterest">
        <img src="../assets/img/footer-periscope.png" alt="logo periscope">
      </div>
    </div>
    
  </div>
</template>

<script>
export default {
name: 'FooterComp',
}
</script>

<style scoped lang="scss">
.bg-footer-down{
  background-color: #303030;
  position: relative;
  z-index: 1;
}

.width-80{
  width: 80%;
  margin: auto;
  display: flex;
  justify-content: space-between;
}

.flex-center{
  display: flex;
  align-items: center;
}

button{
  border: 2px solid #0282F9;
  background-color: #303030;
  color: white;
  margin: 2rem 0;
  padding: 1rem ;
}

h2{
  color: #0282F9;
}

.padding-l-1 > *{
  padding-left: 1rem;
}
</style>