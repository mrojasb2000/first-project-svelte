<script>
  export let date;
  export let locale;
  // Deviring the 'label' variable from the 'date' prop
  $: label = date.toLocaleDateString(locale);
</script>
<p>{label}</p>
