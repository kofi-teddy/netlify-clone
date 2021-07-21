<template>
  <Header />
  <overlapped-card />
  <col-section />
  <the-footer />
</template>

<script>
import Header from '@/components/Header'
import OverlappedCard from '@/components/OverlappedCard.vue'
import ColSection from '@/components/ColSection.vue'
import TheFooter from '@/components/TheFooter.vue'

export default {
  name: 'App',
  components: {
    Header,
    OverlappedCard,
    ColSection,
    TheFooter
  }
}
</script>

<style>
::-moz-selection {
  color: white;
  background: #1b857b;
}

::selection {
  color: white;
  background: #1b857b;
}
</style>
