<template>
    <!-- BLACK ROW -->
    <div class="black-row">
      <div class="width-80">
        <h1>-- Content goes here -- </h1>
      </div>
    </div>
</template>

<script>
export default {
  name: 'MainComp',
}
</script>

<style scoped lang="scss">
  .black-row{
    color: white;
    background-color: #1C1C1C;
    padding: 1rem;
  }

  .width-80{
  width: 80%;
  margin-top: 1rem;
  margin: auto;
}
</style>