This project is a React template with the following features:

- [Vite](https://vitejs.dev/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Material UI](https://mui.com/)
- [ESLint](https://eslint.org/)
- [Prettier](https://prettier.io/)

## Scripts

- `pnpm dev` - run development server
- `pnpm build` - build for production
- `pnpm preview` - preview production build
- `pnpm prettier` - format code with Prettier
- `pnpm lint` - lint code with ESLint
- `pnpm lint:fix` - lint code with ESLint and fix errors

### Combining ESLint and Prettier

To combine ESLint and Prettier, you can use two packages:

- `eslint-config-prettier`: This package disables all ESLint rules that may conflict with Prettier.
- `eslint-plugin-prettier`: This package integrates the Prettier rules into the ESLint rules.


### About `plugin:react/jsx-runtime`

> If you are using the new JSX transform from React 17, extend react/jsx-runtime in your eslint config (add "plugin:react/jsx-runtime" to "extends") to disable the relevant rules.

https://github.com/jsx-eslint/eslint-plugin-react#configuration-legacy-eslintrc

## References

- [MUI installation](https://mui.com/material-ui/getting-started/installation/)
- [Tailwind installation](https://tailwindcss.com/docs/guides/vite)
- [ESLint installation](https://eslint.org/docs/latest/use/getting-started)
- [Prettier installation](https://prettier.io/docs/en/install.html)
- [Bing chat](https://www.bing.com/new)