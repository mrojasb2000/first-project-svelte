<script>
  export let date;
  // Deviring the 'label' variable from the 'date' prop
  $: label = date.toLocaleDateString();
</script>
<p>{label}</p>
