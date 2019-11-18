# React-Rails-PostgresQL-boilerplate
A React-Rails-PostgresQL-boilerplate. Uses minitest reporters, and has circleci setup. The database configuration is stored in config/database.yml.ci and config/database.yml has been added to gitignore.

Run a global search for 'my_app' and replace it with the name of your app.

## Getting started

To get started with the app, clone the repo and then install the needed gems:

```
$ bundle install --without production
```

Next, migrate the database:

```
$ rails db:migrate
```

Finally, run the test suite to verify that everything is working correctly:

```
$ rails test
```

If the test suite passes, you'll be ready to run the app in a local server:

```
$ rails server
```
