<template>
  <div class="between">
    <img src="../assets/img/dc-logo.png" alt="Logo header">
    <div>
      <ul>
        <li>CHARACTERS</li>
        <li>COMICS</li>
        <li>MOVIES</li>
        <li>TV</li>
        <li>GAMES</li>
        <li>COLLECTIBLES</li>
        <li>VIDEOS</li>
        <li>FANS</li>
        <li>NEWS</li>
        <li>SHOP</li>
      </ul>
    </div>
  </div>

</template>

<script>
export default {
  name: 'HeaderComp',
}
</script>

<style scoped lang="scss">
*{
  display: flex;
}

.between{
  justify-content: space-around;
  width: 80%;
  margin: auto;
}

ul{
  align-self: center;
}

li{
  padding: .5rem;
}
</style>