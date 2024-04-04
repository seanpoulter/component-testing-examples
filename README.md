# WebdriverIO Component Testing Examples [![Test](https://github.com/webdriverio/component-testing-examples/actions/workflows/test.yaml/badge.svg)](https://github.com/webdriverio/component-testing-examples/actions/workflows/test.yaml)

This repository contains several examples for testing web components using WebdriverIO. They are using different frameworks and set-ups and we will continue to add more examples as we improve support for more environments. All examples use WebdriverIO v8 and the `@wdio/browser-runner` to run tests within the browser environment.

Current examples are:

- [`lit-typescript-vite`](https://github.com/webdriverio/component-testing-examples/tree/main/lit-typescript-vite): [Lit](https://lit.dev/) + [TypeScript](https://www.typescriptlang.org/) compiled with [Vite](https://vitejs.dev/)
- [`preact-typescript-vite`](https://github.com/webdriverio/component-testing-examples/tree/main/preact-typescript-vite): [Preact](https://preactjs.com/) + [TypeScript](https://www.typescriptlang.org/) compiled with [Vite](https://vitejs.dev/)
- [`react-typescript-vite`](https://github.com/webdriverio/component-testing-examples/tree/main/react-typescript-vite): [React](https://reactjs.org/) + [TypeScript](https://www.typescriptlang.org/) compiled with [Vite](https://vitejs.dev/)
- [`svelte-typescript-vite`](https://github.com/webdriverio/component-testing-examples/tree/main/svelte-typescript-vite): [Svelte](https://svelte.dev/) + [TypeScript](https://www.typescriptlang.org/) compiled with [Vite](https://vitejs.dev/)
- [`vue-typescript-vite`](https://github.com/webdriverio/component-testing-examples/tree/main/vue-typescript-vite): [Vue.js](https://vuejs.org/) + [TypeScript](https://www.typescriptlang.org/) compiled with [Vite](https://vitejs.dev/)
- [`nuxt`](https://github.com/webdriverio/component-testing-examples/tree/main/nuxt): [Nuxt](https://nuxt.com/)
- [`nextjs`](https://github.com/webdriverio/component-testing-examples/tree/main/nextjs): [Next.js](https://nextjs.org/)
- [`solidjs-typescript-vite`](https://github.com/webdriverio/component-testing-examples/tree/main/solidjs-typescript-vite): [Solid.js](https://www.solidjs.com/) + [TypeScript](https://www.typescriptlang.org/) compiled with [Vite](https://vitejs.dev/)
- [`enhance`](https://github.com/webdriverio/component-testing-examples/tree/main/enhance): [Enhance](https://enhance.dev/docs/)
- [`create-react-app`](https://github.com/webdriverio/component-testing-examples/tree/main/create-react-app): [Create React App](https://create-react-app.dev/)
- [`stencil-component-starter`](https://github.com/webdriverio/component-testing-examples/tree/main/stencil-component-starter): [Stencil Component Starter](https://github.com/ionic-team/stencil-component-starter) using [Stencil](https://stenciljs.com/)
- [`ionic-react`](https://github.com/webdriverio/component-testing-examples/tree/main/ionic-react): [Ionic React Starter](https://ionicframework.com/docs/react) using [Capacitor](https://capacitorjs.com/)

If you are missing an example, feel free to [raise an issue](https://github.com/webdriverio/component-testing-examples/issues/new).

## Usage

You can test component testing with WebdriverIO using the given examples:

1. Switch to the desired example directory

    ```sh
    cd ./<example-directory>
    ```

1. Install dependencies:

    ```sh
    npm install
    ```

1. Run WebdriverIO tests:

    ```sh
    npm run wdio
    ```

## Documentation

For more information on browser and component testing using WebdriverIO, check out the [project docs](https://webdriver.io/).

## Contributing

Contributions to adding more examples or extending existing examples are very welcome. For questions about this topic, feel free to join us on [Discord Support channel](https://discord.webdriver.io) or raise an issue.
