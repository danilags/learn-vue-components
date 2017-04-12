<template>
  <div class="">
    <manage-products></manage-products>
  </div>

</template>

<script>
import ProductList from './components/ProductList';
import SaveProductForm from './components/SaveProductForm';
import ManageProducts from './components/ManageProducts';

export default {

  components: {
    ProductList,
    SaveProductForm,
    ManageProducts
  }
}

</script>
