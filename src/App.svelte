<script>
	import {Router, Link, Route} from 'svelte-routing';
	import Home from './pages/Home.svelte';

	export let url = '/';
</script>

<main>
	<Router url={url}>
		<nav>
			<Link href="/">Home</Link>
		</nav>
		<Route path="/home" component={Home} />
	</Router>
</main>
<style>

</style>