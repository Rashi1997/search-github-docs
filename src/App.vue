<template>
  <div>
    <Introduction id="home"/>
    <Usability id="usability" />
    <Deploy id ="deploy"/>
  </div>
</template>

<script>
import Introduction from './components/Introduction.vue'
import Usability from './components/Usability.vue'
import Deploy from './components/Deploy.vue'
export default {
  name: 'App',
  components: {
    Introduction,
    Usability,
    Deploy
  }
}
</script>

<style>
</style>