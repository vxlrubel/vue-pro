<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header class="clearfix">
    <div class="container-xl">
      <div class="row align-items-center">
        <div class="col-4">
          <RouterLink to="/" class="text-decoration-none">
            <img
              src="https://img.freepik.com/free-vector/flat-design-ac-logo-design_23-2149482027.jpg?t=st=1726338524~exp=1726342124~hmac=b5ae64a9eb04ec45e10fd98b1eae3954f70d101f17011315a798ea45881bffcf&w=740"
              alt="logo image"
              class="w-auto"
              loading="lazy"
              height="100"
            />
          </RouterLink>
        </div>
        <div class="col-8">
          <ul class="list-unstyled m-0 p-0 d-flex gap-3">
            <li><RouterLink to="/" class="text-decoration-none">Home</RouterLink></li>
            <li>
              <RouterLink to="/about" class="text-decoration-none">About</RouterLink>
            </li>
            <li>
              <RouterLink to="/services" class="text-decoration-none">Services</RouterLink>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </header>
  <RouterView />
</template>

<style lang="scss" scoped></style>
