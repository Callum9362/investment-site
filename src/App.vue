<template>
  <div id="app">
    <Title />
    <Nav />
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
import Title from './components/Title.vue'
import Nav from './components/Nav.vue'
import MarketSummary from './components/MarketSummary.vue'
import CryptoSearch from './components/CryptoSearch.vue'
import QuickQuote from './components/QuickQuote.vue'
import FinanceNews from './components/FinanceNews.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: { Title, Nav, MarketSummary, CryptoSearch, QuickQuote,FinanceNews, Footer}
}
</script>

<style>
</style>
