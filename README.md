This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

Why use this rather than the official create-react-app:

- This project just uses the official CRA to bootstrap.
- NO eject. Everything is original.
- Just add few more features to make developer life easier.

How to use it?

- Clone or fork this repo instead of `create-react-app blahBlah`
- Then start coding.

But add some additional features to create-react-app:

## Unlock the following features:

In the project directory, you can run:

### Enable the in-IDE ESLint tips

Just add `eslintConfig` to `package.json`

### `yarn update`

It will interactively check the latest version for your packages and let you choose whether to update or not.

It you use `npm` over `yarn`, please run the following command:

```bash
npm uninstall syncyarnlock
npm install --dev npm-check
```

Then replace the `update` script in `package.json` to this: `npm-check -u`

### `yarn inspectBundle`

It will build your production build and analysis your bundle file in a nice way.
