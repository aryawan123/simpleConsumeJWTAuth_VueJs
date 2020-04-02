<template>
  <div id="app">
    <TheNavigation/>
    <router-view/>
  </div>
</template>


<script>
import TheNavigation from '@/components/TheNavigations'
export default {
  components: {
    TheNavigation
  }
}
</script>