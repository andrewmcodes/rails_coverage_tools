[![Ruby Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://github.com/testdouble/standard)

# README

## Install

### Clone the repository

```shell
git clone git@github.com:andrewmcodes/rails_coverage_tools.git
cd rails_coverage_tools
```

### Dependencies

- Ruby 2.7
- Node 13.7.0
- Rails 6.0.2.1
- Webpacker 4.2.2
- TailwindCSS 1.2.0
- psql (PostgreSQL) 12.1

### Install dependencies

Using [Bundler](https://github.com/bundler/bundler) and [Yarn](https://github.com/yarnpkg/yarn):

```shell
bundle && yarn
```

### Initialize the database

```shell
bin/setup_db
```

## Serve

```shell
rails s
```

If you want to run the webpack-dev-server and livereload, run this in another tab:

```shell
bin/guard
```
