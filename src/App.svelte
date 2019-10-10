<script>
  let count = 0;
  export function handleClick() {
    count += 1;
  }
</script>

<style>
  button {
    color: purple;
  }
</style>

<button on:click={handleClick}>Clicked {count}</button>
