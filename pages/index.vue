<template>
  <Layout>
    main
    <Element></Element>
    <NuxtLink to="/parent">parent</NuxtLink>
    <br />
    <NuxtLink to="/user">user</NuxtLink>
    <br />
    <NuxtLink to="/paren2t">paren2t</NuxtLink>
  </Layout>
</template>

<script setup lang="ts">
import Element from "@/components/Element.vue";
</script>

<style lang="scss" scoped></style>
