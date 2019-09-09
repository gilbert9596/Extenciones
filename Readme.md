# Extenciones

• [AB HTML Formatter](https://marketplace.visualstudio.com/items?itemName=zovorap.ab-html-formatter)

• [Angular Snippets (Version 8)](https://marketplace.visualstudio.com/items?itemName=johnpapa.Angular2)

• [Angular Language Service](https://marketplace.visualstudio.com/items?itemName=Angular.ng-template)

• [Angular2-Inline](https://marketplace.visualstudio.com/items?itemName=natewallace.angular2-inline)

• [Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag)

• [Awesome Flutter Snippets](https://marketplace.visualstudio.com/items?itemName=Nash.awesome-flutter-snippets)

• [Bar Activitus](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.activitusbar)

• [Beautify](https://marketplace.visualstudio.com/items?itemName=HookyQR.beautify)

• [Bracket Pair Colorizer 2](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2)

• [Bootstrap 4, Font awesome 4, Font Awesome 5 Free & Pro snippets](https://marketplace.visualstudio.com/items?itemName=thekalinga.bootstrap4-vscode)

• [Color Highlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight)

• [Dart](https://marketplace.visualstudio.com/items?itemName=Dart-Code.dart-code)

• [ES7 React/Redux/GraphQL/React-Native snippets](https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets)

• [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)

• [Flutter](https://marketplace.visualstudio.com/items?itemName=Dart-Code.flutter)

• [Gist](https://marketplace.visualstudio.com/items?itemName=kenhowardpdx.vscode-gist)

• [Git Extension Pack](https://marketplace.visualstudio.com/items?itemName=donjayamanne.git-extension-pack)

• [HTML Snippets](https://marketplace.visualstudio.com/items?itemName=abusaidm.html-snippets)

• [HTML CSS Support](https://marketplace.visualstudio.com/items?itemName=ecmel.vscode-html-css)

• [Ionic 4 Snippets](https://marketplace.visualstudio.com/items?itemName=fivethree.vscode-ionic-snippets)

• [JavaScript (ES6) code snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets)

• [jshint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.jshint)

• [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)

• [Lorem ipsum](https://marketplace.visualstudio.com/items?itemName=Tyriar.lorem-ipsum)

• [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)

• [Paste JSON as Code](https://marketplace.visualstudio.com/items?itemName=quicktype.quicktype)

• [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

• [Project Manager](https://marketplace.visualstudio.com/items?itemName=alefragnani.project-manager)

• [PWA Tools](https://marketplace.visualstudio.com/items?itemName=johnpapa.pwa-tools)

• [Simple React Snippets](https://marketplace.visualstudio.com/items?itemName=burkeholland.simple-react-snippets)

• [React Native Tools](https://marketplace.visualstudio.com/items?itemName=msjsdiag.vscode-react-native)

• [Terminal](https://marketplace.visualstudio.com/items?itemName=formulahendry.terminal)

• [TODO Highlight](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight)

• [Todo Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)

• [TSLint](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-typescript-tslint-plugin)

• [TypeScript Importer](https://marketplace.visualstudio.com/items?itemName=pmneo.tsimporter)

• [Web Template Studio](https://marketplace.visualstudio.com/items?itemName=WASTeamAccount.WebTemplateStudio-dev-nightly)


## Bracket Pair Colorizer 2 - Mis colores favoritos.

```
"bracket-pair-colorizer-2.colors": [
        "#fafafa",
        "#33F0FF",
        "#58FF33",
        "#FF3333"
    ]
```
## Todo Tree - Para no ver estos archivos.
```
"todo-tree.excludeGlobs": [
        "**/node_modules/**",
        "**/vendor/**",
        "**/bower_components/**",
        "**/dist/**"
    ]
```
## Snippets JS
```
"Mostrar log": {
		"prefix": "clg",
		"body": [
			"console.log(${1:object});", 
			"$2"
		],
		"description": "Mostrar un log en la consola..."

	},

	"Generar clase": {
		"prefix": "clase",
		"body": [
			"export class ${1:NombreClase} {",
			"",
			"   constructor() {",
			"      $2",
			"   }",	
			"}"
		],
		"description": "Para generar la estructura de una clase"

	}
```
