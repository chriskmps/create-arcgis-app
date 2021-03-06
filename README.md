# Create ArcGIS App

An example of how to use the ArcGIS platform in an application built with [create-react-app].

![App screenshot](./screenshot.png)

[View it live!](https://create-arcgis-app.surge.sh/)

This application uses [arcgis-rest-js](https://esri.github.io/arcgis-rest-js/) to authenticate users and search for items and the [ArcGIS API for JavaScript](https://developers.arcgis.com/javascript/) (via [esri-loader]) to show the extents of those items on a map.

This is a [React] port of [ambitious-arcgis-app-2018](https://github.com/mjuniper/ambitious-arcgis-app-2018/). See that repository for more information on the motivation behind this application.

See [next-arcgis-app](https://github.com/tomwayson/next-arcgis-app) for a port of the same application built with [Next.js](https://nextjs.org/) instead of create-react-app.

See below for instructions on how to run and modify this application locally after cloning the repository.

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

**NOTE**: in order to see linting rules in your editor, you will need to install eslint globally (i.e. `npm i -g eslint`).

### `yarn test`

Launches the test runner in the interactive watch mode.<br>
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

### `yarn run deploy`

Deploy the built application to https://surge.sh/. You will need to update this script in package.json to point to your own surge domain.

See the section about [deploying to surge](https://facebook.github.io/create-react-app/docs/deployment#surge-https-surgesh) for more information.

### `yarn run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (Webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

### Analyzing the Bundle Size

This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

### Making a Progressive Web App

This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

### Advanced Configuration

This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

### Deployment

This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

### `yarn run build` fails to minify

This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify

[create-react-app]: https://facebook.github.io/create-react-app/
[arcgis]: https://www.arcgis.com/
[esri-loader]: https://github.com/Esri/esri-loader
[react]: https://reactjs.org/
