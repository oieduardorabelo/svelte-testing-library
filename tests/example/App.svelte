<script>
	export let name;

	let buttonText = "Button Text";

	function handleClick() {
	  buttonText = "Button Clicked";
	}
</script>

<style>
	h1 {
	  color: purple;
	}
</style>

<h1>Hello {name}!</h1>

<button on:click={handleClick}>{buttonText}</button>
