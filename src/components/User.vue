<script setup>
const props = defineProps({
  userData: String,
});
</script>
<template>
  <span class="user">
    <span class="name">{{ props.userData.name }}</span>
    <span class="handle">@{{ props.userData.handle }}</span>
  </span>
</template>
<style></style>
