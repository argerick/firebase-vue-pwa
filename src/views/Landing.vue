<template><div>
  <section class="hero is-primary has-navbar-fixed-top is-medium shadow is-fullheight">
    <!-- Hero head: will stick at the top -->
    <div class="hero-head">
      <Navbar />
    </div>

    <!-- Hero content: will be in the middle -->
    <div class="hero-body">
      <div class="container has-text-centered my-content">
        <h1 class="title is-2">Welcome to your new app! 🎉</h1>
        <h2 class="subtitle is-4">
          Deploying a Firebase Progressive Web App has never been this easy!
        </h2>
      </div>
    </div>
  </section>
  <section class="content landing-body">
    <div class="tile is-ancestor">
      <div class="tile is-parent">
        <div class="tile is-child box">
          <h3>🔥 Integrate to Firebase</h3>
          <p>
           Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque tincidunt, eros a faucibus sollicitudin, nunc nunc feugiat metus, vel ullamcorper metus sem at dolor. Vivamus posuere elementum mauris, vitae porttitor risus maximus non. Sed pulvinar ipsum ut orci tincidunt iaculis.
          </p>
        </div>
      </div>
      <div class="tile is-parent">
        <div class="tile is-child box">
          <h3>⚙️ Configure the template</h3>
          <p>
            Sed pulvinar ipsum ut orci tincidunt iaculis. Aliquam condimentum vestibulum leo, vitae posuere turpis auctor ac. Praesent ligula mauris, euismod a ante vitae, sodales volutpat dolor. Morbi pharetra erat non efficitur accumsan. Nullam mattis maximus ipsum sed pretium. Integer eget purus volutpat, mollis dui quis, pulvinar velit.
          </p>
        </div>
      </div>
      <div class="tile is-parent">
        <div class="tile is-child box">
          <h3>🍺 Add your content</h3>
          <p>
            Aliquam condimentum vestibulum leo, vitae posuere turpis auctor ac. Praesent ligula mauris, euismod a ante vitae, sodales volutpat dolor. Morbi pharetra erat non efficitur accumsan. Nullam mattis maximus ipsum sed pretium. Integer eget purus volutpat, mollis dui quis, pulvinar velit.
          </p>
        </div>
      </div>
    </div>
  </section>
  </div>
</template>

<script>
import Navbar from "../components/NavbarLanding.vue";

export default {
  components: { Navbar },
  mounted: function() {
    document.getElementById("app").classList.remove("has-navbar-fixed-top");
  }
};
</script>

<style scoped>
  .my-content {
    max-width: 52em;
  }
  .custom-field {
    max-width: 32em;
  }
  .landing-body {
    margin: 3em auto;
    max-width: 66rem;
    padding: 0 2rem 0 2rem;
  }
  .shadow {
    box-shadow: 0px 0px 30px -14px rgb(20, 20, 20);
  }
</style>
