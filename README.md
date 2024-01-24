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

Open [http://localhost:5173](http://localhost:5173) with your browser to see the result.

## Deploy on Wasmer Edge

The easiest way to deploy your Svelte app is to use the [Wasmer Edge](https://wasmer.io/products/edge).

Live example: http://wasmer-edge-svelte-sample.wasmer.app/

First, you'll need to run `npm run build`, and then, to deploy to Wasmer Edge:

```bash
wasmer deploy
```

> [!NOTE]
> You will need to have Wasmer installed (check out [the docs to install the Wasmer CLI](https://docs.wasmer.io/install)!). 
> You will also need to change the namespace in `wasmer.toml` to your own namespace and app name in `app.yaml` to your own app name.
