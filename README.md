# babylon-vrm-loader-VR
Base repo is  "https://github.com/virtual-cast/babylon-vrm-loader"

Great thanks for [il-m-yamagishi](https://github.com/il-m-yamagishi).

# Set vrm model

(1) set vrm model in "test/vrm"

(2) modify your code in "src/test/index.ts"

```js
 await SceneLoader.AppendAsync('./vrm/', 'filename.vrm', scene);
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
$ yarn build
```

# run
```bash
$ yarn debug-lan
```

# Reference

### Vita

![vita.jpg](./img/vita.jpg)

https://hub.vroid.com/characters/6193066630030526355/models/3525604181073039892

### Alicia

![alicia.png](./img/alicia.png)

https://3d.nicovideo.jp/works/td32797

