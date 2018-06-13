# Clubhouse App

A basic web application for members of the clubhouse to write nasty posts
about non-members. Members will be able to view the author of the post but 
non-members won't. This is a project that is part of (The Odin Project)[https://www.theodinproject.com/lessons/authentication]
curriculum.

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
