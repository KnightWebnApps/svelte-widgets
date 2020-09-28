<script>
  export let onClick = () => {}
  export let disabled = false

</script>

<button {disabled} on:click={onClick}>
  <slot name="icon"></slot>
  <slot>Submit</slot>
</button>
