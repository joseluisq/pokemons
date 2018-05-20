# Pokémons

> Full JSON file with every Pokémon basic info. Useful for prototyping. 

_Inspirated by [Pokemondb](https://pokemondb.net/pokedex/all)_

## Install

[Yarn](https://github.com/yarnpkg/)

```sh
yarn add pokemons
```

[NPM](https://www.npmjs.com/)

```sh
npm install pokemons
```

## API

__URL:__

- `https://unpkg.com/pokemons`
- `https://unpkg.com/pokemons/pokemons.json`

_This JSON file is available via [unpkg](https://unpkg.com)._

__Data:__

The JSON file contains an array of Pokémons.

```js
{
  "name": "Venusaur",
  "type": [
    "Grass",
    "Poison"
  ],
  "national_number": "003",
  "evolution": {
    "name": "Mega Venusaur"
  },
  "sprites": {
    "normal": "https://img.pokemondb.net/sprites/omega-ruby-alpha-sapphire/dex/normal/venusaur.png",
    "large": "https://img.pokemondb.net/artwork/venusaur.jpg",
    "animated": "https://img.pokemondb.net/sprites/black-white/anim/normal/venusaur.gif"
  },
  "total": 625,
  "hp": 80,
  "attack": 100,
  "defense": 123,
  "sp_atk": 122,
  "sp_def": 120,
  "speed": 80
}
```

## Contributions

Feel free to send some [Pull request](https://github.com/joseluisq/pokemons/pulls) or [issue](https://github.com/joseluisq/pokemons/issues).

## License
MIT license

© 2018 [José Luis Quintana](http://git.io/joseluisq)
