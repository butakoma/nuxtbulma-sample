<template>
  <section>
    <div class="hero is-info">
    <div>
      <h1 class="title">
        nuxtbulma-sample
      </h1>
    </div>
    <nav class="navbar">
      <div class="container">
        <div class="navbar-menu">
          <div class="navbar-start">
            <div class="navbar-item">
              <nuxt-link to="/">
              Home
              </nuxt-link>
            </div>
            <div class="navbar-item">
              <nuxt-link to="/about">
              About
              </nuxt-link>
            </div>
          </div>
        </div>
      </div>
    </nav>
    </div>
    <div>
      <nuxt />
    </div>
  </section>
</template>

<style>
html {
  font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

</style>
