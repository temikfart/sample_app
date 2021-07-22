# Ruby on Rails Tutorial sample application

This is the sample application for
[*Ruby on Rails Tutorial: Learn Web Development with Rails*](https://www.railstutorial.org/)
(6th edition)
by [Michael Hartl](https://www.michaelhartl.com/).

## License

All source code in the [Ruby on Rails Tutorial](https://www.railstutorial.org/)
is available hointly under the MIT License and the Beerware
License. See
[LICENSE.md](LICENSE.md) for details

## Getting started

To get sterted with the app, clone the repo and then itall the needed gems:
```
$ bundle install --without production
```

Next, migrate the database:

```bigquery
$ rails db:migrate
```

Finally, run the test suite to verify that everything is working correctly:

```
$ rails test
```

If the test suite passes, you'll be ready to run the app in a local server:

```bigquery
$ rails server
```

For more information, see the
[*Ruby on Rails Tutorial* book](https://www.railstutorial.org/book).