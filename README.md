# Project 1: Shared shopping list

About the project

This project involves the development of a web-based application designed to offer collaborative shopping lists, enabling simultaneous edits by multiple users. Constructed with Deno, Eta, and PostgreSQL, the application's components are encapsulated within Docker containers for streamlined deployment and operation.


Project structure

The project is structured in a way that the three tier architecture is followed. Eta views, controllers, and services are separated into their own folders. The database connection is also separated into its own folder. The database schemas and migrations are handled by flyway. The e2e tests are located in the e2e-playwright folder.
