<template>
  <div>
    <header>
      <nuxt-link to="/">
        <img src="../assets/images/logo/logo.png" width="120" height="50" onclick="window.scrollTo(0,0);" />
      </nuxt-link>
    </header>
  </div>
</template>

<script>
export default {
  name: 'heading',
}
</script>

<style scoped>
header {
  position: fixed;
  padding: 1rem;
  display: flex;
  align-items: right;
  top: 0;
  right: 0;
}
</style>