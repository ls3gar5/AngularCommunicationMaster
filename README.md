# AngularCommunicationMaster
Steps to start the migration from Angular 5 to 6

Move to Angular 5 to 6 

npm uninstall -g angular-cli
npm cache verify
npm install -g @angular/cli@6

rm -rf node_modules
npm uninstall --save-dev @angular/cli@6
npm install --save-dev @angular/cli@6
ng update @angular/cli@6
npm i
ng update @angular/core@6 --force
npm install -g rxjs-tslint
npm install rxjs-compat --save-dev

ng build => you´ll see the different error for the beanking change.

Move to 6 to 7
ng update @angular/cli@7 @angular/core@7
