# Pokemon App

## Modelos

### Trainers

| id | name |
|----|------|
| 1  | ash  |

### Pokemon

| id | name    | hp  | level | category |
|----|---------|-----|-------|----------|
| 1  | pikachu | 100 | 1     | Electric |

### Attacks

| id | name  | category | power |
|----|-------|----------|-------|
| 1  | ember | Fire     | 43    |

## App

### Pokemons
* Cada pokemon empieza con un nivel random del 0 al 30
* Cada pokemon 4 ataques random - 2 normales y 2 de su tipo

### Entrenadores

* Cada entrenador comienza el juego con 5 pokemons random

### Batallas

* Un hit es un ataque random de la lista de ataques del pokemon
* El daño de un hit es: `power + pokemon_level / 10`
* Una batalla consiste en que se ataquen 2 poquemones hasta que uno se desmaya. El pokemon que no se desmaya gana
* Una batalla de entrenadores es pokemon contra pokemon el que tenga mas victorias
