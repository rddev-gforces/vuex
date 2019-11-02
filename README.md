# vuex-cognito-module

Vuex module to interface with AWS Cognito

Docs Link: [https://cognito.vuetifyjs.com/](https://cognito.vuetifyjs.com/)

Install (Forked Version containing ie11 fix):
```bash
npm install https://github.com/rddev-gforces/vuex.git --save
```

Import into your project's entry point (main.js in most Vue projects)
```js
import attachCognitoModule from '@vuetify/vuex-cognito-module';
```

Attach cognito module to the store
```js
import store from './store';
attachCognitoModule(store, {
  userPoolId: 'your-data-here',
  identityPoolId: 'your-data-here',
  userPoolWebClientId: 'your-data-here',
  region: 'your-data-here',
}, 'cognito')
```
