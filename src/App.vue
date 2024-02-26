<template>
  <el-container>
    <el-header>
      <Header />
    </el-header>

    <el-main>
      <Main />
    </el-main>

    <el-footer>
      <Footer />
    </el-footer>
  </el-container>
</template>

<script setup>
  import Header from '@/layouts/Header.vue'
  import Main from '@/pages/main/Main.vue'
  import Footer from '@/layouts/Footer.vue'
</script>

<style scoped>

</style>
