## Dev

1. Clone repo
2. Create .env base on .env.example
3. Run `git submodule update --init --recursive` to rebuild submodules
4. Run `docker compose up --build`

## Prod

1. Clone repo
2. Create .env base on .env.example
3. Run `docker compose -f docker-compose.prod.yml build`
