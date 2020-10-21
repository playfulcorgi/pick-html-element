# Pick HTML Element

<!-- TODO: pick color different than red, pick if elements underneath can be clicked -->

<!-- FIXME: show a gif of how the script work on a website -->

Creates a JavaScript file generating an interface for picking an HTML element on any website. The file needs to be injected into a website. It's a self-contained solution. It uses a mouse and keyboard for choosing an element on the page. The tool sends out an event when an element is picked so that another script can pick up the collected information and react to it.

This is a building block for applications and not to be used separately.

To test the script on an example website, open `example/index.html` in Google Chrome.

<!-- FIXME: show example website -->

## Development

```shell
npm install
npm run-script build:watch
```

## Production

```shell
npm install
npm run-script build:production
```

## Testing

```shell
npm run-script test
```

## Docker

It's possible to run the development and production commands above inside a Docker container already configured with the right tools. To do so, use a prefix `./bin/exec` before each command. For example, `./bin/exec npm run-script build:watch`.

## Mintenance

The project uses ESLint and Prettier for maintaining a consistent code style across source files. Usually, these tools are picked up by the text editor and used automatically to validate and format code. They can be started manually using NPM commands specified inside package.json in the `scripts` section.
