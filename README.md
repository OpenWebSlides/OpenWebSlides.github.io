# Open Webslides

Open Webslides is an open source platform for teacher-student co-creation.

This is the repository containing the project website.

## Setup

Install RVM and Ruby first

```
$ gem install bundler --no-ri --no-rdoc
$ bundle install
```

## Setup

```
$ rvm install `cat .ruby-version`
$ rvm gemset create `cat .ruby-gemset`
$ rvm use $(cat .ruby-version)-$(cat .ruby-gemset)
$ gem install bundler
$ bundle install
```

## Developing

```
$ middleman server
```

## Building

```
$ middleman build
```
