<template>
  <section>
    <!-- First layout Icon -->
    <svg
      v-if="name === 'LgDarkCircle'"
      class="fill-current"
      :class="[width, height]"
      viewBox="0 0 234 152"
      fill="none"
      xmlns="http://www.w3.org/2000/svg"
    >
      <circle opacity="0.4" cx="117" cy="35" r="117" fill="black" />
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
