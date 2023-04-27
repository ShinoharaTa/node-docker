# Docker Node Template

Use Node.js version: v18

## How to use

Clone or Copy "./app" directory in your Project folder.

```bash
touch ./app/project
cd ./app/project/
```

### Build docker dontaienr

```bash
docker compose build --no-cache
```

### Up to docker container

```bash
docker compose up -d
```

### Shell in docker contaienr

```bash
docker compose exec node bash
```

### End of docker contaienr

```bash
docker compose down
```
