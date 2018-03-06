# react-native-ssb-shims

Node.js-related shims necessary for the SSB ecosystem to run on React Native apps.

## usage

First link all deps.

```js
react-native link react-native-randombytes && react-native link react-native-crypto && react-native link react-native-fs && react-native link react-native-os && react-native link react-native-tcp
```

Just import it in your project's index.js:

```js
require('react-native-ssb-shims');
```

### Note
Mac users: in order to get the post-install scripts to run, you will first need to install `coreutils` through homebrew
```brew install coreutils```
