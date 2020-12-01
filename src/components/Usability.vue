<template>
  <div>
    <b-jumbotron fluid container-fluid="md" border-variant="dark" class="full-height">
      <template #header>
        <span class="h1">Usabilities Principles</span>
      </template>

      <template #lead>
        The web app was created by keeping the four usability guidlines: usability, learnability, memorability and efficiency in mind.
      </template>

      <hr class="my-4" style="color:white;">
      <span><b>Usability:</b></span>
      <ul>
        <li>
        The site visitors don't get an error when trying to search, filter or sort repositories or load the site.
        </li>
        <li>
        There are no dead or broken links on the site.
        </li>
        <li>
        The site can handle different screen sizes and slow connections.
        </li>
        <li>
        The cards section has the ring spinner when the API has not fetched results, to make sure the 
        users are engaged.
        </li>
      </ul>
      <span><b>Learnability:</b></span>
      <ul>
        <li>
        The site was developed keeping simplicity in mind to avoid distracting the users.
        </li>
        <li>
        The site is developed using the known patterns of having filters in sidebars seperate from 
        cards to make learnability easier.
        </li>
        <li>
        There is consistency in the format of the cards and the colors of the entire website.
        </li>
        <li>
        The form controls in sidebar have the topics and language in the same format as they are in cards.
        </li>
        <li>
        The search on keyword is instant and provides immediate feedback to the user.
        </li>
        <li>
        The cards have information in good hierarchy and architecture.
        </li>
      </ul>
      
      <span><b>Memorability:</b></span>
      <ul>
        <li>
        The site visitors can recognize the cards in bookmarks from the cards on filter.
        </li>
        <li>
        The bookmark symbol matches the bookmarks on books.
        </li>
        <li>
        The site uses familiar words like stars, topics, etc as used in Github.
        </li>
        <li>
        The form allows to reset all filters to null, providing user control over things.
        </li>
      </ul>
      <span><b>Efficiency:</b></span>
      <ul>
        <li>
        The site does an async call to the API and thus we can achieve instant keyword search.
        </li>
        <li>
        The site allows to bookmark repositories, providing personalization.
        </li>
        <li>
        The users can also customize the content in cards section based on the filters in the sidebar.
        </li>
        <li>
        The repositories are listed as cards to show information in a concise and understandable manner.
        </li>
      </ul>

      <b-button variant="primary" class="ml-2" href="#deploy" >SOURCE CODE & DEPLOYED WEBSITE</b-button>
    </b-jumbotron>
  </div>
</template>

<script>
export default {
  name: 'Usability',
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