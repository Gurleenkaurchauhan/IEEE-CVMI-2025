<script>
    import Navbar from "./navbar.svelte"
	import '../app.css';
	let { children } = $props();
</script>

<div class="w-full overflow-hidden">
    <Navbar></Navbar>
</div>
<div class="h-16 w-full"></div>
{@render children()}
