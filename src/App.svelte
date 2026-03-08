<script>
  import Parent from './components/Parent.svelte';
  export let condition = true;
</script>

<main>
 <h1 class="text-center text-sky-400">Hello World!</h1>
 <h1 class:text-center={condition}> Conditionally center aligned</h1>
 <Parent />
</main>

