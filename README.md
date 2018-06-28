# No export duplications

Find duplications of named exports inside JavaScript project.

### Installation

```sh
npm i -g @orisomething/no-export-duplications
```

### Usuage

After installation, when you inside a JavaScript / TypeScript project, just run:

```sh
no-export-duplications
```

You can add path as an argument when you want to check duplications in another project.

### Notes

- Support JavaScript files including Flow (Current compiler `babylon@6.18.0`)
- Support TypeScript files (Current complier is `typescript@2.9.2`)
- List of globs that always ignored:
  - `.test.{js,mjs,ts,tsx}`
  - `.spec.{js,mjs,ts,tsx}`
  - `.d.ts`
  - `.flow`
  - Everything in folders:
    - `node_modules`
    - `flow-typed`
    - `dist`
    - `build`
