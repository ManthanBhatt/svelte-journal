<script lang="ts">
	import Child from "./component/Child.svelte";
	const name:string = 'world';
</script>

<style>
	h1 {
		color: purple;
	}
</style>

<h1>Hello {name}!</h1>
<Child></Child>