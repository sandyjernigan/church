# Church Page

This is a Sample Page. It is a personal page I started to see if my church would like this layout. Anyone that is interested in using this, please message me. I'd be happy to share any layout and design, however content may need permission to be used. 
This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

# Dependencies
## React
### Available Scripts

In the project directory, you can run:

#### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

#### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

#### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

#### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

### Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

#### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

#### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

#### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

#### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

#### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)

## react-dom
https://www.npmjs.com/package/react-dom

```
var React = require('react');
var ReactDOM = require('react-dom');

class MyComponent extends React.Component {
  render() {
    return <div>Hello World</div>;
  }
}

ReactDOM.render(<MyComponent />, node);
```
### API
#### react-dom
- findDOMNode
- render
- unmountComponentAtNode
#### react-dom/server
- renderToString
- renderToStaticMarkup

## react-router-dom
https://www.npmjs.com/package/react-router-dom

### Quick Start Guide
https://reactrouter.com/web/guides/quick-start

```
// using ES6 modules
import { BrowserRouter, Route, Link } from "react-router-dom";
 
// using CommonJS modules
const BrowserRouter = require("react-router-dom").BrowserRouter;
const Route = require("react-router-dom").Route;
const Link = require("react-router-dom").Link;
```
## react-scripts
https://www.npmjs.com/package/react-scripts

https://create-react-app.dev/
## react-universal-hooks
https://www.npmjs.com/package/react-universal-hooks

```
import "react-universal-hooks";
import React from 'react';
import ReactDOM from 'react-dom';
import App from './App';

  ReactDOM.render(
      <App />,
    document.getElementById('root'),
  );
```
### Api Reference
Api Reference are the same as official ones, so you can see api reference @ https://reactjs.org/docs/hooks-reference.html
Currently supported api on Classes Component:

- useState
- useEffect
- useLayoutEffect
- useMemo
- useCallback
- useReducer
- useRef
- useContext
- useImperativeHandle
- useDebugValue

## hooks-for-redux
https://www.npmjs.com/package/hooks-for-redux

## material-ui 
https://material-ui.com/

https://www.npmjs.com/package/@material-ui/core

- @material-ui/core
- @material-ui/icons

```
import React from 'react';
import ReactDOM from 'react-dom';
import Button from '@material-ui/core/Button';

function App() {
  return <Button variant="contained">Hello World</Button>;
}

ReactDOM.render(<App />, document.querySelector('#app'));
```

## @testing-library/jest-dom
https://www.npmjs.com/package/@testing-library/jest-dom

## @testing-library/react
https://www.npmjs.com/package/@testing-library/react
## @testing-library/user-event
https://www.npmjs.com/package/@testing-library/user-event
```
import userEvent from '@testing-library/user-event'
// or
const {default: userEvent} = require('@testing-library/user-event')
```
## @types/react-transition-group
https://www.npmjs.com/package/@types/react-transition-group
### Components
- [Transition](http://reactcommunity.org/react-transition-group/transition)
- [CSSTransition](https://reactcommunity.org/react-transition-group/css-transition)
- [SwitchTransition](https://reactcommunity.org/react-transition-group/switch-transition)
- [TransitionGroup](https://reactcommunity.org/react-transition-group/transition-group)

## bulma
https://bulma.io/

https://www.npmjs.com/package/bulma

```
@import 'bulma/css/bulma.css'
```

https://github.com/aldi/awesome-bulma-templates

## reactbulma
https://github.com/kulakowka/react-bulma

https://kulakowka.github.io/react-bulma/#box

## chalk
https://www.npmjs.com/package/chalk

```
const chalk = require('chalk');
console.log(chalk.blue('Hello world!'));
```

## node-sass
https://www.npmjs.com/package/node-sass

### Usage
```
var sass = require('node-sass');
sass.render({
  file: scss_filename,
  [, options..]
}, function(err, result) { /*...*/ });
// OR
var result = sass.renderSync({
  data: scss_content
  [, options..]
});
```
## web-vitals
https://www.npmjs.com/package/web-vitals

## query-string
https://www.npmjs.com/package/query-string

### Usage
```
const queryString = require('query-string');

console.log(location.search);
//=> '?foo=bar'

const parsed = queryString.parse(location.search);
console.log(parsed);
//=> {foo: 'bar'}

console.log(location.hash);
//=> '#token=bada55cafe'

const parsedHash = queryString.parse(location.hash);
console.log(parsedHash);
//=> {token: 'bada55cafe'}

parsed.foo = 'unicorn';
parsed.ilike = 'pizza';

const stringified = queryString.stringify(parsed);
//=> 'foo=unicorn&ilike=pizza'

location.search = stringified;
// note that `location.search` automatically prepends a question mark
console.log(location.search);
//=> '?foo=unicorn&ilike=pizza'
```

### API
- .parse(string, options?)
- .stringify(object, options?)
- .extract(string)
- .parseUrl(string, options?)
- .stringifyUrl(object, options?)
- .pick(url, keys, options?)
- .pick(url, filter, options?)
- .exclude(url, keys, options?)
- .exclude(url, filter, options?)

## firebase
https://www.npmjs.com/package/firebase

Access Firebase using:
```
var firebase = require('firebase');
var app = firebase.initializeApp({ ... });
```

## analytics 
https://www.npmjs.com/package/analytics

Usage
```
import Analytics from 'analytics'
import googleAnalytics from '@analytics/google-analytics'
import customerIo from '@analytics/customerio'

/* Initialize analytics */
const analytics = Analytics({
  app: 'my-app-name',
  version: 100,
  plugins: [
    googleAnalytics({
      trackingId: 'UA-121991291',
    }),
    customerIo({
      siteId: '123-xyz'
    })
  ]
})

/* Track a page view */
analytics.page()

/* Track a custom event */
analytics.track('userPurchase', {
  price: 20
  item: 'pink socks'
})

/* Identify a visitor */
analytics.identify('user-id-xyz', {
  firstName: 'bill',
  lastName: 'murray',
  email: 'da-coolest@aol.com'
})
```