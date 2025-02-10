<script lang="ts">
    import Card from '$lib/components/card.svelte';
	import MenuBar from '$lib/components/menu_bar.svelte';
import type { PageData } from './$types';

    let { data }: { data: PageData } = $props();
</script>

<MenuBar/>
<Card></Card>