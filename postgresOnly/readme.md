# Setup

## Env

Edit `.env` file

## Start

Run command `docker-compose up -d --build`

## PgAdmin

Open localhost:5050

Login with PGADMIN_DEFAULT credentials

Servers > Create server

General > Name > `mydb`  
Connection > Host > `srv_pg`  
Connection > Port > `${POSTGRES_PORT}`  
Connection > Username > `${POSTGRES_USER}`  
Connection > Password > `${POSTGRES_PASSWORD}`
