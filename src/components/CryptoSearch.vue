<template>
  <section class="cryptoSearch">
    <div class="container">
      <div class="input-group">
        <span class="input-group-btn">
          <button class="btn btn-success" type="button">Go!</button>
        </span>
        <input
          type="text"
          class="form-control"
          aria-label="..."
          placeholder="CRYPTO SEARCH"
        />
        <div class="input-group-btn"></div>
      </div>
    </div>
    <br />
    <div class="container">
      <a class="link text-center" href="">Free Real-Time Crypto Prices</a>
    </div>
    <br />

    <div  class="container currency" >
          <div v-for="currency in info" :key="currency.id" class="list-group currency">
            <a href="#" class="list-group-item disabled">Bitcoin: {{currency.rate_float | currencydecimal}} {{currency.code}}</a>
          </div>
    </div>
  </section>
</template>

<script>

const axios = require('axios');

export default {
  name: "CryptoSearch",
  components: {},
  data () {
    return {
      info: null
    }
  },
  mounted(){

     axios
      .get('https://api.coindesk.com/v1/bpi/currentprice.json')
      .then(response => (this.info = response.data.bpi))
      .catch(error => console.log(error))

  },
  filters: {
  currencydecimal (value) {
    return value.toFixed(2)
  }
},
};
</script>

<style>
.cryptoSearch {
  padding-top: 45px;
}

.link {
  color: black;
  padding-top: 10px;
  padding-bottom: 10px;
}
</style>
