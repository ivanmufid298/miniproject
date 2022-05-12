<template>
  <div>
    <Navbar />
    <div class="container">
      <ProductList />
    </div>
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from "@/components/Navbar.vue";
import ProductList from "@/components/ProductList.vue";
import Footer from "@/components/Footer.vue";
export default {
  name: "Products",
  components: {
    Navbar,
    ProductList,
    Footer,
  },
};
</script>
