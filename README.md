# ⚡ vite-react-ts-tailwind-starter ⚡

Starter using Vite + React + TypeScript + Tailwind.

## Motivation

Enhance the efficiency of developing your prototypes quicker by leveraging Vite, TypeScript, React, and TailwindCSS.

This starter kit employs the following libraries:

- Vite
- React
  - React Router
- TypeScript
- Tailwind CSS
- ESLint
- Prettier

## Set up

```shell
npm install
npm run dev
```

## Vite

The [Vite](https://github.com/vitejs/vite) tool is designed for efficient frontend development. Its [README](https://github.com/vitejs/vite/blob/main/README.md) outlines two main components:

1.  A development server that uses native ES modules to serve source files. It comes equipped with advanced built-in functionalities and boasts an impressive Hot Module Replacement (HMR) feature that operates at lightning-fast speeds.

2.  A build command that utilizes Rollup to bundle code and generate optimized static assets for production purposes. The tool is pre-configured to ensure maximum optimization.

## React

[React](https://github.com/facebook/react) is a JavaScript library for building user interfaces.

## TypeScript

[TypeScript](https://github.com/microsoft/TypeScript) is a superset of JavaScript. It is just one of NPM library, but it provides an original compiler.

When you use TypeScript with React, you can write JSX with TypeScript, called TSX. Then you can develop views written by **Type-Safe** template.

## Tailwind CSS

[Tailwind CSS](https://tailwindcss.com/) is a modern CSS framework that utilizes utility-first principles. It offers a comprehensive set of CSS rules, but these are purged during production builds, which means that developers need not concern themselves with CSS asset sizes for performance optimization.

For developers using Visual Studio Code, it is recommended to use the [intellisense extension](https://tailwindcss.com/docs/intellisense).

When working with React, developers often struggle with deciding how to write CSS in TSX(JSX) templates. They may consider options such as CSS Modules, [styled-components](https://styled-components.com/), [linaria](https://github.com/callstack/linaria), and more. Additionally, CSS architecture can be difficult to manage, such as with scoping methods like [BEM](https://getbem.com/) or [FLOCSS](https://github.com/hiloki/flocss/blob/master/README_eng.md).

However, when utilizing Tailwind CSS, developers only need to write utility-first CSS classes and need not worry about the other concerns mentioned above.

## Formatter and Linter

Please read: https://prettier.io/docs/en/integrating-with-linters.html.

[ESLint](https://eslint.org/) and [Prettier](https://prettier.io/) have already been installed and set up, and users are able to customize the rules as needed.

Please note that the starter does not currently utilize [eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) and [prettier-eslint](https://github.com/prettier/prettier-eslint). As a result, it is recommended that users run commands individually, such as `prettier && eslint`.

For further information, please refer to: [https://prettier.io/docs/en/integrating-with-linters.html](https://prettier.io/docs/en/integrating-with-linters.html).
