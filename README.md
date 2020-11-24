# README

# rails-docker-boilerplate

This is a `Ruby on Rails / Docker / Github Actions` boilerplate app.

## Features
- Docker Compose
  - web: Ruby 2.7.1 / Ruby on Rails 6.0.3
  - worker: Sidekiq
  - db: MySQL
  - redis: Redis

## Usages

```
$ git clone git@github.com:yassun/rails-docker-boilerplate.git
$ cd rails-docker-boilerplate
$ docker-compose up
$ docker exec -it rails-docker-boilerplate_web_1 bash
$ rails db:create
```
