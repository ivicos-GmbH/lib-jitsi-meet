# Jitsi Meet API library

## Notes

The repository has been forked from https://github.com/jitsi/lib-jitsi-meet and adapted to the need for a custom Jitsi Meet implementation. The additional configuration and changes made regarding Ivicos custom Jitsi Meet implementation can be found in USAGE.md. The original documentation from the forked repository is accessible below.

You can use Jitsi Meet API to create Jitsi Meet video conferences with a custom GUI.

## Installation

- [Installation guide](doc/API.md#installation)
- [Checkout the example](doc/example)

## Building the sources

NOTE: you need Node.js >= 12 and npm >= 6

To build the library, just type:
```
npm install
```
To lint:
```
npm run lint
```
and to run unit tests:
```
npm test
```
if you need to rebuild lib-jitsi-meet.min.js

```
npm run postinstall
```

Both linting and units will also be done by a pre-commit hook.
