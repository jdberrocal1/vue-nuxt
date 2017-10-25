<template>
  <div>
    <header>
      <nav class="flex w-75 justify-around f4 code pa1">
        <nuxt-link class="link underline-hover" to="/">Home</nuxt-link>
        <nuxt-link class="link underline-hover" to="/ask">Ask</nuxt-link>
        <nuxt-link class="link underline-hover" to="/jobs">Jobs</nuxt-link>
        <nuxt-link class="link underline-hover" to="/news">News</nuxt-link>
        <nuxt-link class="link underline-hover" to="/show">Shows</nuxt-link>
      </nav>
    </header>
    <nuxt></nuxt>
  </div>
</template>

<style>
  .nuxt-link-exact-active{
    background-color: gray;
    color: white;
    padding: 5px 10px;
  }
</style>

