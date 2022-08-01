<template>
    <section class="hero is-fullheight bg-color tablet:flex tablet:flex-row-reverse tablet:justify-between">
      <div class="hero-body">
        <div class="hero-icon w-full tablet:w-5/12 desktop-md:w-1/2 tablet:block">
          <img
            src="@/assets/img/happy_kids.png"
            alt="Kids being happy"
            class="img-size"
          />
      </div>
      <div class="hero-content w-full mt-8 tablet:mt-0 tablet:w-7/12 desktop-md:w-1/2">
        <p class="title change-text">
          Purple<span class="spring-text"> Spring </span><span class="text"> - A place where dreams become Reality</span>
        </p>
        <p class="change-paragraph">
          I welcome you to take your time and look around, and watch as all my dreams become reality. All my idea come to life right before your eyes. I hope you enjoy this journey as much as I did while making it all.
        </p>
      </div>

      </div>
      
    </section>
</template>

<script>
export default {
  name: 'LandingPage',
  components: {
    
  },
}

</script>

<style>
.bg-color{
  background-color: white;
}

.hero-icon{
  max-width: 50%;
  width: 50%;
  height: 50%;
  position: relative;
}

.hero-content{
  padding-right: 0;
  max-width: 50%;
  margin-right: 15px;
}

.hero-body{
  flex-direction: row-reverse;
}

.img-size{
  margin-left: 100px;
}

.hero.is-fullheight {
    min-height: 150px;
    margin-left: auto;
    margin-right: auto;
}

.hero-body {
    padding: 0px 3rem !important;
}

.change-text{
  color:  var(--purple);
}

.spring-text{
    color: var(--light-green);
    font-size: medium;
    vertical-align: super;
}

.text{
  color: black;
}

.change-paragraph{
  color: var(--purple);
  font-size: larger;
}

</style>
