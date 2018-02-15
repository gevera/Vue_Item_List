<template>
  <div class="header">
    <h1>{{ storeName }}</h1>
    <hr/>
  </div>
</template>

<script>
export default {
  name: "Header",
  data() {
    return {
      storeName: "Save-A-Lot"
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  font-weight: 100;
}
</style>
