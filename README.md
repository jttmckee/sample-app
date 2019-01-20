# Ruby on Rails Tutorial sample application
This is the sample application for [*Ruby on Rails Tutorial*](http://www.railstutorial.org/)

## License
All source code in the [Ruby on Rails Tutorial](http://railstutorial.org/) is available jointly under the MIT License and the Beerware License.

##Getting started
To get started with the app, clone the repo and then install the gems:
```
$ bundle install --without production
```

Next, migrate the database:

```
$ rails db:migrate
```

Finally, run the test suite to check everything is working correctly:
```
$ rails test
```
If the test suite passes, the app is ready to run on a local server:
```
$ rails server
```
