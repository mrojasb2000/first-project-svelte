<script lang='ts'>
  // Defining state
  let count: number = 0;

  function increment() {
    count += 1;
  }
</script>
<button on:click={increment}>Click me</button>
<p>{count}</p>
