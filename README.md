# Typescript Starter Project
Contains the basic starter code to kick start your typescript project.

## Prerequisites
* Typescript compiler - 
The easiest way to install TypeScript is through npm, the Node.js Package Manager. If you have npm installed, you can install TypeScript globally (-g) on your computer by:
```
npm install -g typescript
```

You can test your install by checking the version or help.
```
tsc --version
```

## Validate Compiler Settings
* tsconfig.json -
Make sure to modify the compilerOptions as per your needs. For more information on Compiler Settings you can look at this [link](https://code.visualstudio.com/docs/typescript/typescript-compiling)

## Compile and Verify
Use these command to just run the compiler or set it to watch the changes:
```
tsc
```

```
tsc --watch or tsc -w
```

The compiled JS would be in the `build/` folder. 

Open the index.html to view the sample HTML page loaded with the compiled JS message.
