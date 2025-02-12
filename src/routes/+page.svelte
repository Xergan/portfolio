<script lang="ts">
	import MenuBar from "$lib/components/menu_bar.svelte";
	import BlueskyIcon from "$lib/svgs/bluesky_icon.svelte";
	import DiscordIcon from "$lib/svgs/discord_icon.svelte";
	import EmailIcon from "$lib/svgs/email_icon.svelte";
	import GithubIcon from "$lib/svgs/github_icon.svelte";
	import InstagramIcon from "$lib/svgs/instagram_icon.svelte";
</script>

<MenuBar />

<div class="fixed h-full w-full bg-cover bg-top" style="background-image: url(/images/background.png);">
  <div class="h-full w-full backdrop-blur-sm bg-base-300 bg-opacity-70"></div>
</div>
<div class="hero min-h-screen">
<div class="hero-content lg:w-2/3 w-full min-h-screen">
    <div class="hero-content flex-col lg:flex-row-reverse">
      <img
        src="https://github.com/xergan.png"
        class="max-w-64 rounded-lg shadow-2xl"
        alt="Xergan's github pfp" />
      <div class="bg-transparent">
        <h1 class="text-4xl md:text-5xl pb-3 h-auto text-center md:text-left">Hi, I'm <span class="font-bold bg-gradient-to-r from-pink-500 to-blue-500 bg-clip-text text-transparent">Xergan</span>!</h1>
        <p class="pt-3 pb-6 text-lg text-center md:text-left">
            Self-taught developer with a strong background in game development, web development, and mobile app development.
        </p>
        <div class="flex gap-2 justify-center md:justify-start">
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
</div>
