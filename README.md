## How to use this template

- ⚠️ **Don't fork this repository.** Use the "Use this template" green GitHub
  button.
- Put your bindings in `src/ReactNativeXxxxxxxxxx` & rename accordingly or use
  `rescript.json` `"namespace"` field (more on this below),
- Update all occurences of

  - `@rescript-react-native/__template__`
  - `https://github.com/rescript-react-native/__template__`
  - `__template__`
  - `react-native-XXXXXXXXXX`
  - `https://github.com/OWNER/react-native-XXXXXXXXXX`
  - `ReactNativeXxxxxxxxxx`. If you have more than a file exposed, you should
    consider using ReScript custom namespace by adjusting `rescript.json`
    and adding a `"namespace": "react-native-something"` (note that it will be
    converted to `ReactNativeXxxxxxxxxx`)

- Add your `react-native-XXXXXXXXXX` (adjusted) in `peerDependencies`
  & `devDependencies` section
- Adjust the changelog (and/or clean it)
- Remove this part ⬆ & keep everything below ⬇

---

# `@rescript-react-native/__template__`

[![Build Status](https://github.com/rescript-react-native/__template__/workflows/Build/badge.svg)](https://github.com/rescript-react-native/__template__/actions)
[![Version](https://img.shields.io/npm/v/@rescript-react-native/__template__.svg)](https://www.npmjs.com/@rescript-react-native/__template__)
[![ReScript Forum](https://img.shields.io/discourse/posts?color=e6484f&label=ReScript%20Forum&server=https%3A%2F%2Fforum.rescript-lang.org)](https://forum.rescript-lang.org/)

[ReScript](https://rescript-lang.org) bindings for
[`react-native-XXXXXXXXXX`](https://github.com/OWNER/react-native-XXXXXXXXXX).

Exposed as `ReactNativeXxxxxxxxxx` module.

`@rescript-react-native/__template__` X.y.\* means it's compatible with
`react-native-XXXXXXXXXX` X.y.\*

## Installation

When
[`react-native-XXXXXXXXXX`](https://github.com/OWNER/react-native-XXXXXXXXXX)
is properly installed & configured by following their installation instructions,
you can install the bindings:

```console
npm install @rescript-react-native/__template__
# or
yarn add @rescript-react-native/__template__
```

`@rescript-react-native/__template__` should be added to `bs-dependencies` in your
`rescript.json`:

```diff
{
  //...
  "bs-dependencies": [
    "@rescript/react",
    "rescript-react-native",
    // ...
+    "@rescript-react-native/__template__"
  ],
  //...
}
```

## Usage

### Types

#### `ReactNativeXxxxxxxxxx.t`

...

### Methods

#### `ReactNativeXxxxxxxxxx.method`

...

---

## Changelog

Check the [changelog](./CHANGELOG.md) for more informations about recent
releases.

---

## Contribute

Read the
[contribution guidelines](https://github.com/rescript-react-native/.github/blob/master/CONTRIBUTING.md)
before contributing.

## Code of Conduct

We want this community to be friendly and respectful to each other. Please read
[our full code of conduct](https://github.com/rescript-react-native/.github/blob/master/CODE_OF_CONDUCT.md)
so that you can understand what actions will and will not be tolerated.
