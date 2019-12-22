# :space_invader: React Native Web Monorepo

Testing how to share code between React Native & React Native web.

### :star: Features

### Notes

This can be tricky to set up so if there are any errors, there are a couple of things we can check to make sure everything is set up correctly.

- Within the `common` folder's `package.json` file the `main` should point to a file within your build fodler. In this case this is the `dist/index.js` file.
- Within the `common` folder's `tsconfig.json` file,
  - The `jsx` option should be set to `react`
  - The `module` option should be `commonjs`
  - The `declaration` option should be set to `true`

### Configuring React Native For Yarn Workspaces
