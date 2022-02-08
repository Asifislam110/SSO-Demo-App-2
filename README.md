# Sample SSO DEMO Application

This sample application is developed to demonstrate SSO using WSO2.

## Table of Contents


### Configure the Sample

Update configuration file `src/config.json` with your registered app details.

**Note:** You will only have to paste in the `client ID` generated for the application you registered.

Read more about the SDK configurations [here](../../README.md#configuration).

```json
{
    "clientID": "<ADD_CLIENT_ID_HERE>",
    "serverOrigin": "https://api.asgardeo.io",
    "signInRedirectURL": "https://localhost:5001/signin/redirect",
    "signOutRedirectURL": "https://localhost:5001"
}
```

### Run the Application

```bash
npm install && npm start
```
The app should open at [`https://localhost:5001`](https://localhost:5001)

## Available Scripts

Install [Angular CLI](https://github.com/angular/angular-cli) globally to use default angular scripts.

```bash
npm install -g @angular/cli
```

### Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:5001/`. The app will automatically reload if you change any of the source files.

### Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

### Lint

Run `ng lint` to lint the project. This app will use [Angular EsLint](https://github.com/angular-eslint/angular-eslint) for this purpose.

### Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.

## Contribute

Please read [Contributing to the Code Base](http://wso2.github.io/) for details on our code of conduct, and the process for submitting pull requests to us.
