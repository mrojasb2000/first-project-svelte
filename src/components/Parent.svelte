<script>
  import Child from './Child.svelte';
  import Counter from './Counter.svelte';
  import Bindings from './Bindings.svelte';
  import Profile from './Profile.svelte';
  import DateLabel from './DateLabel.svelte';
  
  let name = 'john';
</script>
<Child message="Hello World!" />
<Counter />
<Bindings />
<Profile bind:username={name} />
<DateLabel date={new Date(2026,3,9)} />
