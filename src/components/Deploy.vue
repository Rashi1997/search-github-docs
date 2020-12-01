<template>
  <div>
    <b-jumbotron fluid container-fluid="md" bg-variant="dark" text-variant="white" border-variant="dark" class="full-height">
      <template #header>
        <span class="h1">Deployment</span>
      </template>

      <!-- <template #lead>
        <span class="h3">Practicing the workflow of creating a list interface in React.</span>
      </template> -->

      <hr class="my-4" style="color:white;">

      <p>
        Then I finally deployed my site using Heroku.

      </p>
      <b-button variant="info" class="ml-2" href="https://github.com/Rashi1997/Search-Github" >SOURCE CODE</b-button>
      <b-button variant="primary" class="ml-2" href="https://agile-crag-93359.herokuapp.com/" >WEBSITE</b-button>
      <b-button variant="success" class="ml-2" href="#home" >BACK TO HOME</b-button>
    </b-jumbotron>
  </div>
</template>

<script>
export default {
  name: 'Deploy',
  components: {
  }
}
</script>

<style scoped>
  .full-height {
    height: 100%;
    padding-top: 9rem;
    padding-bottom: 15rem;
    margin-bottom: 0;
  }
  hr {
    border:0.01rem solid white;
  }
</style>