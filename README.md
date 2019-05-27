# babylon-vrm-loader-VR
Base repo is  "https://github.com/virtual-cast/babylon-vrm-loader"

Great thanks for [il-m-yamagishi](https://github.com/il-m-yamagishi).

# Set vrm model

(1) set vrm model in "./vrm"

(2) modify your code in "src/test/index.ts"

```js
 await SceneLoader.AppendAsync('./', 'filename.vrm', scene);
```

# build

```bash 
$ npm install --save-dev ts-loader
$ npm install --save-dev typescript  
$ npm install --save-dev ts-lib
$ npm install --save-dev @babylonjs/core
$ npm install --save-dev @babylonjs/loaders
$ npm install --save-dev @babylonjs/inspector
$ npm install --save-dev babylon-mtoon-material 
$ npm install --save-dev webpack-dev-server
$ npm install --save-dev webpack 
$ npm install --save-dev webpack-cli
```

# run
```bash
$ yarn debug-lan
```