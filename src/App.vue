<template>
  <div id="app">
    <!--<router-view/>-->
    <nav-bar/>
    <nav-bar :isFixedBottom="true"></nav-bar>
  </div>
</template>

<script>
import NavBar from '@/components/NavBar'
export default {
  name: 'App',
  components: { NavBar }
}
</script>

<style>
</style>
