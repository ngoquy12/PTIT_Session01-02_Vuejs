<script setup>
// import FooterComponent from "./components/FooterComponent.vue";

import Header from "./components/Header.vue";
import FooterComponent from "./components/FooterComponent.vue";
import User from "./components/User.vue";
import Modal from "./components/Modal.vue";
</script>

<template>
  <div>
    <h1>Hello world</h1>

    <Header></Header>

    <!-- <Header /> -->

    <User />

    <footer-component></footer-component>

    <!-- Modal -->
    <Modal />
  </div>
</template>
