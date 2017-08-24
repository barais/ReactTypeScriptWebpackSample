# Sample of react app with typescript

- Build in following the typescript [documentation](
https://www.typescriptlang.org/docs/handbook/react-&-webpack.html)

- Just add [gulp configuration](https://webpack.github.io/docs/usage-with-gulp.html) and support of [watching function](https://github.com/shama/webpack-stream/issues/18) to automatically recreate bundle.js

- Use [live-server](https://github.com/tapio/live-server) to test the app.

### Test the example.

```bash
npm i #install dependencies
npm i -g gulp
npm i gulp-stream
gulp
```

On another terminal

```bash
npm i -g live-server
live-server --watch=dist/bundle.js
```
