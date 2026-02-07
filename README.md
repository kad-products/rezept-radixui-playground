# Rezept Radix UI Playground

This is a quick [Storybook](https://storybook.js.org/) site to play around within [Radix UI](https://radix-ui.com/) for the design system for [Rezept](https://github.com/kad-products/rezept-core).

## Published Playground

Visit the published site at https://kad-products.github.io/rezept-radixui-playground/.  This is built by CI in GitHub Actions upon merge to `main`.

## Development

1. Clone this site down
2. Run `pnpm install` to install dependencies
3. Run `pnpm dev` to run the storybook locally
4. Visit `http://localhost:6006` to see the site

Changes made should refresh the site automatically.

## Components

The files in `/src/*` are the components we are playing with.  Within each directory is a set of files that represents the componet:

- `<component-name>.module.css` is the CSS module for that component
- `<component-name>.story.tsx` is the Storybook file for that component defining how things should render on the Storybook site
- `<component-name>.test.tsx` is unit tests for that component
- `<component-name>.tsx` is the actual component