<script setup>
const props = defineProps({
  userData:String,
});
</script>
<template>
<span class="user">
  <span class="name"> {{ props.userData }}</span>
  <span class="handle">@{{ props.userData }}</span>
</span>
</template>
<style></style>
