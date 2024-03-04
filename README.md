# taskify

Task management in Typescript with React.

## Installation

```bash
uid=$(id -u) gid=$(id -g) docker compose run -it npm i
```

## Start server

```bash
uid=$(id -u) gid=$(id -g) docker compose up -d
uid=$(id -u) gid=$(id -g) docker compose exec -it taskify npm run check
```

## Informations

* I followed this tutorial : https://www.youtube.com/watch?v=FJDVKeh7RJI
* This project has been setup with Vite instead of create-react-app.