<template>
  <h1>¿Quien es este pokémon?</h1>
  <PokemonOption/>
  <PokemonPicture :pokemonId="4" :showPokemon ="false" />
</template>

<script>
import PokemonOption from '@/components/PokemonOption.vue';
import PokemonPicture from '@/components/PokemonPicture.vue';
import getPokemonsOptions from '@/helpers/getPokemonOptions'


export default {
  components:{
    PokemonOption,
    PokemonPicture

  }

}
</script>

