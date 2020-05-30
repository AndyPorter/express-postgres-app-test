# express-postgres-app-test

## aim
build a node-express, app, connected to postgres, running on heroku.

using https://www.taniarascia.com/node-express-postgresql-heroku/ - api served up by express from postgres - to build the postgress connection,  will roll my own node frontend - probably using nunjucks or EJS.

## todo
all of it :)

- first build the example in https://www.taniarascia.com/node-express-postgresql-heroku/  - just do the local express server with postgres
- then build simple front end
- extend the DB to do as bit more than one or two fields?
- deploy to heroku
- improve the thing

## in progress
tutorial, as far as local express server with postgres - from https://www.taniarascia.com/node-express-postgresql-heroku/

## done

- install postgres
- create db user for app, and log in as user
- create books table and add a book from command line
- install npm module pg



## usefull notes:

- brew services start postgresql (to start postgres service running in background)
- brew services stop postgresql (stop postgress service)
- npm start (start server/app)
- curl http://localhost:3002/books (tests the db - should return the books from the db)
