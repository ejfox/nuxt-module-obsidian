# Nuxt Content: Obsidian

Bringing the magic of Obsidian to publishing with Nuxt Content. Contains a number of helpers and convenience composables to make it easier to pulish Markdown files from Obsidian without losing any functionality.

## Interactive Graph

## Footnotes, backlinks, and wikilinks

## Canvas Support

## Frontmatter / Properties

## Table of Contents

## Obsidian Plugin Support

### Kindle Highlights

## Quick Setup

1. Add `obsidian` dependency to your project

```bash
# Using pnpm
pnpm add -D obsidian

# Using yarn
yarn add --dev obsidian

# Using npm
npm install --save-dev obsidian
```

2. Add `obsidian` to the `modules` section of `nuxt.config.ts`

```js
export default defineNuxtConfig({
  modules: [
    'obsidian'
  ]
})
```

That's it! You can now use Obsidian in your Nuxt app ✨

# Development

```bash
# Install dependencies
npm install

# Generate type stubs
npm run dev:prepare

# Develop with the playground
npm run dev

# Build the playground
npm run dev:build

# Run ESLint
npm run lint

# Run Vitest
npm run test
npm run test:watch

# Release new version
npm run release
```