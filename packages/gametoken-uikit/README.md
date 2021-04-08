# 🥞 GameTokenFi UIkit

[![Version](https://img.shields.io/npm/v/@gametoken/uikit)](https://www.npmjs.com/package/@gametoken/uikit) [![Size](https://img.shields.io/bundlephobia/min/@gametoken/uikit)](https://www.npmjs.com/package/@gametoken/uikit)

GameTokenFi UIkit is a set of React components and hooks used to build pages on Pancake's apps. It also contains a theme file for dark and light mode.

## Install

`yarn add @gametoken/uikit`

## Setup

### Theme

Before using GameTokenFi UIkit, you need to provide the theme file to styled-component.

```
import { ThemeProvider } from 'styled-components'
import { light, dark } from '@gametoken/uikit'
...
<ThemeProvider theme={isDark}>...</ThemeProvider>
```

### Reset

A reset CSS is available as a global styled component.

```
import { ResetCSS } from '@gametoken/uikit'
...
<ResetCSS />
```

### Types

This project is built with Typescript and export all the relevant types.

## How to use the UIkit

If you want to use components from the UIkit, please reference the [Storybook documentation](https://pancakeswap.github.io/pancake-uikit/)
