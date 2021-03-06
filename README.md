# Records

Description...

[![Build Status](https://travis-ci.org/DigitalState/Records.svg?branch=develop)](https://travis-ci.org/DigitalState/Records)
[![Coverage Status](https://coveralls.io/repos/github/DigitalState/Records/badge.svg?branch=develop)](https://coveralls.io/github/DigitalState/Records?branch=develop)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/DigitalState/Records/badges/quality-score.png?b=develop)](https://scrutinizer-ci.com/g/DigitalState/Records/?branch=develop)

## Table of Contents

- [Synopsis](#synopsis)
- [Installation](#installation)
- [Documentation](#documentation)
- [Contributing](#contributing)
- [History](#history)
- [Credits](#credits)

## Synopsis

Synopsis...

## Installation

Run docker.

```
docker-compose up -d
```

Run database migrations.

```
docker-compose exec php php bin/console doctrine:migrations:migrate
```

Run dev data fixtures (optional).

```
docker-compose exec php php bin/console doctrine:fixtures:load
```

## Documentation

Documentation...

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## History

History..

## Credits

Credits...