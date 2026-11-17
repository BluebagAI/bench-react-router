> **Benchmark copy.** This repository is an unmodified copy of [remix-run/react-router](https://github.com/remix-run/react-router) at commit [`65a90544aca0d33112d29657c156e766b8481b2d`](https://github.com/remix-run/react-router/commit/65a90544aca0d33112d29657c156e766b8481b2d), used to benchmark CI runners on the project's own Playwright suite. It is not affiliated with or endorsed by the project. The only changes: this note, `.github/workflows/bench.yml` (run by hand only), and the project's other GitHub Actions workflows and Dependabot config removed so nothing runs on its own. The project's license applies (see the license file). Each benchmark run's logs and test results are saved on the [`bench-results`](../../tree/bench-results) branch.

[![npm package][npm-badge]][npm] [![build][build-badge]][build]

[npm-badge]: https://img.shields.io/npm/v/react-router-dom.svg
[npm]: https://www.npmjs.org/package/react-router-dom
[build-badge]: https://img.shields.io/github/actions/workflow/status/remix-run/react-router/test.yml?branch=main&style=square
[build]: https://github.com/remix-run/react-router/actions/workflows/test.yml

React Router is a multi-strategy router for React bridging the gap from React 18 to React 19. You can use it maximally as a React framework or minimally as a library with your own architecture.

- [Getting Started - Framework](https://reactrouter.com/start/framework/installation)
- [Getting Started - Declarative](https://reactrouter.com/start/declarative/installation)
- [Upgrade from v6](https://reactrouter.com/upgrading/v6)
- [Upgrade from Remix](https://reactrouter.com/upgrading/remix)
- [Changelog](https://github.com/remix-run/react-router/blob/main/CHANGELOG.md)

## Packages

- [`react-router`](./packages/react-router)
- [`@react-router/dev`](./packages/react-router-dev)
- [`@react-router/node`](./packages/react-router-node)
- [`@react-router/cloudflare`](./packages/react-router-cloudflare)
- [`@react-router/serve`](./packages/react-router-serve)
- [`@react-router/fs-routes`](./packages/react-router-fs-routes)

## Previous Versions

- [v6](https://reactrouter.com/v6)
- [v5](https://v5.reactrouter.com/)
