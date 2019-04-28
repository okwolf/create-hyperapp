# Create Hyperapp

Create Hyperapps with no build configuration.

- [Creating an App](#creating-an-app) – How to create a new app.

Create Hyperapp works on macOS, Windows, and Linux with Node.js >= 8.

## Quick Overview

```sh
npx create-hyperapp my-app
cd my-app
npm start
```

Then open [http://localhost:3000](http://localhost:3000) to see your app.
When you’re ready to deploy to production, create a minified bundle with `npm run build`.

## Creating an App

To create a new app, you may choose one of the following methods:

### npx

```sh
npx create-hyperapp my-app
```

([npx](https://medium.com/@maybekatz/introducing-npx-an-npm-package-runner-55f7d4bd282b) comes with npm 5.2+ and higher.)

### npm

```sh
npm init hyperapp my-app
```

_`npm init <initializer>` is available in npm 6+_

### Yarn

```sh
yarn create hyperapp my-app
```

_`yarn create` is available in Yarn 0.25+_

It will create a directory called `my-app` inside the current folder. Inside that directory, it will generate the initial project structure and install dependencies:

```
my-app
├── README.md
├── node_modules
├── package.json
├── .gitignore
├── public
│   ├── favicon.png
│   ├── index.html
└── src
    ├── App.css
    ├── App.js
    ├── App.test.js
    ├── index.css
    ├── index.js
    ├── logo.svg
```

No configuration or complicated folder structures, just the files you need to build your app. Once the installation is done, you can open your project folder:

```sh
cd my-app
```

Inside the newly created project, you can run some built-in commands:

### `npm start` or `yarn start`

Runs the app in development mode.

Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will automatically reload if you make changes to the code. You will see the build errors and lint warnings in the console.

### `npm test` or `yarn test`

Runs the test watcher in an interactive mode. By default only tests related to files changed since the last commit are run.

[Read more about testing.](https://facebook.github.io/create-react-app/docs/running-tests)

### `npm run build` or `yarn build`

Builds the app for production to the `build` folder. It bundles in production mode and optimizes the build for the best performance. The build is minified and the filenames include unique hashes based on the contents. Your app is ready to be [deployed](https://facebook.github.io/create-react-app/docs/deployment).

## License

Create Hyperapp is MIT licensed. See [LICENSE](LICENSE.md).