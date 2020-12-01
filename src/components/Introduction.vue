<template>
  <div>
    <b-jumbotron fluid container-fluid="md" bg-variant="dark" text-variant="white" border-variant="dark" class="full-height">
      <template #header>
        <span class="h1">Development</span>
      </template>

      <template #lead>
        <span class="h3">Practicing the workflow of creating a list interface in React.</span>
      </template>

      <hr class="my-4" style="color:white;">

      <p>
        There are many great repositories templates available on GitHub, however, 
        I didn't find one good search platform to search through the repositories by many filters. 
        I created a search app in React through which you can filter and sort on repositories to find any public repository.
        So before starting your project you can look for repositories on similar ideas through keyword search and topics search
        and sort them by stars to get the most popular repository. You can also look for the specific language implementation of 
        the idea. This is more beneficial as it 
        also allows you to bookmark repositories you find useful and aggregates them into bookmarks view as cards.

      </p>
      <b-button variant="primary" class="ml-2" href="#usability" >USABILITY</b-button>
    </b-jumbotron>
  </div>
</template>

<script>
export default {
  name: 'Introduction',
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