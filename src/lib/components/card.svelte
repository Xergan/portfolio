<script lang="ts">
	import GithubIcon from "$lib/svgs/github_icon.svelte";
	import ItchIcon from "$lib/svgs/itch_icon.svelte";

  let {title, description, image, alt, isNew = false, tags = []} = $props();
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
      <div class="card-actions justify-start">
        {#each tags as tag}
          <div class="badge badge-outline">{tag}</div>
        {/each}
      </div>
      <div class="card-actions justify-end">
        <a class="btn btn-secondary" href="/">
          <ItchIcon/>
          Itch.io
        </a>
        <a class="btn btn-primary" href="/">
          <GithubIcon/>
          Github
        </a>
      </div>
    </div>
</div>