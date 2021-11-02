<div align="center">

   <p>
    <h1>formula-parser</h1>
  </p>
  <p>
     A simple and small library to parse your formula and provide output
  </p>
  <p>
     Arithmetic expression to value
  </p>
  <p>A javascript based library</p>

  <p>

  </p>
</div>

---

![GitHub watchers](https://img.shields.io/github/watchers/koustov/formula-parser.svg?logo=github&label=Watch) ![GitHub watchers](https://img.shields.io/github/issues/koustov/formula-parser?logo=github&label=Issues) ![GitHub watchers](https://img.shields.io/github/stars/koustov/formula-parser?logo=github&label=Stars) ![GitHub watchers](https://img.shields.io/npm/dt/formula-parser.svg?logo=npm&label=downloads)

This is a **fully flexible** formula parser based on [`Node`](https://nodejs.org/en/)

**Table of Contents**

- [Features](#features)
- [🤲 Want to Motivate?](#-want-to-motivate)
- [When do you need it](#when-do-you-need-it)
  - [Install 🐙](#install-)
- [Usage](#usage)
- [Highlight 🔥](#highlight-)
- [Available Operators](#available-operators)
- [Items in queue](#items-in-queue)
- [Contribution 🍰](#contribution-)
- [License](#license)


## Features

- Node based
- Simple Javascript methods
- Carefully evaluated priorities
- Appropriate infix/prefix/postfix operations

## 🤲 Want to Motivate?

Who doesn't need motivation? Please give the project a star(⭐) and/or share it in your dev circle.

<!-- ## Many Thanks to all the `Stargazers` who has supported this project with stars(⭐)

[![Stargazers repo roster for @koustov/array-initializer](https://reporoster.com/stars/koustov/array-initializer)](https://github.com/koustov/array-initializer/stargazers) -->

## When do you need it

- Has got complex formula needs to be evaluated?


### Install 🐙

```bash
npm install formula-parser
```

or

```bash
yarn add formula-parser
```

## Usage
```js
import {parseFormula} from 'array-initializer'

// const value = ('Your complex formula');
const value = ('(4*(6)^2)+(2*(123))+243/sin(80)');
```
## Highlight 🔥

It was frustrating for me when I was looking for some easy way to evaluate complex formulae in various part of my application.

## Available Operators

|Operator|Description | Positioning|
|---|---|---|
|+|Addition|prefix|
|-|Subtraction |prefix|
|*+*|Multiplication|prefix|
|/|Division|prefix|
|(|Bracket open|prefix|
|)|Bracket close|postfix|
|,|Coma|infix|
|^|Power|infix|
|!|Factorial|postfix|
|min|Minimum|function|
|sqrt|Square root|function|
|sin|Sin function|prefix|
|cos|Cos function|prefix|

## Items in queue

- Logically endless combinations

## Contribution 🍰

If you understand the importance please feel free to create issue and make pull request

Refer [code of conduct ](./CODE_OF_CONDUCT.md)

Refer [contributing ](./CONTRIBUTING.md)

## License

MIT © [Koustov](https://github.com/koustov)


