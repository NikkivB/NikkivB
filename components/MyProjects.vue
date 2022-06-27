<template>
  <div>
    <img src="~/assets/images/divider1.svg" alt="no" class="w-screen h-auto"/>
    <div class="flex w-screen text-black body-font bg-apricot justify-center">
      <div class="w-10/12 py-14 -mt-40">
        <p class="text-5xl">
          Projects
        </p>
        <div class="flex justify-evenly w-screen">
          <div class="bg-white rounded-md h-48 w-3/12">
            <p>.</p>
          </div>
          <div class="bg-white rounded-md h-48 w-11/12">
            <p>.</p>
          </div>
          <div class="bg-white rounded-md h-48 w-11/12">
            <p>.</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
const projects = [
  {
    name: 'YAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA',
    url: 'https://nikkivanbraam.nl'
  },
]

export default {
  name: 'MyProjects',
  data() {
    return {
      projects
    }
  }
}
</script>
