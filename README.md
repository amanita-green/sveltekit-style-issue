# Style loading issue with @sveltejs/adapter-node

1. Created app using `npx sv create`, added `router: { resolution: 'server' }` to `svelte.config.js`
2. Made a couple of routes
3. `npm run build`
4. `node build/`
5. Observe that the CSS does not load when going to the routes, refreshing the page makes the styles magically appear.

# sv

Everything you need to build a Svelte project, powered by [`sv`](https://github.com/sveltejs/cli).

## Creating a project

If you're seeing this, you've probably already done this step. Congrats!

```bash
# create a new project in the current directory
npx sv create

# create a new project in my-app
npx sv create my-app
```

## Developing

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

> To deploy your app, you may need to install an [adapter](https://svelte.dev/docs/kit/adapters) for your target environment.
