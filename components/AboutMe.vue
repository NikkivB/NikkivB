<template>
  <div class="text-gray-600 body-font">
    <div class="container mx-auto flex px-5 py-24 md:flex-row flex-col items-center">
      <div class="lg:flex-grow md:w-1/2 lg:pr-24 md:pr-16 flex flex-col md:items-start md:text-left mb-16 md:mb-0 items-center text-center">
        <h1 class="title-font sm:text-4xl text-3xl mb-4 font-bold text-dark-sky">A bit about me
        </h1>
        <p class="mb-8 leading-relaxed">I'm a 20 years old student.
          I love developing backend applications and I love playing with data.
          <br>I'm an intern junior software developer at StoreKeeper B.V.
          <br>I'm eager to learn new things and I'm always looking for new challenges.
          <br>My favorite programming languages are Python, R and PHP.
        </p>

        <div class="flex justify-center">
          <button class="inline-flex items-center text-mountbatten border-2 border-mountbatten py-2 px-6 focus:outline-none hover:bg-lavender hover:border-lavender hover:text-white rounded text-lg">
            <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 20l4-16m4 4l4 4-4 4M6 16l-4-4 4-4"></path></svg>
            &nbsp;My projects</button>
          <button class="ml-4 inline-flex items-center text-white bg-mountbatten border-0 py-2 px-6 focus:outline-none hover:bg-lavender rounded text-lg">
            <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path></svg>
            &nbsp;Contact</button>
        </div>
      </div>
      <div class="lg:max-w-lg lg:w-full md:w-1/2 w-5/6">
        <img class="object-cover object-center rounded" alt="hero" src="https://dummyimage.com/720x600">
      </div>
    </div>
  </div>
</template>

<script>

export default {

}
</script>
