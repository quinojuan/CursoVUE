<script lang="ts">
import { defineComponent, ref, Ref } from "vue";
export default defineComponent({
  name: "CounterComposition",
  setup() {
    let counter:Ref = ref(0);
    const addCounter = ():void => {
      counter.value++;
    };
    return { counter, addCounter };
  },
});
</script>

<template>
  <h3>{{ counter }}</h3>
  <button @click="addCounter">ADD</button>
</template>
