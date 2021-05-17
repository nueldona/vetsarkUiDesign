<template>
  <div class="grid grid-cols-2">
    <Hero class="" />
    <Form />
  </div>
</template>

<script>
import Hero from "@/components/Layout/Hero.vue";
import Form from "@/components/Layout/Form.vue";
export default {
  components: {
    Hero,
    Form
  },
};
</script>

<style lang="scss" scoped>

</style>