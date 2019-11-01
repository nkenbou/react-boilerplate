# Bolierplate for React projects

An simple webpack boilerplate for React projects **witout** react-create-app.

## Features

- Transpiling ES201x and JSX via Babel.
- Generating an HTML file for webpack bundles that include a hash in the filename.
- Formatting with Prettier.
- Linting with ESLint.

## Usage

- `yarn build` - Build app for developement.
- `NODE_ENV=production yarn build` - Build app for production.
- `yarn start` - Start webpack-dev-server for developement.
- `yarn eslint` - Lint files with ESLint.
- `yarn eslint-check` - Check if your configuration contains any rules that are unnecessary or conflict with Prettier.
