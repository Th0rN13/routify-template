<script>
	let name = 'name';

	function handleClick() {
		name += 'e';
	}
</script>

<!-- routify:options name="main" -->
<button on:click={handleClick}>click</button>
{name}
