<script setup lang="ts">
import HeaderContent from '@/components/HeaderContent.vue'
import FooterContent from '@/components/FooterContent.vue'
import TengahContent from '@/components/TengahContent.vue'



</script>

<template>
  <HeaderContent/>
  <main>
    <TengahContent/>
    <slot></slot>
  </main>
  <FooterContent/>
</template>
