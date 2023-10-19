<script lang="ts">
	export let data;
	console.log(data.pokemon[0]);

	const bulbasaur = data.pokemon[0];
	const { name, id, sprites } = bulbasaur;
</script>

<h1>Pokedex</h1>
<p>{name}</p>
<p>{id}</p>
<img src={sprites.back_default} alt="Pokemon {name}" />
