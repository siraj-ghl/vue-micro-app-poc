<template>
<p> I am a paragraph coming from V3 </p>
</template>

<script>

export default {
  methods: {
    click() {
      this.$emit("btnClick");
      this.$emit("onBtnClick");
    }
  }
} 
</script>

