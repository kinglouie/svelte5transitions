<script lang="ts">
	import { fly } from 'svelte/transition';
</script>

<a href="/">Page 1</a><br />

<img
    in:fly|global={{ y: '-30px', duration: 2500 }}
    out:fly|global={{ y: '30px', duration: 2500 }}
    src="https://picsum.photos/200/300" />