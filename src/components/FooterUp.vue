<template>
  <div class="bg-footer">
    <div class="width-80 space-between">
      <!-- LIST LEFT -->
      <div class="flex">
        <ul>
          <h3>DC COMICS</h3>
          <li>Characters</li>
          <li>Comics</li>
          <li>Movies</li>
          <li>TV</li>
          <li>Games</li>
          <li>Videos</li>
          <li>News</li>
          <h3>SHOP</h3>
          <li>Shop DC</li>
          <li>Shop DC Collectibles</li>
        </ul>

        <ul>
          <h3>DC</h3>
          <li>Terms Of Use</li>
          <li>Privacy policy (New)</li>
          <li>Ad Choices</li>
          <li>Advertising</li>
          <li>Jobs</li>
          <li>Subscriptions</li>
          <li>Talent Workshops</li>
          <li>CPSC Certificates</li>
          <li>Ratings</li>
          <li>Shop Help</li>
          <li>Contact Us</li>
        </ul>

        <ul>
          <h3>SITES</h3>
          <li>DC Magazine</li>
          <li>MAD Kids</li>
          <li>DC Kids</li>
          <li>DC Universe</li>
          <li>DC Power Visa</li>
        </ul>
      </div>

      <!-- LOGO BIG -->
      <div>
        <img src="../assets/img/dc-logo-bg.png" alt="big logo">
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
  .width-80{
  width: 80%;
  margin: auto;
}

.bg-footer{
  background: url('../assets/img/footer-bg.jpg');
  padding-top: 1rem;
  background-repeat: no-repeat;
  background-size: 100%;
}

.space-between{
  justify-content: space-between;
  margin: 1rem auto 0 auto;
  display: flex;
}

h3{
  color: white;
}

.flex{
  display: flex;
}

ul{
  flex-direction: column;
  flex-wrap: wrap;
  align-content: flex-start;
}

li{
  color: #959595;
  list-style: none;
  font-size: .9rem;
  line-height: 1.5rem;
}
</style>