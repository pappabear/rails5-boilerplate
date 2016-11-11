# Rails 5 Boilerplate

This is the dockerized reference implementation of the sample application for the 4th edition of [*Ruby on Rails Tutorial: Learn Web Development with Rails*](http://www.railstutorial.org/) by [Michael Hartl](http://www.michaelhartl.com/).

## License

All source code in the [Ruby on Rails Tutorial](http://railstutorial.org/) is available jointly under the MIT License and the Beerware License. See [LICENSE.md](LICENSE.md) for details.

## Running in a Docker container

Build the containers from the project images:

```
$ docker-compose build
```

Start the container:

```
$ docker-compose up 
```

The container will launch a script named _machine_start.rb_ that will perform the database migrations, seed the database, and launch the Puma server.

Shut down the container:

```
$ docker-compose down
```

 
## Running the app on localhost

If you want to run this locally:

```
$ rails db:migrate
```

Run the test suite to verify that everything is working correctly:

```
$ rails test
```

Run the app in a local server:

```
$ rails server
```

