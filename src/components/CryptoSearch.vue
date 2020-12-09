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

    <div class="container">
          <div class="list-group">
            <a href="#" class="list-group-item disabled">BitCoin1 </a>
            <a href="#" class="list-group-item disabled">BitCoin1</a>
            <a href="#" class="list-group-item disabled">BitCoin1</a>
            <a href="#" class="list-group-item disabled">BitCoin1</a>
            <a href="#" class="list-group-item disabled">BitCoin1</a>
            <a href="#" class="list-group-item disabled">BitCoin1</a>
            <a href="#" class="list-group-item disabled">BitCoin1</a>
            <a href="#" class="list-group-item disabled">BitCoin1</a>
            <a href="#" class="list-group-item disabled">BitCoin1</a>
            <a href="#" class="list-group-item disabled">BitCoin1</a>
          </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "CryptoSearch",
  components: {},
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
