# Medusa Marketplace
A multivendor marketplace implementation using [Medusa 2.0](https://medusajs.com/)


### Installation

1. Run PostgreSQL (optional)

Start the `PostgreSQL` container:

```
docker compose up -d
```


2. Run Medusa app

```bash
cd marketplace
yarn
cp .env.example .env
npx medusa db:setup --db marketplace
yarn dev
```

The Medusa dashboard should now be running on http://localhost:9000/app
