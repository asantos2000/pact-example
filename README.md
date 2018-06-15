# pact-example

This is an example application for demonstrating the use of pact and consumer driven contract testing.

The codebase was created for the blogpost [Consumer Driven Contract Testing with Pact](https://blog.risingstack.com/consumer-driven-contract-testing-with-pact/) by [Tamas Kadlecsik](https://blog.risingstack.com/author/tamas-kadlecsik/).

## Usage

Setup

```bash
$ git clone git@github.com:RisingStack/pact-example.git
$ npm i
``` 

Run consumer side tests and create pacts

```bash
$ npm run test-consumer
``` 

Start Pact Broker

```bash
$ npm run pact-broker
```

Delete example pact

```bash
$ npm run delete-example-pact
```

Publish pacts

```bash
$ npm run publish-pacts
```

Verify pacts against the provider 

```bash
$ npm run test-provider
```

## Compatibility

The codebase was tested using `node v10.3.0`