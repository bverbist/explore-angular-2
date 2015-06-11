# explore-angular-2

## angular 2 quickstart

[https://angular.io/docs/js/latest/quickstart.html](https://angular.io/docs/js/latest/quickstart.html)

### setup

```shell
npm install -g tsd
npm install -g typescript@^1.5.0-beta
npm install -g http-server
```

### run quickstart

dir angular2

```shell
// run TypeScript compiler
tsc --watch -m commonjs -t es5 --emitDecoratorMetadata app.ts

// Creates a server at localhost:8080
http-server
```

visit [http://localhost:8080/index.html](http://localhost:8080/index.html)
