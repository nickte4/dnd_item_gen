# D&D Item Generator

## Project Idea/Scope

- generates a random d&d item of a randomized rarity
- ability to choose btwn. randomized or specific rarity
- keeps track of last 10 generated items

## Project Architecture

- external api: D&D 5e API (https://www.dnd5eapi.co)
- languages: Java
- frameworks: Spring Boot (to make api)
- test framework: JUnit
- data persistence: JSON files 

## Project MVC
- Model -> list of recently generated items, calls to D&D API
- View -> command line UI for interaction/observation
- Controller -> Spring Boot RESTful API endpoints to handle view <=> model interactions

## Test Cases / User Stories
- [ ] user can generate a randomized d&d item of a randomized rarity
- [ ] user can pick a specific rarity
- [ ] user can pick a specific rarity and generate a random item with that rarity
- [ ] user can view last 10 generated items
