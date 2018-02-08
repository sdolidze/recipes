# Starting new project

`ng new [project-name] --routing --style=scss`

`ng g module [module-name] --routing`

## Material

`npm i @angular/material @angular/cdk @angular/animations hammerjs`

update `styles.scss` with `@import "~@angular/material/prebuilt-themes/indigo-pink.css";`

update `index.html` with `<link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">`

update `src/main.ts` with `import 'hammerjs';`

add `BrowserAnimationsModule` from `@angular/platform-browser/animations` to `module.ts` imports

## Flex Layout

`npm i @angular/flex-layout`
add `FlexLayoutModule` to `module.ts` imports
