# Getting started with Angular schematics

This repo contains the scaffolded Angular projects which were part of te Betatalk "Getting started with Angular Schematics, Prt. 1". [Check it out](https://www.youtube.com/watch?v=NDcvAjNz2Qo) 

## You already use schematics

[Angular CLI](https://angular.io/cli)
```
npm install @angular/cli -g
```
GitHub: [@schematics/angular](https://github.com/angular/angular-cli/tree/master/packages/schematics/angular)

### Schematics: 
- #### **Transform** an **in-memory** representation of the file system (Tree). 
- #### Define adaptable functions that return Rule(s).

## lets create schematics

Angular-devkit
``` 
npm install @angular-devkit/schematics-cli -g
```
[Angular Docs](https://angular.io/guide/schematics)

### lets explore hello-world
```
schematics schematic --name=hello-world 
```