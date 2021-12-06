<template>
  <!-- Design inspired from https://www.hotjar.com/ -->
  <div class="jumbotron">
    <div class="container text-center text-lg-left">
      <div class="row">
        <div class="col-lg-8">
          <h1 class="display-4">
            Welcome to our
            <span class="highlight-word">home page</span>
          </h1>
          <p class="lead">
            This is a simple home unit page, feel free to register or login at
            anytime of the day. Join us!
          </p>
          <span class="text-center d-inline-block">
            <a class="btn btn-success btn-lg w-100" href="#" role="button"
              >Continue</a
            >
          </span>
        </div>
        <div class="col-lg-4 align-items-center d-flex">
          <img
            src="https://wallpaperaccess.com/full/1940064.jpg"
            alt=""
            class="img-fluid"
          />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "Home",
  components: {
    HelloWorld,
  },
};
</script>

<style scoped></style>
