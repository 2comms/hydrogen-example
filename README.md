# Hydrogen

[Hydrogen](https://shopify.dev/custom-storefronts/hydrogen) is a React framework and SDK that you can use to build fast and dynamic Shopify custom storefronts.

## Deploy Your Own

Deploy your own Hydrogen project on 2comms.

[![Deploy with 2comms](https://2comms.com/button)](https://2comms.com/build?repo-url=https://github.com/2comms/templates/hydrogen&template=hydrogen)

_Live Example: https://hydrogen-template.2comms.app_

## Getting started

**Requirements:**

- Node.js version 16.5.0 or higher
- Yarn

To create a new Hydrogen app, run:

```bash
npm init @shopify/hydrogen
```

## Running the dev server

Then `cd` into the new directory and run:

```bash
npm install
npm run dev
```

Remember to update `hydrogen.config.js` with your shop's domain and Storefront API token!

## Building for production

```bash
npm run build
```

## Previewing a production build

To run a local preview of your Hydrogen app in an environment similar to Oxygen, build your Hydrogen app and then run `npm run preview`:

```bash
npm run build
npm run preview
```
