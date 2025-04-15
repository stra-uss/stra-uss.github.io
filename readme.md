

### Build only Windows Operation System

#### - Node installer
```
node-v18.20.4-x64.msi
```

#### - Node version
```
D:\DEV\stss.dev\gitpages-template-model>npm -version
10.7.0
```


#### Node buid
```
D:\DEV\stss.dev\gitpages-template-model>npm run build

> STSSPortfolio@0.1.0 build
> react-scripts --openssl-legacy-provider build

Creating an optimized production build...
Browserslist: caniuse-lite is outdated. Please run:
  npx update-browserslist-db@latest
  Why you should do it regularly: https://github.com/browserslist/update-db#readme
Compiled successfully.

File sizes after gzip:

  181.68 KB (+2 B)      build\static\js\2.7289aa8a.chunk.js
  164.18 KB (+1.26 KB)  build\static\js\main.9c3edc56.chunk.js
  17.14 KB              build\static\css\main.37f7feb6.chunk.css
  781 B                 build\static\js\runtime-main.58b5d89d.js

The project was built assuming it is hosted at https://stra-uss.github.io.
You can control this with the homepage field in your package.json.

The build folder is ready to be deployed.
You may serve it with a static server:

  npm install -g serve
  serve -s build

Find out more about deployment here:

  https://bit.ly/CRA-deploy
```


#### Node run
```
npm start
```



#### Build

 - Empty local repository
```
git clone https://github.com/stra-uss/stra-uss.github.io.git
```
 - Source Code on Local repositoty
```
git pull
git push
```
