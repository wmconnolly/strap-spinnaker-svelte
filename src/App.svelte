<script>
  let greatThings = ["You", "will", "do", "great", "things!"];
</script>

<style>

</style>

<div class="row justify-self-center">
  <div class="col mt-3 d-flex justify-content-around text-indigo-500 shadow">
    {#each greatThings as word}
      <p class="d-inline-block">{word}</p>
    {/each}
  </div>

</div>
