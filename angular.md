## What is [Angular](https://angular.io/guide/what-is-angular)?
- Angular is a development platform built on [TypeScript](https://www.typescriptlang.org/) (strongly typed Javascript)
- Angular applications make use of ng CLI for managing angular applications, creating components, modules, and more.

| Command | Details |
|- | -|
|**ng build** | Compiles an Angular application into an output directory. |
|**ng serve** | Builds and serves your application, rebuilding on file changes. |
|**ng generate** | Generates or modifies files based on a schematic. |
|**ng test** | Runs unit tests on a given project. |
|**ng e2e** | Builds and serves an Angular application, then runs end-to-end tests. |

## Angular architecture
1. Modules
2. Components
3. Templates
4. Services
5. Metadata
6. Data binding
7. Directives
8. Dependency Injection
   
- **Components** are central to Angular architecture which includes
  - TypeScript class with **@Component** decorator, the Component also includes: An HTML selector, HTML Template using inline HTML or file path to the HTML, optional CSS style file
- **Templates** which is HTML that allows dynamic values via {{ someValueFromTheComponent }}  syntax, it also allows Events via (event)="action()" syntax and Directives
- **Directives** are used in the templates to allow dynamic manipulation of the DOM structure. Common directives are *ngIf and *ngFor; note developers can create custom directives as well.
- **Dependency Injection** lets you declare the dependencies of your TypeScript classes without taking care of their instantiation; Angular handles the instantiation for you.
- This  is done via @Injectable({providedIn:'root'}) format on the Type you wish to inject into another Type using a constructor.
