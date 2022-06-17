<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import HelloWorld from "./components/HelloWorld.vue";

@Component({
  component: {
    HelloWorld,
  },
})
export default class FirstComponent extends Vue {}

// ↑のVueでエラー出るのなんで・・・？
// Vue Class ComponentとVue Property Decoratorとsetupが出てきてわけわからん最新はどれ？
</script>

<template>
  <h1>Vue 3</h1>
  <img src="@/assets/logo.png" />
  <HelloWorld />
</template>

<style>
#app {
  font-family: Arial, Helvetica, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: darkolivegreen;
  margin-top: 60px;
}
</style>