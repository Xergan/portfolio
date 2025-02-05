<script lang="ts">
	import MenuBar from "$lib/components/menu_bar.svelte";
	import BlueskyIcon from "$lib/svgs/bluesky_icon.svelte";
	import DiscordIcon from "$lib/svgs/discord_icon.svelte";
	import EmailIcon from "$lib/svgs/email_icon.svelte";
	import GithubIcon from "$lib/svgs/github_icon.svelte";
	import InstagramIcon from "$lib/svgs/instagram_icon.svelte";


</script>

<MenuBar />
<div class="hero flex justify-center bg-base-200 min-h-screen pt-8 md:pt-16 lg:pt-0">
<div class="hero-content lg:w-2/3 w-full min-h-screen">
    <div class="hero-content flex-col lg:flex-row-reverse">
      <img
        src="https://github.com/xergan.png"
        class="max-w-64 rounded-lg shadow-2xl"
        alt="Xergan's github pfp" />
      <div>
        <h1 class="text-4xl md:text-5xl font-bold">Hi, I'm Xergan!</h1>
        <p class="py-6 text-wrap">
            Self-taught developer with a strong background in game development, web development, and mobile app development.
        </p>
        <a class="btn btn-circle btn-outline" href="https://github.com/Xergan" aria-label="Github">
            <GithubIcon />
        </a>
        <a class="btn btn-circle btn-outline" href="https://discordapp.com/users/767827683811655730" aria-label="Discord">
            <DiscordIcon />
        </a>
        <a class="btn btn-circle btn-outline" href="https://bsky.app/profile/xergan.com" aria-label="Bluesky">
            <BlueskyIcon />
        </a>
        <a class="btn btn-circle btn-outline" href="https://instagram.com/xergan" aria-label="Instagram">
            <InstagramIcon />
        </a>
        <a class="btn btn-circle btn-outline" href="mailto:contact@xergan.com" aria-label="Email">
            <EmailIcon />
        </a>
      </div>
    </div>
  </div>
</div>