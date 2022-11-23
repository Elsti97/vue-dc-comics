<template>
    <!-- BLUE ROW -->
    <div class="blue-row">
      <div class="width-80">
        <ul>
          <li>
            <img src="../assets/img/buy-comics-digital-comics.png" alt="dc comics">
            <span>DIGITAL COMICS</span>
          </li>
          <li>
            <img src="../assets/img/buy-comics-merchandise.png" alt="dc merch">
            <span>DC MERCHANDISE</span>
          </li>
          <li>
            <img src="../assets/img/buy-comics-subscriptions.png" alt="subs">
            <span>SUBSCRIPTION</span>
          </li>
          <li>
            <img src="../assets/img/buy-comics-shop-locator.png" alt="comic locations">
            <span>COMIC SHOP LOCATOR</span>
          </li>
          <li>
            <img class="payment" src="../assets/img/buy-dc-power-visa.svg" alt="payments">
            <span>DC POWER VISA</span>
          </li>
        </ul>
      </div>
      
    </div>
</template>

<script>
export default {
  name: 'MainComp',
}
</script>

<style scoped lang="scss">
  .width-80{
  width: 80%;
  margin: auto;
}

.blue-row{
  background-color: #2F82F9;
  padding-top: .1rem;
}

ul{
  align-self: center;
  display: flex;
  justify-content: space-between;
}

li{
  list-style: none;
  display: flex;
  align-items: center;
}

img{
  height: 40%;
  margin-right: .5rem;
}

.payment{
  height: 30%;
}

span{
  color: white;
  font-size: 1rem;
}
</style>