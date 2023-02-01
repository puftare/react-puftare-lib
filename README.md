# react-puftare-lib

Library for making my everyday projects/work much easier! No more rewriting and copy/pasting, just install and reuse wherever you like!

## Instructions..

    1. Initialize project by typing `npm init`
    2. Leave everything on default, for now
    3. Run the following command `npm install react typescript @types/react --save-dev`
        1. Inside your `tsconfig.json` write these rules:
        `
        "jsx": "react",
        "module": "ESNext",
        "declaration": true,
        "declarationDir": "types",
        "sourceMap": true,
        "outDir": "dist",
        "moduleResolution": "node",
        "allowSyntheticDefaultImports": true,
        "emitDeclarationOnly": true
        `
    4. Run the following command `npm install rollup @rollup/plugin-node-resolve @rollup/plugin-commonjs @rollup/plugin-typescript rollup-plugin-dts --save-dev`

### WIP...

1. Button

#### Author

[Puftare][https://github.com/puftare]
