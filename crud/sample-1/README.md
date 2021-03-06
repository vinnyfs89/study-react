# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## How to

- create a `.env.local` file with the content below:

```environment
REACT_APP_OKTA_CLIENT_ID={clientId}
REACT_APP_OKTA_ORG_URL=https://{yourOktaDomain}
```

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

## References

- [Basic CRUD app - Node + React](https://developer.okta.com/blog/2018/07/10/build-a-basic-crud-app-with-node-and-react)
- [OKTA User management](https://developer.okta.com/product/user-management)
  - Authenticate and authorize your users
  - Store data about your users
  - Perform password-based and social login
  - Secure your application with multi-factor authentication
  - And much more! Check out our product documentation
- [React Router](https://reactrouter.com)
- [Epilogue - Flexible rest endpoints](https://github.com/dchester/epilogue)