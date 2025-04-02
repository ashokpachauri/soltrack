<script>
    import Network from "../network.svelte";
</script>

{#each [{ name: "Home", url: "/" }, { name: "About IM WEB PROS", url: "https://imwebpros.com" }] as { name, url }}
    <a
        href={url}
        data-sveltekit-reload
        class="btn-ghost btn w-full">{name}</a
    >
{/each}
<Network />
