# API

The API will be here.

Refer to the [Getting Started Guide](https://api-platform.com/docs/distribution) for more information.


# MetaDatApp 

Start the app on local machine with docker compose.

Pre-requisites:
- Docker installed locally
- With command line, go to the repository (where the compose.yaml file is: cd ...)
- do:
```bash
docker compose up -d --wait
```
and, in a  new terminal, to generate the fixtures:  
```bash
docker compose exec php bin/console doctrine:migrations:migrate
docker compose exec php bin/console doctrine:fixtures:load
```
