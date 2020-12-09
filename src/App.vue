<template>
  <div id="app">
    <Nav />
    <Menu />
    <MarketSummary />
  </div>
</template>

<script>
import Nav from './components/Nav.vue'
import Menu from './components/Menu.vue'
import MarketSummary from './components/MarketSummary.vue'

export default {
  name: 'App',
  components: { Nav, Menu, MarketSummary}
}
</script>

<style>
</style>
