# react-scripts

This package includes scripts and configuration used by [Create React App](https://github.com/facebook/create-react-app).<br>
Please refer to its documentation:

- [Getting Started](https://facebook.github.io/create-react-app/docs/getting-started) – How to create a new app.
- [User Guide](https://facebook.github.io/create-react-app/) – How to develop apps bootstrapped with Create React App.

# react-scripts-istanbul

This is a custom react-scripts package for loading istanbul plugin. To use this script, run

```
create-react-app --scripts-version react-scripts-istanbul myApp
```

To create an instrumented build

```
react-scripts build --coverage
```

The start command starts webpack-dev-server with instrumentation on.
