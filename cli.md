```
ng generate universal --client-project ssr-universal-j-benito
npm install --save @angular/platform-server @nguniversal/module-map-ngfactory-loader @nguniversal/express-engine ts-loader
npm install -D webpack-cli
```

Change angular.json outputDirs?
Lazy Loading enabled? ModuleMapLoaderModule -> app.server.module

npm run build:ssr
npm run serve:ssr
