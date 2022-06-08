<template>
  <div>
    <h3>Standalone Vue3 App</h3>
    <Paragraph />
    <RemoteWidget />
  </div>
</template>

<script>
import { ref } from "vue";
import Paragraph from "./components/Paragraph";
import RemoteWidget from "./components/RemoteWidget";

export default {
  components: {
    Paragraph,
    RemoteWidget
  },
  setup() {
    const count = ref(0);
    const inc = () => {
      count.value++;
    };

    return {
      count,
      inc,
    };
  },
};
</script>

<style scoped>
h1 {
  font-family: Arial, Helvetica, sans-serif;
}
</style>
