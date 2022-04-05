# node-kafka-producer-consumer

A kafka producer/consumer poc using node and kafak can used as message broker in Event Driven architecture to talk between two api's.

## Prerequisites
* `node`
* `docker`

## Running locally

* `npm install` - installs npm dependencies.
* `./scripts/start-kafka.sh` - starts kafka inside docker container.
* `./scripts/create-topic.sh` - creates kafka topic.
* `npm run start:producer` - starts producer.
* `npm run start:consumer` - starts consumer.
