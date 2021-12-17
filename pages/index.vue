<template>
  <div>
    <div>Welcome, you are logged in!</div>
    <br />

    <div><b>Token:</b></div>
    <pre v-text="$auth.strategy.token.get()" />

    <div><b>Refresh Token:</b></div>
    <pre v-text="$auth.strategy.refreshToken.get()" />
  </div>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>
