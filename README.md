# Customer Trends

You can play with the dashboard on https://customer-behaviour.fly.dev/


## How to run for local development

1. Rename the .envrc-example to .envrc and specify values for environment variables
2. Load environment variables use `direnv allow` in the project's directory
3. Make sure that you have python and poetry installed with `asdf install`
3. Install project dependencies with `make deps`
4. Start PostgreSQL container with `make postgres_up`
5. Migrate database with `make migrate_up`
6. Run tests with `make tests`, run server with `make server`
