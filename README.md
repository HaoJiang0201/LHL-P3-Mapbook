# mapbook
Midterm project for Lighthouse Labs Web Development Bootcamp
Main Contributors: [Hao Jiang](https://github.com/HaoJiang0201), [Estella Song](https://github.com/estellajaysong), [Bonita Choi](https://github.com/bonitac)

## Overview
For our Midterm Project, we created an app called mapbook that allows users to create a map with markers by inputing an address or location name to create a marker. The location's name, description, photo may be editted as desired. Users can add or remove locations from their own maps. Anyone may view all maps that have been created, but may only "like" a map once logged in. One may not like their own map.

## Screenshots of the Final Product
![Map Book](https://github.com/HaoJiang0201/LHL-P3-Mapbook/blob/master/docs/Map%20Book.jpg?raw=true)



## Getting Started
1. Fork this repository.
2. Install dependencies using `npm install` command.
3. Run migrations: `npm run knex migrate:latest`
  - Check the migrations folder to see what gets created in the DB
4. Run the seed: `npm run knex seed:run`
  - Check the seeds file to see what gets seeded in the DB
5. Run the server: `npm run local`
6. Visit `http://localhost:8080/maps`

## App usage
- Currently, this app has 3 users in the database, without the ability to register a new user
- Once Logged in as a visitor, you may create and like maps as you wish!

## Dependencies

- Node 5.10.x or above
- NPM 3.8.x or above
- Body-parser
- Dotenv
- EJS
- JQuery
- Knex
- Knex-Logger
- PostgreSQL
- Sass
- Morgan
