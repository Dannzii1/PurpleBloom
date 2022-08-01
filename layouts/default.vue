<template>
   <div class="hero-wrapper bg-color">
    <Navbar class="bg-color" />
    <section>
       <Nuxt />
    </section>
    <Footer class="is-flex-shrink-1" />
    </div>
</template>

<script>
export default {
  name: 'DefaultLayout',
  data() {
    return {
      items: [
        {
          title: 'Home',
          icon: 'home',
          to: { name: 'index' },
        },
      ],
    }
  },
}
</script>
<style>
:root {
  --vs-theme-bg2: #f0f0f0;
  --alice-blue: #eef2f5ff;
  --white: #ffffffff;
  --midnight-green-eagle-green: #004e64ff;
  --pink: #f95858;
  --light-pink: #fb8a8a;
  --dark: #363636;
  --purple: #a324eb;
  --light-green:  #13e5d0;
}

.bg-color{
  background-color:white;
}
</style>