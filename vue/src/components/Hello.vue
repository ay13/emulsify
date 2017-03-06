<template>
  <div class="hello">
    <h1 class="heading-1">{{ msg }}</h1>
    <h2 class="heading-2">Essential Links</h2>
    <ul>
      <li class="list-item"><a href="https://vuejs.org" target="_blank">Core Docs</a></li>
      <li class="list-item"><a href="https://forum.vuejs.org" target="_blank">Forum</a></li>
      <li class="list-item"><a href="https://gitter.im/vuejs/vue" target="_blank">Gitter Chat</a></li>
      <li class="list-item"><a href="https://twitter.com/vuejs" target="_blank">Twitter</a></li>
      <br>
      <li class="list-item"><a href="http://vuejs-templates.github.io/webpack/" target="_blank">Docs for This Template</a></li>
    </ul>
    <h2 class="heading-2">Ecosystem</h2>
    <ul>
      <li class="list-item"><a href="http://router.vuejs.org/" target="_blank">vue-router</a></li>
      <li class="list-item"><a href="http://vuex.vuejs.org/" target="_blank">vuex</a></li>
      <li class="list-item"><a href="http://vue-loader.vuejs.org/" target="_blank">vue-loader</a></li>
      <li class="list-item"><a href="https://github.com/vuejs/awesome-vue" target="_blank">awesome-vue</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'hello there',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>
