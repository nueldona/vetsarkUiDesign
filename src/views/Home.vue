<template>
  <div class="w-100 h-100 grid md:grid-cols-2">
    <Hero />
    <LoginForm />
  </div>
</template>

<script>
import LoginForm from "@/components/Layout/LoginForm.vue";
import Hero from "@/components/Layout/Hero.vue";
export default {
  components: {
    Hero,
    LoginForm,
  },
};
</script>

<style lang="scss" scoped>

</style>