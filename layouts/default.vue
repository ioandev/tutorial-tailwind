<template>
  <div>
    <aside class="bg-green-300 text-white py-1 text-center text-sm font-semibold">
      <p class="inline-block">We are updating our site. If you find a bug hit us on our discord channel</p>
      <button class="inline-block bg-green-500 p-1 text-xs rounded">chat with us</button>
    </aside>
    <header class="px-8 py-4">
      <div id="logo-container" class="inline-block">

      </div>
      <nav class="inline-block">
        <ul>
          <li>How it works</li>
          <li>Themes</li>
          <li>Blog</li>
          <li>Guide
            <ul class="hidden">
              <li>Page 1</li>
              <li>Page 2</li>
              <li>Page 3</li>
            </ul>
          </li>
          <li class="search-icon">Search</li>
          <li class="basket-icon">Basket</li>
          <li class="tryfree-button">Try Free</li>
          <li class="signin-button">Sign in</li>
        </ul>
      </nav>
    </header>
    <nuxt />
  </div>
</template>

<style>
html {
  font-family: 'Open Sans', 'Montserrat', 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
  Roboto, 'Helvetica Neue', Arial, sans-serif;
}

#logo-container {
  background: url("../assets/img/logo.png") no-repeat 0px 0px;
  width: 185px;
  height: 35px;
}

ul li {
  display: inline-block;
}

</style>
