<script>
  const year = new Date().getFullYear();
</script>

<footer>
  <slot {year} ></slot> 
</footer>

<style>
  footer {
    text-align: center;
    color: #33333365;
  }
</style>
