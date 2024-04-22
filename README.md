# To Reproduce
1. Run `npm install`
1. Use the `.env.example` file to create your own `.env` file, or simply add `DISABLE_DB_CONNECTION=true` to your existing .env file
1. Start a local postgres database (I use `postgres.app` on mac) and add the connection string in your .env file.
1. Run `npm run build`. The error should appear when the `npm run build:next` command runs.
