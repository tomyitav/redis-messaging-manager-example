# redis-messaging-manager-example

## An example for using [redis-mesagging-manager](https://github.com/dotansimha/graphql-code-generator) library.

## Installation

Clone the repository and run `npm install`

```
git clone https://github.com/tomyitav/redis-messaging-manager.git
npm install
tsc
```

### Running receiver

```bash
node dist\receiver.js
```

### Running publisher

```bash
node dist\publisher.js
```

Messages from the publisher will appear in the receiver code.