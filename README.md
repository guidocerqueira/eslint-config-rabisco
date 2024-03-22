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
npm i -D eslint @guidocerqueira/eslint-config
```
Adiciona em: `.eslintrc.json`
```
{
  "extends": [
    "@guidocerqueira/eslint-config/next", 
    "next/core-web-vitals"
  ]
}
```

### React

Install:
```
npm i -D eslint @guidocerqueira/eslint-config
```
Adiciona em: `.eslintrc.json`
```
{
  "extends": "@guidocerqueira/eslint-config/react"
}
```

### Node.js

Install:
```
npm i -D eslint @guidocerqueira/eslint-config
```
Adiciona em: `.eslintrc.json`
```
{
  "extends": "@guidocerqueira/eslint-config/node"
}
```
