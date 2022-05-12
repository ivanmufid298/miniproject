<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-6">
        <h1><strong>Electro</strong></h1>
        <h3>In your Age</h3>
        <p>Choose your powerfull device</p>
        <button class="btn btn-info">
          <router-link style="text-decoration: none; color: white" to="/product"
            >Shop Now</router-link
          >
        </button>
      </div>
      <div class="col-6">
        <img
          class="img-fluid"
          src="https://cdn.dribbble.com/users/101577/screenshots/8071324/media/849d4f53355557312134e05c5acbdcec.png?compress=1&resize=400x300"
        />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Banner",
};
</script>

<style></style>
