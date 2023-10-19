<script lang="ts">
	export let data;
	import Pokemon from '$lib/Pokemon.svelte';
</script>

<h1>Pokedex</h1>

{#each data.pokemon as { name, id, sprites }}
	<Pokemon {id} {name} src={sprites.front_default} />
	<!-- 	// destructuring -->
	<!-- 	<p>{name}</p>
	<p>{id}</p>
	<img src={sprites.front_default} alt="Pokemon {name}" />
 -->
{/each}
