# AngularCrud

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 10.1.0.

## Development server

Install json-server (https://github.com/typicode/json-server):

```
npm install -g json-server
```

Create a `db.json` file with some data

 ```json
 {  
 	"itens":[  
 	{  
 		"id":1,
 		"nome":"Item 1"
 	},
 	{  
 		"id":2,
 		"nome":"Item 2"
 	}
 	]
 }
 ```
Start JSON Server in back-end folder.

```bash
json-server --watch db.json
```

Now if you go to [http://localhost:3000/itens/1](http://localhost:3000/itens/1), you'll get

```json
{  
    "id":1,
    "nome":"Item 1"
}
```

Then run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

<img src="src/assets/teste1.png" alt="tela 1">
<img src="src/assets/teste2.png" alt="tela 2">
<img src="src/assets/teste3.png" alt="tela 3">
<img src="src/assets/teste4.png" alt="tela 4">

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).
