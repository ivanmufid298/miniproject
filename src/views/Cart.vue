<template>
  <div class="home">
    <Navbar />
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from "@/components/Navbar.vue";
import Footer from "@/components/Footer.vue";
export default {
  name: "Cart",
  components: {
    Navbar,
    Footer,
  },
};
</script>
