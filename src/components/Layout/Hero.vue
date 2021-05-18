<template>
  <section
    class="
      relative
      w-100
      bg-gradient-to-b bg-bg-darkblue
      to-black
      from-bg-darkblue
      wrapper
    "
  >
    <!-- SvG icons -->
    <div class="absolute right-0 -mt-14 mr-8">
      <LgDarkCircle name="LgDarkCircle" width="w-56" height="h-56" />
    </div>

    <!-- SvG icons -->
    <div class="absolute mt-9 -ml-4">
      <XmGrayCircle
        name="XmGrayCircle"
        width="w-14"
        height="h-14"
      ></XmGrayCircle>
    </div>

    <!-- Lead Text -->
    <div class="mb-6 sm:mb-10 mt-20 -space-y-1 w-4/5 mx-auto">
      <h1 class="text-5xl text-white opacity-30 pb-4">Next</h1>
      <h1 class="text-5xl text-white leading-tight">
        Revolution <br />
        in Sales
      </h1>
    </div>

    <!-- Subordinate Text -->
    <div
      class="w-4/5 mx-auto space-x-4 sm:space-x-8 text-lightblue font-semibold"
    >
      <div class="inline-block sm:text-base text-sm">INVENTORY</div>
      <div class="inline-block sm:text-base text-sm">ORDER TRACKING</div>
      <div class="inline-block sm:text-base text-sm">DEBT MANAGEMENT</div>
    </div>

    <!-- SvG icons -->
    <div class="absolute mt-32 left-1/4">
      <SmBlueCircle name="SmBlueCircle" width="w-8" height="h-8"></SmBlueCircle>
    </div>

    <!-- SvG icons -->
    <div class="absolute -ml-10 mt-60">
      <LfDarkCircle
        name="LfDarkCircle"
        width="w-56"
        height="h-56"
      ></LfDarkCircle>
    </div>

    <!-- SvG icons -->
    <div class="absolute right-1/4 top-2/4 mt-44 -mr-5">
      <SmBlueCircle name="SmBlueCircle" width="w-5" height="h-5"></SmBlueCircle>
    </div>

    <!-- SvG icons -->
    <div class="absolute right-1/4 top-2/4 mt-14">
      <XmLightGray
        name="XmLightGray"
        :width="'w-4'"
        :height="'h-4'"
      ></XmLightGray>
    </div>

    <!-- SvG icons -->
    <div class="absolute right-1/4 top-2/4 mt-28 -mr-10">
      <GreenCircle name="GreenCircle" width="w-5" height="h-5"></GreenCircle>
    </div>

    <!-- SvG icons -->
    <div class="absolute right-1/4 top-2/4 mt-24 -mr-28">
      <WhiteCircle name="WhiteCircle" width="w-5" height="h-5"></WhiteCircle>
    </div>

    <!-- SvG icons -->
    <div class="absolute right-1/4 top-2/4 mt-60 -mr-2">
      <XmLightGray
        name="XmLightGray"
        :width="'w-16'"
        :height="'h-16'"
      ></XmLightGray>
    </div>

    <!-- SvG icons -->
    <div class="absolute bottom-12 left-14">
      <BrandLogo width="w-32" height="h-7"></BrandLogo>
    </div>
  </section>
</template>

<script>
import LgDarkCircle from "@/components/Icons/LgDarkCircle.vue";
import XmGrayCircle from "@/components/Icons/XmGrayCircle.vue";
import SmBlueCircle from "@/components/Icons/SmBlueCircle.vue";
import LfDarkCircle from "@/components/Icons/LfDarkCircle.vue";
import XmLightGray from "@/components/Icons/XmLightGray";
import GreenCircle from "@/components/Icons/GreenCircle";
import WhiteCircle from "@/components/Icons/WhiteCircle";
import BrandLogo from "@/components/Icons/BrandLogo";
export default {
  components: {
    LgDarkCircle,
    XmGrayCircle,
    SmBlueCircle,
    LfDarkCircle,
    XmLightGray,
    GreenCircle,
    WhiteCircle,
    BrandLogo,
  },
};
</script>

<style lang="scss" scoped>
.wrapper {
  height: 63rem;
}

h1 {
  font-weight: 700;
}
</style>
