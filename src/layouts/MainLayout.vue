<script setup lang="ts">
import HeaderContent from '@/components/HeaderContent.vue'
import FooterContent from '@/components/FooterContent.vue'
import TengahContent from '@/components/HomePage.vue'



</script>

<template>
  <HeaderContent/>
  <main>
    <TengahContent/>
    <slot></slot>
  </main>
  <FooterContent/>
</template>
