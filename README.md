# Simple Website with NGINX & Docker

This is a simple repo with a static website in a docker container.  Useful for quick local hacks.


## Usage
Put static files in the \static directory in this folder
Static css and js files can be put in the associated web\js and web\css folders

Note that by defauly boostrap5 and bitwrench are included in the js and css folders

To serve the application type

```bash
docker compose up --build

```

