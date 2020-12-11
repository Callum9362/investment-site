<template>
  <section class="menus">
    <nav class="navbar navbar-expand-lg navbar-light bg-white justify-content-center align-items-center">
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse position-absolute" id="navbarSupportedContent">
        <ul class="navbar-nav mr-auto">
          <li class="nav-item active">
            <a class="nav-link" href="#"
              >Home <span class="sr-only">(current)</span></a
            >
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Upgrade</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Messages</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Plus 1</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Crypto</a>
          </li>
          <li class="nav-item dropdown">
            <a
              class="nav-link dropdown-toggle"
              href="#"
              id="navbarDropdown"
              role="button"
              data-toggle="dropdown"
              aria-haspopup="true"
              aria-expanded="false"
            >
              Most Popular
            </a>
            <div class="dropdown-menu" aria-labelledby="navbarDropdown">
              <a class="dropdown-item" href="#">Monitor</a>
              <div class="dropdown-divider"></div>
              <a class="dropdown-item" href="#">Quote</a>
              <div class="dropdown-divider"></div>
              <a class="dropdown-item" href="#">Charts</a>
            </div>
          </li>
          <li class="nav-item dropdown">
            <a
              class="nav-link dropdown-toggle"
              href="#"
              id="navbarDropdown"
              role="button"
              data-toggle="dropdown"
              aria-haspopup="true"
              aria-expanded="false"
            >
              SiteMap
            </a>
            <div class="dropdown-menu" aria-labelledby="navbarDropdown">
              <a class="dropdown-item" href="#">Alerts</a>
              <div class="dropdown-divider"></div>
              <a class="dropdown-item" href="#">Charts</a>
              <div class="dropdown-divider"></div>
              <a class="dropdown-item" href="#">Charts</a>
              <div class="dropdown-divider"></div>
              <a class="dropdown-item" href="#">Desktop</a>
              <div class="dropdown-divider"></div>
              <a class="dropdown-item" href="#">Forum</a>
              <div class="dropdown-divider"></div>
              <a class="dropdown-item" href="#">Financials</a>
              <div class="dropdown-divider"></div>
              <a class="dropdown-item" href="#">Monitor</a>
              <div class="dropdown-divider"></div>
              <a class="dropdown-item" href="#">News</a>
              <div class="dropdown-divider"></div>
              <a class="dropdown-item" href="#">Portfolio</a>
            </div>
          </li>
          <li class="nav-item dropdown">
            <a
              class="nav-link dropdown-toggle"
              href="#"
              id="navbarDropdown"
              role="button"
              data-toggle="dropdown"
              aria-haspopup="true"
              aria-expanded="false"
            >
              Forex / Futures
            </a>
            <div class="dropdown-menu" aria-labelledby="navbarDropdown">
              <a class="dropdown-item" href="#">Forex</a>
              <div class="dropdown-divider"></div>
              <a class="dropdown-item" href="#">Future and Options</a>
              <div class="dropdown-divider"></div>
              <a class="dropdown-item" href="#">Commodities</a>
            </div>
          </li>
          <li class="nav-item dropdown">
            <a
              class="nav-link dropdown-toggle"
              href="#"
              id="navbarDropdown"
              role="button"
              data-toggle="dropdown"
              aria-haspopup="true"
              aria-expanded="false"
            >
              World Exchanges
            </a>
            <div class="dropdown-menu" aria-labelledby="navbarDropdown">
              <a class="dropdown-item" href="#">United States of America</a>
              <div class="dropdown-divider"></div>
              <a class="dropdown-item" href="#">United Kingdom</a>
              <div class="dropdown-divider"></div>
              <a class="dropdown-item" href="#">Australia</a>
              <div class="dropdown-divider"></div>
              <a class="dropdown-item" href="#">China</a>
            </div>
          </li>
        </ul>
      </div>
    </nav>
  </section>
</template>

<script>
export default {
  name: "Nav",
  components: {},
};
</script>

<style>


</style>