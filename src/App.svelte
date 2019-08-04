<script>
  let greatThings = ["You", "will", "do", "great", "things!"];
</script>

<style>

</style>

<div class="row">
  <div class="col d-flex justify-content-around text-indigo-500 shadow">
    {#each greatThings as word}
      <p class="d-inline-block">{word}</p>
    {/each}
  </div>

</div>
