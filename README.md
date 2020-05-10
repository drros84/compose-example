# compose-example

 Developing know-how and examples building multi-container applications with docker-compose

## Useful documents

* Beginner video YouTube https://www.youtube.com/watch?v=DX1T-PKHKhg
* Docker compose official documentation: https://docs.docker.com/compose/
* Docker compose reference: https://docs.docker.com/compose/compose-file/
* Securing secrets: https://stackoverflow.com/q/37552980

## How to use examples present in this repository?

Each yml file will be stored in the separate folder. Each folder starts with:

01-Example-Description

Several reproducible examples hence to be stored there.

In general, these are the steps to run docker-compose:

1. Navigate to the directory with `cd dirname`
2. Create docker compose file e.g. `touch docker-compose.yml`
3. Edit docker compose file
4. Check docker compose file for errors with `docker-compose config`
5. Execute docker compose file with: `docker-compose up -d`
6. Once required, put down everything with: `docker-compose down`

# Example 01 - YoutubeTutorial

## Purpose

Starts web server

## Details

## How to run

Start up both containers with one line of code: `docker-compose up -d`
Stop them: `docker-compose down`

## How to test

`docker ps`

# Example 02 - Plumber API + ShinyApp

## Purpose

Use compose for images developed in the docker course:

* docker-r-plumber
* shiny-merkle-tree

## Details

## How to run

## How to test

# Example 03

## Purpose

Run trackpack shiny app by launching the docker-compose.yml file 

## Details

Dedicated executable script to launch the app

## How to run

Launch executable files in the folder

## How to test

Once docker compose is launched - navigate to 0.0.0.0 in the browser

# Example 04

## Purpose

Run RStudio (using environmental variables to pass secrets)

## Details

## How to run

Launch executable files in the folder

## How to test

`docker ps` to check that container is working;
navigate to localhost:8787

# Example 05

## Purpose

## Details

## How to run

## How to test

