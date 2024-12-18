<script lang="ts">
	import GridBeam from '$lib/components/animations/GridBeam.svelte';
</script>

<div class="h-full w-full bg-grid-black/[0.07] dark:bg-grid-white/[0.05]">
	<GridBeam class="flex items-start justify-start">
		<slot />
	</GridBeam>
</div>
