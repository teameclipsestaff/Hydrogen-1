# Hydrogen App

Hydrogen is a React framework and SDK that you can use to build fast and dynamic Shopify custom storefronts.

[Check out the docs](https://shopify.dev/custom-storefronts/hydrogen)

## Getting started

## Shopify Connection

Create a variables.js file in the root directory and add below details.

```bash
export const YOUR_STORE_DOMAIN = 'https://your-domain.myshopify.com/';
export const YOUR_STORE_TOKEN = 'your-access-token';
```

**Requirements:**

- Node v14+
- Yarn

```bash
yarn
yarn dev
```

Remember to update `shopify.config.js` with your shop's domain and Storefront API token!

## Building for production

```bash
yarn build
```

Then, you can run a local `server.js` using the production build with:

```bash
yarn serve
```
