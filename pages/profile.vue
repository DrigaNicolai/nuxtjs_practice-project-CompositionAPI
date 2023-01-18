<template>
  <p>Welcome User</p>
</template>

<script setup>
definePageMeta({
  layout: "sidebar",
  middleware: ["auth"],
});
</script>
