<script lang="ts">
	export let name: string;
	export let id: number;
	export let src: string;
</script>

<p>{name}</p>
<p>{id}</p>
<img {src} alt="Pokemon {name}" />
