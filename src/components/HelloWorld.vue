<script setup lang ='ts'>
import { ref, reactive } from "vue";
const refNumber = ref(0);
const reactiveNumber = reactive({ num: 0 });
</script>

<template>
  <h3>The First Component</h3>
  <!-- ここを<h3 />と記述することはOK？ -->
  <p>Ref Count:{{ refNumber }}</p>
  <p>Reactive Count:{{ reactiveNumber.num }}</p>
</template>