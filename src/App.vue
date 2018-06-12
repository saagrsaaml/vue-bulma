<template>
  <div id="app">
    <!--<router-view/>-->
    <nav-bar/>
    <side-bar></side-bar>
    <nav-bar :isFixedBottom="true"></nav-bar>
  </div>
</template>

<script>
import NavBar from '@/components/NavBar'
import SideBar from '@/components/SideBar'
export default {
  name: 'App',
  components: { NavBar, SideBar }
}
</script>

<style>
</style>
