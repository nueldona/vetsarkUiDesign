<template>
  <section class="py-28 px-32">
    <div>
      <h1 class="">Welcome to <span>Vetsark</span></h1>
      <p class="mt-5">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore.</p>
    </div>
    <div class="flex flex-row mt-10">
      <div class="tab-1 mr-4"></div>
      <div class="tab-2"></div>
    </div>
    <form action="" class="my-8 space-y-4">
      <div>
        <label></label>
        <input
          type="text"
          name=""
          id=""
          placeholder="Enter Name"
          class="
            px-4
            py-2
            w-full
            border
            focus:border-primary
            focus:outline-none
            rounded
            bg-gray-200
          "
          required
        />
        <!-- <span class="text-red-600 text-sm">error massage</span> -->
      </div>
      <div>
        <label></label>
        <input
          type="email"
          name=""
          id=""
          placeholder="Enter Email"
          class="
            px-4
            py-2
            w-full
            border
            focus:border-primary
            focus:outline-none
            rounded
            bg-gray-200
          "
          required
        />
      </div>
    </form>
  </section>
</template>

<script>

</script>

<style lang="scss" scoped>
h1 {
  color: #525D6F;
  font-weight: bold;
  font-size: 36px;
  line-height: 54px;
  span {
    color: #4385F5;
  }
}

p {
  font-weight: normal;
  font-size: 18px;
  line-height: 27px;
  color: #525D6F;
}

.tab-1 {
  width: 138px;
  height: 6px;
  background: #4385F5;
}

.tab-2 {
  width: 138px;
  height: 6px;
  background: #C4C4C4;
}
</style>