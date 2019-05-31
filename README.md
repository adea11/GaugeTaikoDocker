# Gauge Taiko Docker

This is sample gauge project illustrating gauge + taiko usage in a docker container

## Prerequisite

* docker

## How to run
* Clone the repo
* Build image
    * Run `docker build . -t gauge-taiko`
* Run tests
    * Run `docker run gauge-taiko npm test`

    or to run `gauge` args

    * Run `docker run gauge-taiko npm run gauge -- {args for gauge command}`
