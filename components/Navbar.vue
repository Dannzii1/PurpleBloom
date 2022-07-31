<template>
      <b-navbar transparent="true">
          <template #brand>
            <b-navbar-item tag="router-link" :to="{ path: '/' }">
              <img
                src="@/assets/img/smile.png"
                alt="Smiling Logo"
              >
              <span class="Largepurple">Purple</span><span class="Littlegreen">Bloom</span>
            </b-navbar-item>
          </template>
          <template #end>
            <b-navbar-item class="textcolor">
              About Me
            </b-navbar-item>
            <b-navbar-item class="textcolor">
              Work
            </b-navbar-item>
            <b-navbar-item class="textcolor">
              Contact
            </b-navbar-item>
            <b-navbar-item>
              <a to="https://github.com/Dannzii1" target="_blank">
                <img
                src="@/assets/img/github.png"
                alt="github Logo"
              >
              </a>
            </b-navbar-item>
          </template>
    </b-navbar>
</template>

<script>
export default {
   name: 'NavBar'

}
</script>

<style>
.Largepurple{
  color: #a324eb;
  font-size: 1.6rem;
  margin-left: 10px;
}

.Littlegreen{
  color: #13e5d0;
}

.textcolor{
  color:black;
}
</style>
