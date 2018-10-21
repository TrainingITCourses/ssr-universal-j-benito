```
  npm install @ngrx/schematics --save-dev
  npm install @ngrx/store --save
  npm install @ngrx/store-devtools --save
  ng config cli.defaultCollection @ngrx/schematics
  ng g st State --root -m app.module.ts --spec false
  cd .\src\app\reducers\
  ng g r Car --spec false -r index.ts
  ng g a Car --spec false
  npm install @ngrx/effects --save
  ng g ef Car --root -m ../app.module.ts --spec false
```;
