<template>
  <header>
      <nav>
          <ul>
              <li><nuxt-link :to="'/'"><img src="/" alt="Profile Image"></nuxt-link></li>
              <li><nuxt-link :to="'/'"><font-awesome-icon :icon="['fas', 'house']" /></nuxt-link></li>
              <li><nuxt-link :to="'/'"><font-awesome-icon :icon="['fas', 'list']" /></nuxt-link></li>
              <li><nuxt-link :to="'/'"><font-awesome-icon :icon="['fas', 'fire']" /></nuxt-link></li>
              <li><nuxt-link :to="'/'"><font-awesome-icon :icon="['fas', 'gear']" /></nuxt-link></li>
          </ul>
      </nav>
      <span class="header__close"><font-awesome-icon :icon="['fas', 'backward-step']" /></span>
  </header>
</template>

<script>
export default {

}
</script>

<style>

</style>