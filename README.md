#Webpack Little Project

##Pre Requirements

- node.js

##Steps

1. To initialize project run `npm init`
2. Install webpack as new dependency `npm install webpack --save-dev` which will save is in the development environment as webpack is a development tool only
3. The simplest way to start using webpack is to define the script in the `package.json` like follows:
```json
"scripts" {
    "build": "webpack ./src/js/app.js ./dist/bundle.js"
}
```
4. Run `npm run build` to launch the project
5. Add webpack Dev Server for live reloading of application wit the following `npm install webpack-dev-server --save-dev`
6. We can replace the `build` with the following `"build": "webpack-dev-server --entry ./src/js/app.js --output-filename ./dist/bundle.js"`
7. Adding `webpack.config.js` file to configure the entry, output, modules and plugins