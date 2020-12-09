<template>
  <section class="marketSummary text-center">
    <div class="container">
      <h3 class="sumTitle">Market Summary</h3>
       <div class="container">
         <div class="row">
           <div class="col-sm">
             <h6>ASX Status</h6>
             <p class="green">Market Open</p>
           </div>
           <div class="col-sm">
             <h6>Australian SE All Ordinaries Index</h6>
             <p class="green">+0.71% 6,971.50</p>
           </div>
           <div class="col-sm">
             <h6>SP ASX 200 Index</h6>
             <p class="green">+0.73% 6,736.70</p>
           </div>
         </div>
       </div>
       <div class="container">
         <div class="row">
           <div class="col-sm">
              <a class="other-market" href="">Dow Jones</a>
           </div>
           <div class="col-sm">
             <a class="other-market" href="">ASX</a>
           </div>
           <div class="col-sm">
             <a class="other-market" href="">ASX200</a>
           </div>
           <div class="col-sm">
             <a  class="other-market" href="">Forex</a>
           </div>
           <div class="col-sm">
             <a class="other-market" href="">Level 2</a>
           </div>
         </div>
       </div>
    </div>
  </section>
</template>

<script>

export default {
  name: 'MarketSummary',
  components: {
  }
}
</script>

<style>
  .marketSummary{
    padding-top: 45px;
  }

  .sumTitle{
    padding-bottom: 10px;
  }

  .green{
    color: green;
  }

  .other-market{
    color: black;
  }
</style>