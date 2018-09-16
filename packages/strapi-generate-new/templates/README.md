# <%= name %>

A quick description of <%= name %>.

### Setup

Setup:
```
npm run setup
```

Running the application in development mode:
```
npm run start
```

Running in production mode:
```
DATABASE_PORT=5433 DATABASE_NAME='postgres' DATABASE_USERNAME=<DB_USER> DATABASE_PASSWORD=<DB_PASS> NODE_ENV=production npm start
```

### Usage in Development

The admin panel is located at localhost:1337/admin in development mode.

The index.html for localhost:1337 is in public/index.html.

You can use the cli to create an api as well, or in development mode you can use the admin page's Content Manager
```
strapi generate:api <apiName>
```

After setup, make sure that the graphql plugin is enabled and go to localhost:1337/playground to see graphiql test playground.

### Resources

[Documentation](http://strapi.io/documentation/introduction)
[Repository on GitHub](https://github.com/strapi/strapi)
[News on Twitter](https://twitter.com/strapijs)
[Real-time support on Slack](http://slack.strapi.io/)
