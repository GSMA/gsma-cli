## install
```
git clone git@github.com:GSMA/gsma-cli.git
cd gsma-cli
npm install -g .
```

## usage
Go to the folder where you want to create your plugin, then
```
createPlugin -n <plugin name>
```

more options
```
--no-webpack // disable webpack and karma tests, by default true
--no-test // disable php unit tests, by default true
--react // set up environment for react build and tests, by default false
```

## uninstall
```
npm uninstall -g gsma-cli
```

## third party libraries
- ejs https://ejs.co/
- rimraf https://www.npmjs.com/package/rimraf
- shelljs https://github.com/shelljs/shelljs
- yargs https://github.com/yargs/yargs
