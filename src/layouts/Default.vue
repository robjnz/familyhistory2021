<template>
  <div class="layout">
    <TheHeader/>
    
    <slot/>
    <TheFooter/>
  </div>
</template>

<static-query>
query {
  metadata {
    siteName
  }
}
</static-query>

<style>



</style>

<script>
import TheHeader from '@/components/TheHeader/TheHeader'
import TheFooter from '@/components/TheFooter/TheFooter'



export default {
  
  components: {
    TheHeader,
    TheFooter,
  }
}
</script>

