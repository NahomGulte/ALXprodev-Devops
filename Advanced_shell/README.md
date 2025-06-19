Objective: Automate the process of making API requests to the Pokémon API and saving the results to a file

Instructions:

Write a shell script that makes a request to the Pokémon API and retrieves data for a specific Pokémon Pikachu.

It should save the response to a json file: data.json

If the request fails, it should log the error to an error file: errors.txt

Sample Output

ghostmode@GhostMode:~$ jq . < data.json | head -n 50
{
  "abilities": [
    {
      "ability": {
        "name": "static",
        "url": "https://pokeapi.co/api/v2/ability/9/"
      },
      "is_hidden": false,
      "slot": 1
    },
    {
      "ability": {
        "name": "lightning-rod",
        "url": "https://pokeapi.co/api/v2/ability/31/"
      },
      "is_hidden": true,
      "slot": 3
    }
  ],
  "base_experience": 112,
  "cries": {
    "latest": "https://raw.githubusercontent.com/PokeAPI/cries/main/cries/pokemon/latest/25.ogg",
    "legacy": "https://raw.githubusercontent.com/PokeAPI/cries/main/cries/pokemon/legacy/25.ogg"
  },
  "forms": [
    {
      "name": "pikachu",
      "url": "https://pokeapi.co/api/v2/pokemon-form/25/"
    }
  ],
  "game_indices": [
    {
      "game_index": 84,
      "version": {
        "name": "red",
        "url": "https://pokeapi.co/api/v2/version/1/"
      }
    },
    {
      "game_index": 84,
      "version": {
        "name": "blue",
        "url": "https://pokeapi.co/api/v2/version/2/"
      }
    },
    {
      "game_index": 84,
      "version": {
        "name": "yellow",
        "url": "https://pokeapi.co/api/v2/version/3/"
