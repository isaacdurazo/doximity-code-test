<script setup>
import WelcomeItem from './WelcomeItem.vue'

import LeftSidebar from './LeftSidebar.vue'
import Cards from './Cards.vue'
import RightSidebar from './RightSidebar.vue'
</script>

<template>
  <LeftSidebar/>
  
  <Cards/>

  <RightSidebar/>

  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Documentation</template>

    Vue’s
    <a href="https://vuejs.org/" target="_blank" rel="noopener">official documentation</a>
    provides you with all information you need to get started.
  </WelcomeItem>

</template>
