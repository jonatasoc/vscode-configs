# :computer: VS Code Configurations

Repo to join my personal Visual Studio Code configuration, such as ESLint, Prettier, TypeScript, etc.

Also to put together the commons scripts and devDependencies of ***package.json*** files.

# React Configs



# Node Configs (with Typescript)

## **package.json**

### scripts

```
  "scripts": {
    "build": "tsc",
    "dev:server": "ts-node-dev --inspect --transpile-only --ignore-watch node_modules src/server.ts",
  },
```

### devDependencies

```
  "devDependencies": {
    "@types/express": "^4.17.9",
    "@types/morgan": "^1.9.2",
    "@typescript-eslint/eslint-plugin": "^4.7.0",
    "@typescript-eslint/parser": "^4.7.0",
    "eslint": "^7.13.0",
    "eslint-config-airbnb-base": "^14.2.1",
    "eslint-plugin-import": "^2.21.2",
    "ts-node-dev": "^1.0.0",
    "typescript": "^4.0.5"
  },
```
