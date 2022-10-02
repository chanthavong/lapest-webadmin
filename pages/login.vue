<template>
  <div
    class="bg-no-repeat bg-cover bg-center relative"
    style="
      background-image: url(https://images.unsplash.com/photo-1481833761820-0509d3217039?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1740&q=80);
    "
  >
    <div
      class="absolute bg-gradient-to-b from-yellow-50 to-yellow-50 opacity-20 inset-0 z-0"
    />

    <div
      class="min-h-screen grid grid-cols-1 md:grid-cols-2 justify-center items-center"
    >
      <div class="justify-center flex items-center z-50">
        <div class="flex-col text-white justify-center items-center">
          <div class="flex justify-center">
            <img src="logo.png" class="mb-3 h-40 w-40">
          </div>
          <h1 class="mb-3 font-bold text-xl">
            Hi ? Welcome Back
          </h1>
          <p class="pr-3">
            Lapest Enterprises , Cafe, Destination And restaurant
          </p>
        </div>
      </div>
      <div class="w-full flex items-center justify-center">
        <div class="w-full px-8">
          <div
            class="backdrop-blur-2xl max-w-xl bg-white/90 p-12 rounded-2xl flex flex-col w-full gap-y-4"
          >
            <div class="flex flex-col items-center gap-2 text-2xl mb-8">
              <span>Sign In Your Account</span>
              <span class="text-sm text-gray-400 font-light">Access to web admin monitor.</span>
            </div>
            <div class="flex flex-col gap-4">
              <div class="flex flex-col gap-2">
                <span class="text-sm">Your Email</span>
                <input
                  placeholder="mail@gmail.com"
                  class="border p-2 rounded-xl"
                >
              </div>
              <div class="flex flex-col gap-2">
                <span class="text-sm">Password</span>
                <input
                  type="password"
                  show-password-on="mousedown"
                  placeholder="Password"
                  :maxlength="150"
                  class="border p-2 rounded-xl"
                >
              </div>
            </div>
            <button class="border p-2 rounded-xl bg-yellow-500 text-white">
              <span>Sign In</span>
            </button>
            <p class="flex gap-2 items-center">
              <button text>
                ພາສາລາວ
              </button>
              <span class="text-gray-500">|</span>
              <button text>
                English
              </button>
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">
definePageMeta({
  layout: 'blank'
})
</script>

<style>
.textGrd {
  font-size: 72px;
  background: linear-gradient(45deg, #274185, #159af2);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}
</style>
