<script setup lang="ts">
const { t } = useI18n()
</script>

<template>
  <div>
    <Header/>
    <p>GOMES {{ t('intro.desc') }}</p>
  </div>
</template>

<route lang="yaml">
meta:
  layout: home
</route>
