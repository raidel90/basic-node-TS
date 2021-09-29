
## Install

`npm install`


## compile TS

`npm run tsc`

## run

`npm start`

### comands just in case

`npm install --save-dev typescript`

### problems with TS
To do: `npm run tsc` that (at least on Mac) I had to add the path for the actual compiler within the package, like this


``{
  "name": "foo"
  "scripts": {
    "tsc": "./node_modules/typescript/bin/tsc"
  },
  "dependencies": {
    "typescript": "^2.3.3",
    "typings": "^2.1.1"
  }
}``


### demo capture

![image](capture.png)
