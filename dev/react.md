# React

## Setting up a new repository

1. Set up the React app with Typescript and Webpack: [tutorial](https://www.smashingmagazine.com/2020/05/typescript-modern-react-projects-webpack-babel/)
2. Install and set up [eslint](https://eslint.org/docs/user-guide/getting-started)
3. Install and set up [prettier](https://prettier.io/docs/en/install.html)
   1. Install and set up [eslint-config-prettier](https://github.com/prettier/eslint-config-prettier#installation)
4. Install and set up [tailwind](https://tailwindcss.com/docs/guides/create-react-app)
   1. Fix for "cannot find module autoprettier" when running `npx tailwindcss init`: [link](https://stackoverflow.com/a/65179433)
   2. Fix for @tailwind css rules getting flagged by vscode as unknown: [link](https://stackoverflow.com/a/61333686)
   3. Fix for type error when running `craco start`: [update node version](https://stackoverflow.com/questions/65247279/typeerror-in-index-css-with-tailwind-and-typescript)
      1. Save required node version to `.nvmrc`: `node --version > .nvmrc`

## React Hooks

- [React Hooks - Observer vs Provider pattern](https://medium.com/javascript-in-plain-english/programming-patterns-with-react-hooks-329c22b96461)

## Testing

- [Common mistakes with React Testing Library](https://kentcdodds.com/blog/common-mistakes-with-react-testing-library)
- [Enzyme - Shallow vs Render vs Mount](https://gist.github.com/fokusferit/e4558d384e4e9cab95d04e5f35d4f913)
- `act()` - wrap around component rendering or updating to ensure DOM is updated before assertions. Allows testing to be closer to browser behaviour.
  - [React `act()` documentation](https://reactjs.org/docs/testing-recipes.html#act)
  - [Examples of when to use `act()`](https://github.com/mrdulin/react-act-examples/blob/master/sync.md)

## Tools

- [Important VS Code extensions for React developers](https://blog.usejournal.com/important-vs-code-extensions-for-react-developers-in-2020-2ca8185eee0a)
- [Setting Up React with Git Hooks to Automatically Test and Lint before Pushing Code](https://dev.to/nas5w/setting-up-react-with-git-hooks-to-automatically-test-and-lint-before-pushing-code-3fp9)
- [Setup ESLint, Prettier & Airbnb Style Guide in under 2 Minutes](https://dev.to/karlhadwen/setup-eslint-prettier-airbnb-style-guide-in-under-2-minutes-a27)
