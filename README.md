# To Reproduce
1. Run `npm install`
1. add `DISABLE_DB_CONNECTION=true` to your .env file
1. Start a local postgres database (I use postgres.app on mac) and add the connection string in your .env file.
1. Run `npm run build`. The error should appear when the `npm run build:next` command runs
