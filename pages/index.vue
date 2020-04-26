<template>
  <section class="hero is-fullheight-with-navbar is-primary">
    <div class="hero-body">
      <div class="container">
        <div class="columns">
          <div class="column">
            <h1 class="title is-size-1">
              Novel Petstore
              <br />is coming up!
            </h1>
            <p>JPetstore UI will be updated.</p>
            <div class="buttons" style="margin-top: 1em">
                <a class="button is-link is-medium"><nuxt-link to="/login">Get Started</nuxt-link></a>
            </div>
          </div>
          <div class="column">
            <img src="~/assets/buefy.png" width="500" height="500" alt srcset />
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import Card from "~/components/Card";

export default {
  name: "HomePage",

  components: {
    Card
  }
};
</script>
