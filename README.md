<p align="center">
  <a href="https://github.com/abbassiddiqi/react-google-places-autocomplete-next" target="_blank">
    <img width="250"src="https://raw.githubusercontent.com/tintef/react-google-places-autocomplete/master/docs/static/img/logo.svg">
  </a>
</p>

<p align="center">
  <a href="https://www.npmjs.com/package/react-google-places-autocomplete-next">
    <img src="https://img.shields.io/npm/v/react-google-places-autocomplete-next.svg"/>
    <img src="https://img.shields.io/npm/dm/react-google-places-autocomplete-next.svg"/>
  </a>
  <a href="https://github.com/abbassiddiqi/react-google-places-autocomplete-next">
    <img src="https://img.shields.io/github/license/abbassiddiqi/react-google-places-autocomplete-next.svg" alt="License">
  </a>
</p>

# React Google Places Autocomplete Next

React component for easily use Google Places Autocomplete with **React 19 support**.

> This is a fork of [react-google-places-autocomplete](https://github.com/Tintef/react-google-places-autocomplete) with added React 19 compatibility and ongoing maintenance.

## Getting started

Install the latest version:
```sh
npm install --save react-google-places-autocomplete-next
  or
yarn add react-google-places-autocomplete-next
```

Use the component!
```js
import React from 'react';
import GooglePlacesAutocomplete from 'react-google-places-autocomplete-next';

const Component = () => (
  <div>
    <GooglePlacesAutocomplete
      apiKey="****"
    />
  </div>
);

export default Component;
```

## React Version Support

This package supports:
- React 16.8.0+
- React 17.x
- React 18.x
- **React 19.x** ✨

## Documentation

For detailed documentation, please refer to the [original documentation](https://tintef.github.io/react-google-places-autocomplete) as the API remains the same.

## Migration from original package

Simply replace the package name in your imports:

```js
// Before
import GooglePlacesAutocomplete from 'react-google-places-autocomplete';

// After
import GooglePlacesAutocomplete from 'react-google-places-autocomplete-next';
```

## How to contribute?

1. Fork this repo
2. Clone your fork
3. Code 🤓
4. Test your changes

    For this, I like to use [yalc](https://github.com/whitecolor/yalc), as it allows to emulate the process of using npm/yarn.

    1. Install [yalc](https://github.com/whitecolor/yalc)
    2. Build project with `yarn build` or `npm run build`
    3. Publish the package with yalc: `yalc publish`
    4. Add the package to your test project `yalc add react-google-places-autocomplete-next`
    5. If needed, to update the package on your test project: `yalc update react-google-places-autocomplete-next`

5. Submit a PR!

## Credits

This package is based on the excellent work by [Nicolás Tinte](https://github.com/Tintef) in the original [react-google-places-autocomplete](https://github.com/Tintef/react-google-places-autocomplete) package.

<br />
<br />
<p align="center">
  Icons made by <a href="https://www.flaticon.com/authors/freepik" title="Freepik">Freepik</a> from <a href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a>
</p>