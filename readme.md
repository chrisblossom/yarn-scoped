
```js
➜  yarn-scoped git:(master) ✗ cd yarn-scoped-bin

➜  yarn-scoped-bin git:(master) ✗ rm -rf node_modules

➜  yarn-scoped-bin git:(master) ✗ yarn --version
0.20.3

➜  yarn-scoped-bin git:(master) ✗ yarn
yarn install v0.20.3
[1/4] 🔍  Resolving packages...
[2/4] 🚚  Fetching packages...
[3/4] 🔗  Linking dependencies...
[4/4] 📃  Building fresh packages...
✨  Done in 2.38s.

➜  yarn-scoped-bin git:(master) ✗ ls node_modules/.bin
ls: node_modules/.bin: No such file or directory

➜  yarn-scoped-bin git:(master) ✗ ls node_modules/@chrisblossom/yarn-scoped-pkg/node_modules/.bin
eslint
```

```js
➜  yarn-scoped-bin git:(master) ✗ npm --version
3.10.1

➜  yarn-scoped-bin git:(master) ✗ npm install

➜  yarn-scoped-bin git:(master) ✗ ls node_modules/.bin
acorn      eslint     esparse    esvalidate js-yaml    mkdirp     rimraf     shjs
```