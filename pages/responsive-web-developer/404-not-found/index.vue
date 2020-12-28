<template>
  <div id="page-404-not-found" class="max-w-md lg:max-w-5xl mx-auto font-normal px-8">
    <header class="py-6">
      <h5 class="text-purple-700 uppercase">404 Not Found</h5>
    </header>
    <main class="lg:grid lg:grid-cols-2 lg:gap-16 py-10 lg:py-20">
      <section class="flex justify-center items-start">
        <img src="~/assets/images/Scarecrow.png" class="w-72 lg:w-full" alt="Scarecrow image">
      </section>
      <section class="mt-12 lg:mt-0">
        <h1 class="font-bold text-5xl lg:text-6xl text-purple-900 tracking-tight lg:leading-snug">I have bad news for
          you</h1>
        <p class="mt-12 lg:w-96 text-lg lg:text-xl text-gray-600 lg:leading-normal">The page you are looking for might
          be removed or is temporarily unavailable</p>
        <div class="mt-16 flex">
          <NuxtLink to="/"
                    class="px-10 py-6 bg-purple-900 hover:bg-purple-800 font-bold text-sm text-white rounded uppercase focus:outline-none focus:ring-4 focus:ring-purple-300 transition duration-200">
            Back to Homepage
          </NuxtLink>
        </div>
      </section>
    </main>
  </div>
</template>

<script>
export default {
  head: {
    title: '404 Not Found - Dev Challenges',
    link: [
      {rel: 'preconnect', href: 'https://fonts.gstatic.com'},
      {rel: 'stylesheet', href: 'https://fonts.googleapis.com/css2?family=Overpass+Mono:wght@400;700&display=swap'},
    ]
  }
}
</script>

<style>
#page-404-not-found {
  font-family: 'Overpass Mono', monospace;
}
</style>
