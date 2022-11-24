<template>
  <div class="space-between">
    <img src="../assets/img/dc-logo.png" alt="Logo header" class="logo-header">
    <div>
      <ul>
        <li><a href="#">CHARACTERS</a></li>
        <li><a href="#" class="active">COMICS</a></li>
        <li><a href="#">MOVIES</a></li>
        <li><a href="#">TV</a></li>
        <li><a href="#">GAMES</a></li>
        <li><a href="#">COLLECTIBLES</a></li>
        <li><a href="#">VIDEOS</a></li>
        <li><a href="#">FANS</a></li>
        <li><a href="#">NEWS</a></li>
        <li><a href="#">SHOP</a></li>
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

.space-between{
  justify-content: space-between;
  width: 80%;
  margin: auto;
}

.logo-header{
  margin: .5rem;
}

ul{
  align-self: center;
  margin: 0;
}

.active{
  color: #2F82F9;
  border-bottom: 5px solid #2F82F9;
}

a{
  color: black;
  text-decoration: none;
  padding: 3rem .5rem;
}
</style>