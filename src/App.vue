<template>
  <div id="app">
    <Nav />
    <Menu />
    <MarketSummary />
    <div class="container">
      <div class="row">
        <div class="col-md"> 
          <CryptoSearch />
        </div>
        <div class="col-md">
          <FinanceNews />
        </div>
        <div class="col-md">
          <QuickQuote />
        </div>
      </div>
    </div>
    <br>
    <Footer />
  </div>
</template>

<script>
import Nav from './components/Nav.vue'
import Menu from './components/Menu.vue'
import MarketSummary from './components/MarketSummary.vue'
import CryptoSearch from './components/CryptoSearch.vue'
import QuickQuote from './components/QuickQuote.vue'
import FinanceNews from './components/FinanceNews.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: { Nav, Menu, MarketSummary, CryptoSearch, QuickQuote,FinanceNews, Footer}
}
</script>

<style>
</style>
