<template>
  <Switch @isActive="handleIsActive" />
  <Content :status="status" />
  <Swiper />
</template>

<script setup>
import { ref } from "vue";
import Switch from "./Switch.vue";
import Content from "./Content.vue";
import Swiper from "./Swiper.vue";

// Make `status` reactive with ref
const status = ref("builders");

// Function to update the status
const handleIsActive = (value) => {
  status.value = value; // Update the ref's value
};
</script>

<style lang="scss" scoped></style>
