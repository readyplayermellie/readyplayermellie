<template>
  <div class="bg-gradient-to-r from-blue-950 via-indigo-500 to-pink-500">
    <TopNav />
    <div class="pb-9 pt-9 h-screen v-screen content">
      <div class="flex justify-around items-center h-full mx-9">
        <NuxtPage class="mx-11 max-w-screen-md mx-9"/>
        <AppNav />
      </div>
    </div>
    <AppFooter />
  </div>
</template>

<script>
</script>

<style scoped>
.content {
    margin-top: -36px;
}
</style>