# react-redux demo
```配置文件
{
  "name": "react-guide",
  "version": "1.0.0",
  "main": "server.js",
  "scripts": {
    "start": "gulp"
  },
  "author": "konglei <1347271627@qq.com>",
  "license": "ISC",
  "dependencies": {
    "axios": "^0.9.1",
    "express": "^4.13.4",
    "json-server": "^0.8.8",
    "lodash": "^4.6.1",
    "react": "0.14.7",
    "react-dom": "0.14.7",
    "react-redux": "^4.4.1",
    "react-router": "2.0.0",
    "redux": "^3.3.1"
  },
  "devDependencies": {
    "babel-cli": "^6.5.1",
    "babel-core": "^6.5.2",
    "babel-loader": "^6.2.4",
    "babel-polyfill": "^6.9.1",
    "babel-preset-es2015": "^6.5.0",
    "babel-preset-react": "^6.5.0",
    "babel-preset-stage-2": "^6.5.0",
    "del": "^2.2.0",
    "gulp": "^3.9.1",
    "gulp-nodemon": "^2.0.6",
    "gulp-rename": "^1.2.2",
    "webpack": "^1.12.14",
    "webpack-stream": "^3.1.0"
  }
}

```

```sh
# Install Node Modules
npm install

# Start the Server
gulp

# If you want to edit the react code, this rebuilds
gulp watch
```

> The server will be available at localhost:3000

If you want to edit the React code, you'll have to re-build the `public/js/bundle.js` file with Webpack. You'll probably want to open a new terminal tab so you can keep your server running. To rebuild with Webpack, type:

```sh
gulp watch
```

相关总结：
  >http://blog.csdn.net/konglei1996/article/details/51729856
  >http://blog.csdn.net/konglei1996/article/details/51832762
  >http://blog.csdn.net/konglei1996/article/details/51833268

















