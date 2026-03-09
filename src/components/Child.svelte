<script lang='ts'>
  // Defining props
  export let message:string;
  // Defining state
  let count: number = 0;

  function increment() {
    count += 1;
  }
</script>
<h1>{message}</h1>
<button on:click={increment}>Click me</button>
<p>{count}</p>
