<template>
  <section>
    <!-- Second layout Icon -->
    <svg
      class="fill-current"
      v-if="name === 'XmGrayCircle'"
      :class="[width, height]"
      viewBox="0 0 32 59"
      fill="none"
      xmlns="http://www.w3.org/2000/svg"
    >
      <circle opacity="0.1" cx="2.5" cy="29.5" r="29.5" fill="white" />
    </svg>
  </section>
</template>

<script>
export default {
  props: {
    width: {
      type: String,
      required: true,
    },
    height: {
      type: String,
      required: true,
    },
    name: {
      type: String,
      required: true,
    }
  },
};
</script>

<style></style>

