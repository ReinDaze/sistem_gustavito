<script setup lang="ts">
import HeaderContent from '@/components/HeaderContent.vue'
import FooterContent from '@/components/FooterContent.vue'
import PrivacySection from '@/components/PrivacyPage.vue';

</script>

<template>
  <HeaderContent/>
  <main>
    <PrivacySection/>
    <slot></slot>
  </main>
  <FooterContent/>
</template>
