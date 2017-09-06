# README


* Ruby version: Ruby on Rails tutorial to set up employee database

* System dependencies: sqlite, tutorial gems

* Configuration: tutorial configurations until skeleton is up

* Database: sqlite and node
* 
* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

## SAMPLE APP

This is the initial application for the tutorial to set up the rails server

### Instructions for git

Make your current directory a git repository by running:
`git init`
`git checkout sample_app` or `git checkout -b sample_app`
Using the SSH link you copied in step 7, add the remote repository as the origin:
`git remote add origin git@github.com:yourname/yourrepository.git`
Add your files and commits, as you normally would:
`git add`
`git commit -m "First commit"`
Push your changes:
`git push -u origin master`

### errors: see https://stackoverflow.com/questions/28429819/rejected-master-master-fetch-first

### removes errors but unstable
git push origin sample_app --force
* ...

### to run server
rails server -b $IP -p $PORT

README FILE

### Update Gemfile

# Ruby on Rails Tutorial sample application

This is the sample application for
[*Ruby on Rails Tutorial:
Learn Web Development with Rails*](http://www.railstutorial.org/)
by [Michael Hartl](http://www.michaelhartl.com/).

## License

All source code in the [Ruby on Rails Tutorial](http://railstutorial.org/)
is available jointly under the MIT License and the Beerware License. See
[LICENSE.md](LICENSE.md) for details.

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

For more information, see the
[*Ruby on Rails Tutorial* book](http://www.railstutorial.org/book).