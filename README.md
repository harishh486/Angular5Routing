# Angular5routing

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.5.0.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.


## Angular Routing 


Registering the routes in Angular on the RouterModules.


Using router-outlet routing directive instead of selectors(i.e) it may reload the page.


Navigating the paths using router-


Navigating to the paths using navigate methods programmatically.


Unlike the router-link ,navihate method does not know which page it is in or which route we are in currently,where as router-link always know on which component it is sitting on.


Used ActivatedRoute in order to get the currently loaded active route.


Passing & fetching Parameters to /from route dynmically and reactively using snapshot of the router.


Async events using observables which is a third party rxjs package to deal async.


Nested routes using children.


Outsourcing the router config in different module and export them.


Protected the routes/child routes using routing guards with canActivate/canActivateChild route guards.


Controlling Navigation with canDeactivate guard for accidental navigation.


Passing static data to a route.


Resolving Dyn dara with resolve guard which allows us to run some code before it gets routes executed,preloaded info before component is loaded.


Enabling usage of useHash.
