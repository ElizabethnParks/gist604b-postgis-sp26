# [PostGIS Database Orchestration]

**Student:** [Elizabeth Parks]
**Course:** GIST 604B – Open Source GIS
**Module:** [MODULE #4 PostGIS Database Orchestration]
**University of Arizona**

## Project Description
This project focused on building and working woth a PostGIS-enabled PostgreSQL database environment for spatial data analysis using docker. I imported and managed real-world spatial datasets, wrote SQL queries to perform geometry operations, spatial relationships, and multi-table spatial joins across several structured SQL exercises.

## Tools and Technologies
- PostgreSQL with PostGIS
- Docker containers
- SQL functions

## What I Did
- Setup the PostGIS environment.
- Download, unzip, and import data.
- complete and create my own sql, geometry, spatial relationship, and spatial join queries.
- Test queries.

## How to View / Run
- Use docker to setup the database environment.
- Run the sql scripts in the sql/ directory.

## Repository Structure

    .
    ├── README.md
    ├── .devcontainer
    │   ├── devcontainer.json
    │   └── Dockerfile
    ├── sql/
    │   ├── 01_basic_sql_queries.sql
    │   ├── 02_geometry_queries.sql
    │   ├── 03_spatial_relationships.sql
    │   └── 04_spatial_joins.sql
    ├── demos/
    │   ├── demo_aggregation_queries.sql
    │   ├── demo_basic_queries.sql
    │   ├── demo_filtering_queries.sql
    │   └── demo_postgis_queries.sql
    └── docker-compose.yml

## Notes

- demos folder contains sql scripts discussed in the lectures.
- SQL files contain exercises and hints.
- Write and execute queries directly in the `sql/` files using the VS Code PostgreSQL extension.
- Data is downloaded and prepared inside the Codespace environment and is not stored in this repository.
- The database runs in a separate PostGIS container using Docker.
