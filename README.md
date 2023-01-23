# 2nd Call - Frontend Interview

## Part 1
Provided a Pokemon javascript object structured as such:

```
const bulbasaur = { id: 1, 
                    name: "Bulbasaur", 
                    types: ["grass"], 
                    sprite: "https://assets.pokemon.com/assets/cms2/img/pokedex/full/001.png" }
```

Create a reusable <PokemonRow /> component that takes in bulbasaur as a property and renders a row with the name, id, type and sprite image.

## Part 2
Provided a Pokemon javascript array structured as such:
```
const pokemons = [
  { 
    id: 1, 
    name: "Bulbasaur", 
    types: ["grass"], 
    sprite: "https://assets.pokemon.com/assets/cms2/img/pokedex/full/001.png"
  },{ 
    id: 1, 
    name: "Pikachu", 
    types: ["lightning"], 
    sprite: "https://assets.pokemon.com/assets/cms2/img/pokedex/full/025.png"
  },{ 
    id: 1, 
    name: "Squirtle", 
    types: ["water"], 
    sprite: "https://assets.pokemon.com/assets/cms2/img/pokedex/full/007.png"
  },
  { 
    id: 1, 
    name: "Pidgeotto", 
    types: ["air"], 
    sprite: "https://assets.pokemon.com/assets/cms2/img/pokedex/full/017.png"
  }
]
```
Create a <PokedexTable /> component that takes in the array and renders all the pokemon in that array.

## Part 3
Provided a <PokemonTypeSelection /> component with the following props
```
type PokemonTypeSelectionProps = {
	selectedType: string | undefined; 
	selectType: (type: string | undefined) => void; 
}
```
This component should display the types for the user to select:
```const types = ["grass", "water", "lightning", "air"]```

Then,
Create a <FilterablePokedexTable /> component that renders both the <PokemonTypeSelection /> component and <PokedexTable /> component. Make sure you only display Pokemon with the selected type!
