# Algolia Shopify integration

Build Search and Discovery experience with Algolia, a Shopify Plus Certified Partner
Hydrogen is a React framework and SDK that you can use to build fast and dynamic Shopify custom storefronts.

# Remix App with Algollia
Build with React InstantSearch Hooks?
[Guide] https://www.algolia.com/doc/guides/building-search-ui/what-is-instantsearch/react-hooks/

## Configuration for Hydrogen & Algolia
- Algolia

Update `algolia.config.json` with your Algolia APP ID & API KEY. 

Update `algolia.config.json` with your shopify integration prefix ("shopify_" for example) and query sugguestion index name.

- Hydrogen

Update `hydrogen.config.js` with your shop's domain and Storefront API token.

## What's in this template

- Algolia InstantSearch & Autocomplete libraries
- Styling with [Tailwind](https://tailwindcss.com/)
- End-to-end testing with [Playwright](https://playwright.dev)
- Unit testing with [Vitest](https://vitest.dev) and [Testing Library](https://testing-library.com)
- Code formatting with [Prettier](https://prettier.io)
- Javascript linting with [ESLint](https://eslint.org) and the Hydrogen [ESLint plugin](https://github.com/Shopify/hydrogen/tree/main/packages/eslint-plugin)

## Getting started

**Requirements:**

- Node.js version 16.5.0 or higher
- Yarn

```bash
yarn
yarn dev
```

## Previewing a production build

To run a local preview of your Hydrogen app in an environment similar to Oxygen, build your Hydrogen app and then run `yarn preview`:

```bash
yarn build
yarn preview
```
