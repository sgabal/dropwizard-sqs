# dropwizard-sqs

A [Dropwizard](https://github.com/SmartThingsOSS/dropwizard-common) module for working with Amazon's Simple Queue Service and Simple Notification Service

[![codecov](https://codecov.io/gh/SmartThingsOSS/dropwizard-sqs/branch/master/graph/badge.svg)](https://codecov.io/gh/SmartThingsOSS/dropwizard-sqs)
[![CircleCI](https://circleci.com/gh/SmartThingsOSS/dropwizard-sqs/tree/master.svg?style=svg)](https://circleci.com/gh/SmartThingsOSS/dropwizard-sqs/tree/master)
[ ![Download](https://api.bintray.com/packages/smartthingsoss/maven/smartthings.dropwizard-sqs/images/download.svg) ](https://bintray.com/smartthingsoss/maven/smartthings.dropwizard-sqs/_latestVersion)

## Development

### Running Tests

To execute tests, an instance of [GOAWS](https://github.com/p4tin/goaws) must to be running. This repo bundles 
a Docker compose recipe for that purpose; within the repo root execute:

```
docker-compose up -d
./gradlew check
```
