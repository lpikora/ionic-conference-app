# Ionic 2 Conference Application with Ionic Debug Console

This repo contains is fork of Ionic 2 Conference Application (https://github.com/driftyco/ionic-conference-app) with integrated Ionic Debug Console.

Look at app/app.ts and app/app.html how to add Ionic Debug Console to your project.

## Installation

Install Node.js (5x with npm3 is better - https://nodejs.org/dist/latest-v5.x/).

Install Ionic 2 (details on http://ionicframework.com/docs/v2/getting-started/installation/):

```bash
$ npm install -g ionic@beta
```

Install dependencies:

```bash
$ npm install
```

Checkout the `typescript` branch

```bash
$ git checkout typescript
```

All integration code is in app/app.ts and app/app.html.

## Development

Run command for test app in browser:

```bash
$ ionic serve
```

## Other repos

### Ionic Debug Console

In-app javascript console for Ionic 2 apps with remote error tracking.

https://github.com/lpikora/ionic-debug-console

### Ionic Debug Console Server

Ionic Debug Console server with REST API for error tracking.

https://github.com/lpikora/ionic-debug-console-backend-api

### Ionic Debug Console Server UI

User interface for Ionic Debug Console Server. Provide managing apps and displaying tracked logs and errors.

https://github.com/lpikora/ionic-debug-console-backend-ui

## License

MIT © [Lukas Pikora](lpikora@gmail.com)
