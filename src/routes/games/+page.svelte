<script lang="ts">
    import Card from '$lib/components/card.svelte';
	import MenuBar from '$lib/components/menu_bar.svelte';
</script>

<MenuBar/>

<div class="pt-28 pb-4 w-full justify-center flex">
    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-16">
        <Card 
            title="Shoes!" 
            image="https://img.daisyui.com/images/stock/photo-1606107557195-0e29a4b5b4aa.webp" 
            alt="shoes" 
            description="If a dog chews shoes whose shoes does he choose?" 
            />
    </div>
</div>