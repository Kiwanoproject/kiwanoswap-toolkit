# 🥞 Kiwanoswap UIkit

[![Version](https://img.shields.io/npm/v/@pancakeswap/uikit)](https://www.npmjs.com/package/@kiwanoswap/uikit) [![Size](https://img.shields.io/bundlephobia/min/@pancakeswap/uikit)](https://www.npmjs.com/package/@kiwanoswap/uikit)

Kiwanoswap UIkit is a set of React components and hooks used to build pages on Kiwanoswap's apps. It also contains a theme file for dark and light mode.

## Install

`yarn add @kiwanoswap/uikit`

***Note**: In case you want to use the older version of the Pancake UIkit, you should install @pancakeswap-libs/uikit, instead, but we recommend using the latest version of the UIkit.*


## Setup

### Theme

Before using Pancake UIkit, you need to provide the theme file to styled-component.

```
import { ThemeProvider } from 'styled-components'
import { light, dark } from '@kiwanoswap/uikit'
...
<ThemeProvider theme={isDark}>...</ThemeProvider>
```

### Reset

A reset CSS is available as a global styled component.

```
import { ResetCSS } from '@kiwanoswap/uikit'
...
<ResetCSS />
```

### Types

This project is built with Typescript and export all the relevant types.

## How to use the UIkit

If you want to use components from the UIkit, check the [Storybook documentation](https://pancakeswap.github.io/pancake-uikit/)
