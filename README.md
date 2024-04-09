# Hollama

A minimal web-UI for talking to [Ollama](https://github.com/jmorganca/ollama/) servers.

> ![localhost_5173_iavqp6 (1)](https://github.com/fmaclen/hollama/assets/1434675/8ad2e4d0-94e7-4d9e-ac62-69a05b00a77f)
> ![localhost_5173_iavqp6](https://github.com/fmaclen/hollama/assets/1434675/a4855f22-e927-4926-ba77-676dd6242bd6)


### Features

- Streams responses
- Saves sessions/context in your browser's `localStorage`

## Developing

Create a copy `.env.example`, update the values and save it as `.env`. 

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

To create a production version of your app:

```bash
npm run build
```

You can preview the production build with `npm run preview`.

> To deploy your app, you may need to install an [adapter](https://kit.svelte.dev/docs/adapters) for your target environment.
