[![CircleCI](https://circleci.com/gh/panachainy/ruby-on-rails-101.svg?style=svg)](https://circleci.com/gh/panachainy/ruby-on-rails-101)

# Ruby on rails 101

## Arrange

## Setup machine

[Windows](_note/setup-windows.md)

### Config

```shell
# ~/.bash_profile

# ruby on rails config
eval "$(rbenv init -)"
export WEB_DATABASE_PASSWORD=1234
export DATABASE_URL="postgres://admin:1234@localhost"
```

## Command

Create controller
`rails generate controller Welcome index`

# REF

- https://blog.datawow.io/%E0%B9%80%E0%B8%82%E0%B8%B5%E0%B8%A2%E0%B8%99%E0%B9%80%E0%B8%A7%E0%B9%87%E0%B8%9A%E0%B8%87%E0%B9%88%E0%B8%B2%E0%B8%A2%E0%B9%86%E0%B8%88%E0%B8%B2%E0%B8%81%E0%B8%A8%E0%B8%B9%E0%B8%99%E0%B8%A2%E0%B9%8C%E0%B8%94%E0%B9%89%E0%B8%A7%E0%B8%A2-ruby-on-rails-part-i-840749ecc4e8
- https://blog.datawow.io/part-ii-%E0%B9%80%E0%B8%82%E0%B8%B5%E0%B8%A2%E0%B8%99%E0%B9%80%E0%B8%A7%E0%B9%87%E0%B8%9A%E0%B8%87%E0%B9%88%E0%B8%B2%E0%B8%A2-%E0%B9%86-%E0%B8%88%E0%B8%B2%E0%B8%81%E0%B8%A8%E0%B8%B9%E0%B8%99%E0%B8%A2%E0%B9%8C%E0%B8%94%E0%B9%89%E0%B8%A7%E0%B8%A2-ruby-on-rails-mvc-is-easy-8a8b657ef1ff

---

# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

- Ruby version

- System dependencies

- Configuration

- Database creation

- Database initialization

- How to run the test suite

- Services (job queues, cache servers, search engines, etc.)

- Deployment instructions

- ...
