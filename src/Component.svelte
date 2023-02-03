<script>
  import Select from 'svelte-select';

  let text;

  let items = [`Svelte`, `React`, `Vue`, `Angular`];
</script>

hello text
<Select {items} />