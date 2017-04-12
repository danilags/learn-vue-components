<template>
  <div>
    <h1 class="header">Game Card</h1>
    <table class="table table-hover product-table">
      <thead>
        <tr>
          <th>Name</th>
          <th>Description</th>
          <th>Price</th>
        </tr>
      </thead>
      <tbody>
        <tr v-for="product in products" track-by="id">

          <td>{{product.name}}</td>
          <td>{{product.description}}</td>
          <td>{{product.price}}:-</td>
        </tr>
      </tbody>
    </table>
  </div>
</template>

<script>
  export default {
    props: ['products']
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .header {
    font-size: 4rem;
  }
</style>
