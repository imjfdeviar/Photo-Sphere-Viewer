# Development

Photo Sphere Viewer is developped in [TypeScript](https://www.typescriptlang.org/) and [SASS](https://sass-lang.com/). 
The repository is a [Turborepo](https://turbo.build/repo) mono-repo containing the code package as well as official adapters and plugins. 
The building process is based on [tsup](https://tsup.egoist.dev/) (toolkit based on esbuild) with a bunch of customizations. 
The documentation is created with [VuePress](https://vuepress.vuejs.org/) and [TypeDoc](https://typedoc.org/). 
Files are linted with [ESLint](https://eslint.org/) and [Stylelint](https://stylelint.io/). 
The (few) unit tests are executed with [Mocha](https://mochajs.org/). 
You will need [Node.js 16](https://nodejs.org/) (VuePress does not work with later versions).

## Commands

* launch the dev server with `npm run serve`
* launch the documentation with `npm run doc:serve`
* register all package for npm link with `npm run npm-link`
* execute the linters with `npm run lint`
* execute the unit tests with `npm run test`
* build all the packages with `npm run build`
* build the documentation with `npm run doc:build`
