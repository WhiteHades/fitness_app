<script setup>
import Welcome from "./components/pages/Welcome.vue";
import Layout from "./components/pages/layouts/Layout.vue";
import Dashboard from "./components/pages/Dashboard.vue";
</script>

<template>
  <Layout>
    <Dashboard />
    <Welcome />
  </Layout>
</template>

<style scoped></style>
