<script lang="ts">
    import { onMount } from 'svelte'
    let mounted = false
    onMount(() => {setTimeout(() => mounted = true, 1556)})
</script>

are you there?

<br /><br />

{#if mounted}
    it's something, alright!
{:else}
    ...
{/if}