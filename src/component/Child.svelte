<script lang="ts">
  const name: string = "child component";
  let count = 0;
  const hitMe = () => count++;
</script>

<p>Hello from {name}.</p>
<button on:click={hitMe}>Hit me {count}</button>
