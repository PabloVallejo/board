# Board
[![Build Status](https://travis-ci.org/PabloVallejo/board.svg?branch=master)](https://travis-ci.org/PabloVallejo/board)

Simple assignments app

![Board](https://raw.githubusercontent.com/PabloVallejo/board/master/screenshot.png)

### Getting started

Install [Docker](https://www.docker.com/) and build the app.

```bash
$ docker-compose build
$ docker-compose up
```

then open in browser http://localhost:3000

### Running migrations

In order to get the database ready run the following command.

```bash
$ docker-compose run web rails db:migrate
```
