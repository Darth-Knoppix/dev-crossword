<script>
  import Crossword from "svelte-crossword";
  import data from "../content/react-1.json"
</script>

<main>
  <h1>React Crossword</h1>
  <Crossword data="{data}" />
</main>

<style>
  main {
    text-align: center;
    padding: 1em;
    max-width: 240px;
    margin: 0 auto;
  }

  h1 {
    color: #ff3e00;
    text-transform: uppercase;
    font-size: 4em;
    font-weight: 100;
  }

  @media (min-width: 640px) {
    main {
      max-width: none;
    }
  }
</style>
