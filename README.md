# How to install TypeScript

1. Create a **tsconfig.json** file and paste the following content:<br>
```JavaScript
{
    "compilerOptions": {
      "target": "es5",
  
      "module": "commonjs",
  
      "strict": true,
  
      "esModuleInterop": true,
  
      "forceConsistentCasingInFileNames": true,
  
      "moduleResolution": "node",
  
      "outDir": "dist",
  
      "sourceMap": true
    }
  }
```
2. Now in the terminal:
  - `cd` to your project
  - type `npm install webpack@latest`
  - `npm install -D webpack-cli`
  - `npm run build`
  - `npm run watch`

3. Create **.gitignore** file and type `node_modules`
4. In HTML file, `src` will be `./dist/index.pack.js`
