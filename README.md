# My ESLint config

> Lucas Bruno

## Whats included?

- Standard config base;
- React plugin;
- React Hooks plugin;
- JSX a11y plugin;
- Prettier;

## Setup

### NextJS

Install dependencies:

```
npm i -D eslint @lucasbruno/eslint-config
```

Inside `.eslintrc.json`

```
{
  "extends": [
    "@lucasbruno/eslint-config/next",
    "next/core-web-vitals"
  ]
}
```

### React

Install dependencies:

```
npm i -D eslint @lucasbruno/eslint-config
```

Inside `.eslintrc.json`

```
{
  "extends": "@lucasbruno/eslint-config/react"
}
```

### Node.js (AdonisJS, Nestjs...)

Install dependencies:

```
npm i -D eslint @lucasbruno/eslint-config
```

Inside`.eslintrc.json`, if you have configs, delete all and set something this:

```
{
  "extends": "@lucasbruno/eslint-config/node"
}
```

> Inspired by [Rocketseat](https://github.com/Rocketseat/eslint-config-rocketseat)
