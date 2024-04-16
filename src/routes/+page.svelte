<script lang="ts">
    import Neko from '$lib/Neko.svelte';
</script>

<h1>svelte-neko</h1>

<Neko />

Example (component):

<pre>
    {`<script>
        import { Neko } from 'svelte-neko';
    </script>

    <Neko />`}
</pre>

Example (action): 

<pre>
    {`<script>
        import { action } from 'svelte-neko';
    </script>

    <div use:action>`}
</pre>