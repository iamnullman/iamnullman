<script context="module" lang="ts">
	export const prerender = true;
	import Projects from "../components/Index/projects.svelte";
	import Info from "../components/Index/info.svelte";
import Technologies from "../components/Index/technologies.svelte";
import Whatiam from "../components/Index/whatiam.svelte";
</script>

<div class="items-center justify-center p-10">
<Info/>
<Projects />
<Technologies />
<Whatiam/>
</div>