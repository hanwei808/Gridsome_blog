<template>
  <div class="layout">
    <header class="header sticky" data-v-7e33895e="">
      <div class="container" data-v-7e33895e="">
        <div class="left" data-v-7e33895e="">
          <a
            href="/"
            aria-current="page"
            class="home-link active--exact active"
            data-v-7e33895e=""
            ><img
              src="/img/logo.332701b7.svg"
              alt="Nichlas W. Andersen"
              class="logo"
              data-v-7e33895e=""
          /></a>
        </div>
        <nav class="nav right" data-v-7e33895e="">
          <a href="/journal" class="nav__link" data-v-7e33895e="">Journal</a
          ><a href="/contact" class="nav__link" data-v-7e33895e="">Say Hi!</a>
        </nav>
      </div>
    </header>
    <slot />
    <footer class="footer" data-v-07acb5f8="">
      <div class="container" data-v-07acb5f8="">
        <span data-v-07acb5f8="">Copyright © 2021</span>
      </div>
    </footer>
  </div>
</template>

<static-query>
query {
  metadata {
    siteName
  }
}
</static-query>

<style scoped>
@import "index.css";
</style>
