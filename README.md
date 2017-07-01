# ti.transform-example
ti.transform example Alloy project

This project can be used as a Babel/STSS/Pug starter

__Note:__
You need to update `tiapp.xml` with the valid `guid` and `appc-app-id` values before running the project

## Installation
```bash
npm install
```

## Run
### Appcelerator CLI
```bash
appc run -p ios --liveview
```

## Plugins in use
| Plugin | Version | Description |
|--------|---------|-------------|
| [`ti.transform`](https://github.com/vladm3/ti.transform) | [![npm](https://img.shields.io/npm/v/ti.transform.svg)](https://www.npmjs.com/package/ti.transform) | Support plugin |
| [`ti.transform.babel`](https://github.com/vladm3/ti.transform.babel) | [![npm](https://img.shields.io/npm/v/ti.transform.babel.svg)](https://www.npmjs.com/package/ti.transform.babel) | Transforms JS files using [Babel](http://babeljs.io/) |
| [`ti.transform.pug`](https://github.com/vladm3/ti.transform.pug) | [![npm](https://img.shields.io/npm/v/ti.transform.pug.svg)](https://www.npmjs.com/package/ti.transform.pug) | Transforms `*.pug|jade` files using [Pug](https://pugjs.org/) |
| [`ti.transform.stss`](https://github.com/vladm3/ti.transform.stss) | [![npm](https://img.shields.io/npm/v/ti.transform.stss.svg)](https://www.npmjs.com/package/ti.transform.stss) | Transforms style files using [STSS](https://github.com/RonaldTreur/STSS) |


## License
MIT