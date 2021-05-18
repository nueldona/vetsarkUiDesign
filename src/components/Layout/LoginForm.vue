<template>
  <main>
    <section class="bg-white pt-10">
      <section class="w-4/5 mx-auto mt-20 mb-44">
        <!-- Lead Text -->
        <div class="space-y-10">
          <h1 class="text-4xl">
            Welcome to <span class="text-lightblue">Vetsark</span>
          </h1>
          <p class="text-lg sm:pr-12">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            eiusmod tempor incididunt ut labore.
          </p>
        </div>

        <!-- Line Tabs -->
        <div class="space-x-6 mt-12">
          <div class="w-32 h-2 bg-lightblue inline-block"></div>
          <div class="w-32 h-2 bg-gray-400 inline-block"></div>
        </div>

        <!-- Form layout -->
        <section class="mt-12">
          <form class="space-y-12">
            <!-- Email -->
            <div class="sm:w-4/5">
              <div class="text-sm text-lightblue -mt-5" v-if="email != ''">
                Email
              </div>
              <input
                type="email"
                class="
                  border-b border-0 border-lightblue
                  px-0
                  py-2
                  w-full
                  focus:outline-none
                "
                placeholder="Email"
                v-model="email"
              />
            </div>

            <!-- Password -->
            <div class="sm:w-4/5 relative">
              <div class="text-sm text-lightblue -mt-5" v-if="Password != ''">
                Password
              </div>
              <input
                type="Password"
                class="
                  border-b border-0 border-lightblue
                  px-0
                  py-2
                  w-full
                  focus:outline-none
                "
                placeholder="Password"
                v-model="Password"
              />
              <div class="absolute right-3 -mt-8 cursor-pointer">
                <EyeIcon width="w-6" height="h-6" />
              </div>
            </div>

            <!-- Submit and Forget button -->
            <div class="flex flex-row justify-between align-middle sm:w-4/5">
              <div>
                <input
                  type="submit"
                  value="Login"
                  class="
                    bg-btn-color
                    hover:bg-btn-color
                    text-lightblue
                    shadow-md
                    rounded
                    px-14
                    py-3
                  "
                />
              </div>

              <p class="text-lightblue text-lg">forgot password?</p>
            </div>
          </form>
        </section>
      </section>
      <section
        class="
          w-full
          wrapper
          flex flex-col
          justify-center
          align-middle
          place-items-center
        "
      >
        <div class="">
          <GoogleSignIn width="w-64" height="h-14" />
        </div>
        <p class="text-lg pt-4 text-gray-600">
          Don’t have an account? <span class="text-lightblue">Create One</span>
        </p>
      </section>
    </section>
  </main>
</template>

<script>
import EyeIcon from "@/components/Icons/EyeIcon";
import GoogleSignIn from "@/components/Icons/GoogleSignIn";
export default {
  data() {
    return {
      email: "",
      Password: "",
    };
  },
  components: {
    EyeIcon,
    GoogleSignIn,
  },
};
</script>

<style lang="scss" scoped>
h1 {
  color: #525d6f;
  font-weight: 700;
}

.wrapper {
  background: #f4f5f7;
  height: 14.4rem;
}
</style>
