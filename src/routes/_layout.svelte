<script>
	import Nav from '../components/Nav.svelte';

	export let segment;
</script>

<Nav {segment}/>

<main>
	<div class="container">
		<slot></slot>
	</div>
</main>
