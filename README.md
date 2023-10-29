# Pokedex
# Pokémon API

This project is a simple API for listing information about Pokémon.

## Overview

The API provides access to a list of Pokémon, displaying details such as name, type, and Pokédex number.

## Features

- [x] List Pokémon
- [ ] Search Pokémon by name
- [ ] Add new Pokémon
- [ ] Update Pokémon information
- [ ] Remove Pokémon


### List Pokémon

To list all available Pokémon, make a GET request to the `/pokemon` endpoint.

### Add a New Pokémon

To add a new Pokémon to the list, make a POST request to the `/pokemon` endpoint.

Example:

```json
POST /pokemon
{
  "name": "Charizard",
  "type": "Fire",
  "pokedex_number": 006
}



