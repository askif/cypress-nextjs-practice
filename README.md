### Configuration Intelligent Code Completion in TypeScript

Choose the pattern you like.

#### 1 spec file,

```js
/// <reference types="Cypress" />
```

#### 2 add a tsconfig.json inside `cypress` folder with the following configuration.

```json
{
  "compilerOptions": {
    "allowJs": true,
    "baseUrl": "../node_modules",
    "types": [
      "cypress"
    ]
  },
  "include": [
    "**/*.*"
  ]
}
```