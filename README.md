# Simple Docker setup to run multiple MySQL servers at dev machine

## How to run all versions at once:

1. Call `docker-compose up -d` to run all servers in the background.
2. Connect to:
    - MySQL v5.7 with username `root` and password `pass` at port `3307`.
    - MySQL v8.0 with username `root` and password `pass` at port `3308`.
    
## How to run single version at once:

1. Call `docker-compose run -d servicename` to run single server in the background.
2. Connect to the server with its respective credentials by following `docker-compose.yml` configuration.
    
### Disclaimer:

This Docker setup is very insecure and should only be used for local development purposes.
