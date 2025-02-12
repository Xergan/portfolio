<script lang="ts">
	import GithubIcon from "$lib/svgs/github_icon.svelte";
	import ItchIcon from "$lib/svgs/itch_icon.svelte";
	import WebsitesIcon from "$lib/svgs/websites_icon.svelte";

  let {title, description, image, alt, isNew = false, tags = [],  github="", itch="", website=""} = $props();
</script>

<div class="card bg-base-100 w-96 shadow-xl">
    <figure>
      <img
        src={image}
        alt={alt} />
    </figure>
    <div class="card-body">
      <h2 class="card-title">
        {title}
        {#if isNew}
        <div class="badge badge-secondary">NEW</div>
        {/if}
      </h2>
      <p>{description}</p>
      <div class="card-actions justify-start mb-2">
        {#each tags as tag}
          <div class="badge badge-outline">{tag}</div>
        {/each}
      </div>
      <div class="card-actions justify-center">
        {#if itch}
        <a class="btn btn-secondary" href={itch} target="_blank">
          <ItchIcon/>
          Itch.io
        </a>
        {/if}
        {#if website}
        <a class="btn btn-accent" href={website} target="_blank">
          <WebsitesIcon/>
          Website
        </a>
        {/if}
        {#if github}
        <a class="btn btn-primary" href={github} target="_blank">
          <GithubIcon/>
          Github
        </a>
        {/if}
      </div>
    </div>
</div>