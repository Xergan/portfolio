<script lang="ts">
    import Card from '$lib/components/card.svelte';
	import MenuBar from '$lib/components/menu_bar.svelte';
</script>

<MenuBar/>

<div class="fixed h-full w-full bg-cover bg-top" style="background-image: url(/images/background.png);">
    <div class="h-full w-full backdrop-blur-sm bg-base-300 bg-opacity-70"></div>
</div>
<div class="pt-28 pb-4 w-full justify-center flex">
    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-16 mx-8">
        <Card 
            title="Portfolio 🎨" 
            image="images/website.png" 
            alt="portfolio screen" 
            description="A sleek portfolio website, showcasing my work in games, websites, and mobile apps!"
            tags={["🎀 Svelte 5", "🧶 SvelteKit"]}
            github="https://github.com/Xergan/portfolio"
            website="/"
        />

        <Card 
            title="Terminal CV 💾" 
            image="images/terminal.png" 
            alt="terminal cv screen" 
            description="A terminal-style CV website with interactive commands!"
            tags={["✨ React", "⚡ Vite"]}
            github="https://github.com/Xergan/terminal-cv"
            website="https://terminal.xergan.com"
        />
    </div>
</div>