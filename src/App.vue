<template>
  <div id="app">
    <header class="white-80 tc pv4 avenir">
      <h1 class="mt2 mb0 baskerville i fw1 f1">Crypto Center</h1>
      <h2 class="mt2 mb0 f6 fw4 ttu tracked">the goto place for learning about crypto currency</h2>
      <nav class="bt bb tc mw7 center mt4">
        <router-link class="f6 f5-l link bg-animate white-80 hover-bg-white hover-black-80 dib pa3 ph4-l" to="/">Home</router-link>
        <router-link class="f6 f5-l link bg-animate white-80 hover-bg-white hover-black-80 dib pa3 ph4-l" to="/about">About</router-link>
        <router-link class="f6 f5-l link bg-animate white-80 hover-bg-white hover-black-80 dib pa3 ph4-l" to="/coins/ethereum">Ethereum</router-link>
        <router-link class="f6 f5-l link bg-animate white-80 hover-bg-white hover-black-80 dib pa3 ph4-l" to="/coins/bitcoin">Bitcoin</router-link>
      </nav>
    </header>
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>
