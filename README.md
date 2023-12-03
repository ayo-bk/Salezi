[18:59] Ayodélé Bansou kpindé
# Strapi and GraphQL Integration Guide
 
## Strapi Installation
 
- Install Node.js.

- Open the terminal and install Strapi using the command: `npm install strapi@latest -g`.
 
## Creating a Strapi Project
 
- Create a new Strapi project: `npx-create-strapi-app@latest -project-name`.

- Follow the instructions to set up the database and create your first model.
 
## Opening with Visual Studio Code
 
- Open Visual Studio Code.

- Navigate to the created project directory: `cd project-name`.

- Start Strapi in watch mode: `npm run develop`.

- Start Strapi without watch mode: `npm run start`.

- Build Strapi admin panel: `npm run strapi`.

- Display all available commands: `npm run strapi`.
 
## Installation of GraphQL Plugin
 
- Run: `npm run strapi install graphql`.
 
## Using GraphQL in Postman
 
- Launch Postman.

- Create a new GraphQL request.

- Use the request body to send GraphQL queries to your API.
 
## Grafana Installation
 
- Download and install Grafana from [Grafana website](https://grafana.com/get).
 
## Configuration of SQLite Data Source
 
- Open Grafana in your browser.

- Log in and go to "Configuration" -> "Data Sources".

- Add a new SQLite data source.

- Specify the path of the SQLite database to use.
