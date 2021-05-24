<template>
  <div>导航栏 | <router-link to="/">frank</router-link></div>

  <router-view/>
</template>

<script>
import Frank from './components/Frank.vue'

export default {
  name: 'App',
  components: {
    Frank
  }
}
</script>
