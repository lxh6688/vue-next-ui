<template>
  <div>导航栏 | <router-link to="/">Test1</router-link> | <router-link to="/xxx">Test2</router-link></div>
  <hr>
  <router-view />
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
}
</script>
