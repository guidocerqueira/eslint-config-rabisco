# Rabisco ESLint config

## Plugins

- Standard config base;
- React plugin;
- React Hooks plugin;
- JSX a11y plugin;
- Prettier;

## Instruções

### React (com Next.js)

Install:
```
npm i -D @rabisco/eslint-config
```
Adiciona em: `.eslintrc.json`
```
{
  "extends": [
    "@rabisco/eslint-config/next", 
    "next/core-web-vitals"
  ]
}
```

### React

Install:
```
npm i -D @rabisco/eslint-config
```
Adiciona em: `.eslintrc.json`
```
{
  "extends": "@rabisco/eslint-config/react"
}
```

### Node.js

Install:
```
npm i -D @rabisco/eslint-config
```
Adiciona em: `.eslintrc.json`
```
{
  "extends": "@rabisco/eslint-config/node"
}
```
