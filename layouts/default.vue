<template>
  <div>
    <Header />
    <Sidebar />
    <Nuxt />
    <Footer />
  </div>
</template>

<script>
export default {
  layout: (ctx) => ctx.isMobile? 'mobile':'default',
}
</script>