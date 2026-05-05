<script module lang="ts">
	// eslint-disable-next-line no-restricted-imports -- reserved for mdsvex
	import { img, a, table } from '$lib/components/custom'
	export { img, a, table }
</script>

<script lang="ts">
	interface Props {
		children?: import('svelte').Snippet
	}

	let { children }: Props = $props()
</script>

{@render children?.()}
