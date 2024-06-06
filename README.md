# React Native WebView

![star this repo](https://img.shields.io/github/stars/react-native-webview/react-native-webview?style=flat-square)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![NPM Version](https://img.shields.io/npm/v/react-native-webview.svg?style=flat-square)](https://www.npmjs.com/package/react-native-webview)
![Npm Downloads](https://img.shields.io/npm/dm/react-native-webview.svg)

**React Native WebView** is a community-maintained WebView component for React Native. It is intended to be a replacement for the built-in WebView (which was [removed from core](https://github.com/react-native-community/discussions-and-proposals/pull/3)).


### Disclaimer

Maintaining WebView is very complex because it is often used for many different use cases (rendering SVGs, PDFs, login flows, and much more). We also support many platforms and both architectures of react-native.

Since WebView was extracted from the React Native core, nearly 500 pull requests have been merged.  
Considering that we have limited time, issues will mostly serve as a discussion place for the community, while **we will prioritize reviewing and merging pull requests.** 

## Platform compatibility

This project is compatible with **iOS**,  **Android**, **Windows** and **macOS**.  
This project supports both **the old** (paper) **and the new architecture** (fabric).  
This project is compatible with [expo](https://docs.expo.dev/versions/latest/sdk/webview/).

### Getting Started

Read our [Getting Started Guide](docs/Getting-Started.md). If any step seems unclear, please create a pull request.

### Versioning

This project follows [semantic versioning](https://semver.org/). We do not hesitate to release breaking changes but they will be in a major version.

### Usage

Import the `WebView` component from `react-native-webview` and use it like so:

```tsx
import React, { Component } from 'react';
import { StyleSheet, Text, View } from 'react-native';
import { WebView } from 'react-native-webview';

// ...
const MyWebComponent = () => {
  return <WebView source={{ uri: 'https://reactnative.dev/' }} style={{ flex: 1 }} />;
}
```

For more, read the [API Reference](./docs/Reference.md) and [Guide](./docs/Guide.md). If you're interested in contributing, check out the [Contributing Guide](./docs/Contributing.md).


# License

MIT

### Translations

This readme is available in:

- [Brazilian portuguese](docs/README.portuguese.md)
- [French](docs/README.french.md)
- [Italian](docs/README.italian.md)
