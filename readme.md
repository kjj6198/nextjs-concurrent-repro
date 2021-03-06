example copied from [next.js environment variables example](https://github.com/vercel/next.js/tree/canary/examples/environment-variables)
# Reproduce

1. `npm install`
2. `npm run dev`
3. Access `http://localhost:3000`
4. The `ENV_VARIABLE` and `ENV_LOCAL_VARIABLE` are undefined
5. Remove `concurrentFeatures: true` in `next.config.js`
6. restart the dev server, now the `ENV_VARIABLE` and `ENV_LOCAL_VARIABLE` are loaded.


# Environment Variables Example

This example shows how to use [environment variables in Next.js](https://nextjs.org/docs/basic-features/environment-variables).

The index page ([pages/index.js](pages/index.js)) will show you how to [access environment variables in the server](https://nextjs.org/docs/basic-features/environment-variables#loading-environment-variables), and how to [expose environment variables to the browser](https://nextjs.org/docs/basic-features/environment-variables#exposing-environment-variables-to-the-browser).

## Preview

Preview the example live on [StackBlitz](http://stackblitz.com/):

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/vercel/next.js/tree/canary/examples/environment-variables)

## Deploy your own

Deploy the example using [Vercel](https://vercel.com?utm_source=github&utm_medium=readme&utm_campaign=next-example):

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/git/external?repository-url=https://github.com/vercel/next.js/tree/canary/examples/environment-variables&project-name=environment-variables&repository-name=environment-variables)

## How to use

Execute [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app) with [npm](https://docs.npmjs.com/cli/init) or [Yarn](https://yarnpkg.com/lang/en/docs/cli/create/) to bootstrap the example:

```bash
npx create-next-app --example environment-variables environment-variables-app
# or
yarn create next-app --example environment-variables environment-variables-app
```

Deploy it to the cloud with [Vercel](https://vercel.com/new?utm_source=github&utm_medium=readme&utm_campaign=next-example) ([Documentation](https://nextjs.org/docs/deployment)).
