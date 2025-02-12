<script lang="ts">
    import Card from '$lib/components/card.svelte';
	import MenuBar from '$lib/components/menu_bar.svelte';
</script>

<MenuBar/>

<div class="pt-28 pb-4 w-full justify-center flex">
    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-16">
        <Card 
            title="Drawing ✏️" 
            image="images/drawing.png" 
            alt="drawing game screen" 
            description="A short demo of a platformer featuring unique drawing-based mechanics."
            tags={["🤖 Godot", "💻 GDScript"]}
            github="https://github.com/Xergan/drawing-game"
            itch="https://xergan.itch.io/drawing-game"
        />

        <Card 
            title="Basketball 🏀" 
            image="images/basketball.png" 
            alt="basketball game screen" 
            description="A remake of the classic hidden basketball minigame from Meta's Messenger!"
            tags={["🤖 Godot", "💻 GDScript"]}
            github="https://github.com/Xergan/Basketball"
            itch="https://xergan.itch.io/basketball"
        />
    </div>
</div>