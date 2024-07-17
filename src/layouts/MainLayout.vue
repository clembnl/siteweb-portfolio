<template>
  <q-layout view="hHh Lpr fFf" class="q-ma-xl">
    <q-page-container>
      <router-view />
    </q-page-container>
  </q-layout>
</template>

<script setup>
  defineOptions({
    name: 'MainLayout'
  })
</script>
