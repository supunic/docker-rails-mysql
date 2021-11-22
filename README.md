# docker-rails-mysql

## version
- ruby 3.0.2
- rails 6.1.x
- mysql 8.0.19

## setup
```sh
$ docker-compose build
$ docker-compose run web rails webpacker:install
$ docker-compose run web rails db:create
$ docker-compose up -d
```
