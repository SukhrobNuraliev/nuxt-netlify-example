<template>
  <div class="container font-sans text-black">
    <div>
      <div class="flex justify-between items-center">
        <h1 class="pt-8 mb-8 text-2xl">
          <nuxt-link to="/" class="no-underline text-black hover:text-grey-darkest"
            >My Awesome Blog</nuxt-link
          >
        </h1>
        <div class="flex">
          <div class="mr-6">
            <nuxt-link to="/about" class="nav text-black no-underline">About</nuxt-link>
          </div>
          <div>
            <nuxt-link to="/team" class="nav text-black no-underline">Team</nuxt-link>
          </div>
          <div>
            <nuxt-link to="/salam" class="nav text-black no-underline">Salam</nuxt-link>
          </div>
        </div>
      </div>
      <div class="border-b border-solid border-grey mb-8"></div>
    </div>

    <Nuxt />
  </div>
</template>

<style>
 
</style>
