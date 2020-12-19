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
        </div>
      </div>
      <div class="border-b border-solid border-grey mb-8"></div>
    </div>

    <Nuxt  class="markdown-body"/>
  </div>
</template>

<script>
export default {
    
}
</script>

<style>
  @import url('https://cdnjs.cloudflare.com/ajax/libs/github-markdown-css/4.0.0/github-markdown.min.css');

  .markdown-body {
		box-sizing: border-box;
		min-width: 200px;
		max-width: 980px;
		margin: 0 auto;
		padding: 45px;
	}

	@media (max-width: 767px) {
		.markdown-body {
			padding: 15px;
		}
	}
</style>
