<script lang="ts">
	import GamesIcon from "$lib/svgs/games_icon.svelte";
	import HomeIcon from "$lib/svgs/home_icon.svelte";
	import MobileIcon from "$lib/svgs/mobile_icon.svelte";
	import WebsitesIcon from "$lib/svgs/websites_icon.svelte";


</script>

<div class="w-full my-4 flex justify-center fixed z-10">
  <div class="relative mx-auto max-w-md rounded-box bg-gradient-to-r from-pink-500 to-blue-500 p-0.5 shadow-lg" style="backdrop-filter: blur(35px); filter:opacity(0.75)">
  <ul class="menu menu-horizontal bg-base-200 rounded-box" style="filter:opacity(0.75)">
    <li>
      <a class="tooltip tooltip-bottom" data-tip="Home" aria-label="Home" href="/">
        <HomeIcon />
      </a>
    </li>
    <li>
      <a class="tooltip tooltip-bottom" data-tip="Games" aria-label="Games" href="/games">
        <GamesIcon />
      </a>
    </li>
    <li>
      <a class="tooltip tooltip-bottom" data-tip="Websites" aria-label="Websites" href="/">
        <WebsitesIcon />
      </a>
    </li>
    <li>
      <a class="tooltip tooltip-bottom" data-tip="Mobile Apps" aria-label="Mobile Apps" href="/">
        <MobileIcon />
      </a>
    </li>
  </ul>
</div>
</div>