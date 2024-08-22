This is a [Svelte](https://nextjs.org/) project bootstrapped with `npm create svelte@latest my-app`.

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

You can also run the Svelte starter template easily using Wasmer (check out the [install guide](https://docs.wasmer.io/install)):

```bash
npm run build
wasmer run . -- --port 5173
```

Open [http://localhost:5173](http://localhost:5173) with your browser to see the result.

## Deploy on Wasmer Edge

The easiest way to deploy your Svelte app is to use the [Wasmer Edge](https://wasmer.io/products/edge).

Live example: https://wasmer-edge-svelte-sample.wasmer.app/

First, you'll need to run `npm run build`, and then, to deploy to Wasmer Edge:

```bash
wasmer deploy
```
