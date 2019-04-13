[![Build Status](https://travis-ci.org/Abasteca/api.svg?branch=master)](https://travis-ci.org/Abasteca/api)

# Abasteça API

API running on Rails 5.2.3 and Ruby 2.5.3.

#### Setup
To get the API running, follow the steps below:
```shell
bundle install
```

Run `bundle exec figaro install`, copy the content from `config/application.yml.example` file to `config/application.yml` and fill the required data.

After this, execute the following steps:
```shell
rails db:setup
```
Finally, run it:
```shell
rails s
```

#### Tests
To run the test suite, please execute:
```shell
bundle exec rspec
```

#### Static code analysis
To run Rubocop, please execute:
```shell
rubocop -a
```