<template>
  <div>
    <BaseHero />
    <TextBlock />
    <WinPage  />
  </div>
</template>
  
<script>
import BaseHero from '@/components/BaseHero.vue';
import TextBlock from '@/components/TextBlock.vue';
import WinPage from './WinPage.vue';

export default {
  name: 'MainPage',
  components: {
    BaseHero,
    TextBlock,
    WinPage
  },
}
</script>
  