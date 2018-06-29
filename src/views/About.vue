<template>
  <div class="about">
    <h1 class="title is-1 is-spaced" v-if="their_name">Hello {{their_name}}, this is the about page.</h1>
    <h1 class="title is-1 is-spaced" v-else>Hello randy, this is the about page.</h1>

    <p>
      Paragraph Here BTW.
    </p>
  </div>
</template>

<script>
export default {
  name: "About",
  data() {
    return {
      their_name: this.$route.params.name
    };
  }
};
</script>

<style scoped>
h1 {
  margin-top: 20px;
}

/* For mobile phones: */
@media only screen and (max-width: 620px) {
  .about {
    margin: 10px;
    width: 100%;
  }
  h1 {
    padding-top: 50px;
  }
}
</style>
