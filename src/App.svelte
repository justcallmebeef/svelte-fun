<script>
	let name = 'Svelte!!'

	function nameChange() {
		console.log(name)
		name = 'test function stuff'
		console.log(name)
	}
</script>

<style>

</style>

<h1 color="primary">Hello {name}!</h1>

<form>
Name: <br>
<input type="text">
<button on:click={nameChange}>Say Hello to me!</button>
</form>