<script lang="ts">
    import Card from '$lib/components/card.svelte';
	import MenuBar from '$lib/components/menu_bar.svelte';
</script>

<MenuBar/>

<div class="pt-28 pb-4 w-full justify-center flex">
    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-16">
        <Card 
            title="To-Do app ☑️" 
            image="images/todo_app.png" 
            alt="to-do app screen" 
            description="A simple To-Do app, designed to test UI, state management, and performance."
            tags={["🌊 Flutter", "🎯 Dart"]}
            github="https://github.com/Xergan/todo_app"
        />
    </div>
</div>