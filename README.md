################################## 
################################## 
################################## 
################################## 
################################## 
################################## 

##### Instructions taken from:

https://www.pluralsight.com/guides/export-reactjs-components-as-node-modules-to-npm (for npm.js we can't publish private repositories there though)
( downloaded as pdf in ./create_react_npm_package.pdf )

+https://dev.to/dalenguyen/create-your-first-github-package-564f (for github)



################################## 
################################## 
################################## 
################################## 
################################## 
################################## 
################################## 
################################## 
################################## 
################################## 

#### Example of how to publish your react components as NPM packages in github.

When using your exported react components from other projects, please note:

1. in your package.json: **"@roclas/reactwidgets": "^0.1.2"**, (inside "dependencies": {})
2. **@roclas:registry=https://npm.pkg.github.com** in your .npmrc
3. import { HR } from "@roclas/reactwidgets/**dist/HR**";  (in your js code -App.js for example-)

