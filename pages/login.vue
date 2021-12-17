<template>
  <div>Loading...</div>
</template>

<script lang="ts">
export default {
  name: 'LoginPage',
  mounted() {
    this.$auth.loginWith('azure_b2c');
  },
  auth: 'guest'
}
</script>

<style scoped>

</style>
