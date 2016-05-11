<h1 align="center">Yeoman Generator Angular 2 Alfresco Component</h1>
<p align="center">
  <img title="yeoman generator" src='https://github.com/yeoman/media/blob/master/optimized/yeoman-150x150-opaque.png' alt='yeoman logo'  />
</p>
<p align="center">
  <a title='Build Status' href="https://travis-ci.org/Alfresco/generator-ng2-alfresco-component">
    <img src='https://travis-ci.org/Alfresco/generator-ng2-alfresco-component.svg?branch=master' alt='Build Status'  />
  </a>
  <a href='https://coveralls.io/r/Alfresco/generator-ng2-alfresco-component'>
    <img src='https://img.shields.io/coveralls/Alfresco/generator-ng2-alfresco-component.svg' alt='Coverage Status' />
  </a>
  <a href='https://github.com/Alfresco/generator-ng2-alfresco-component/blob/master/LICENSE'>
    <img src='https://img.shields.io/badge/license-MIT-blue.svg' alt='license' />
  </a>
  <a alt='downloads stats' href='https://npmjs.org/package/generator-ng2-alfresco-component'>
    <img src='https://img.shields.io/npm/dm/generator-ng2-alfresco-component.svg' alt='downloads stats' />
  </a>
  <a href="https://nodei.co/npm/generator-ng2-alfresco-component/">
    <img src="http://img.shields.io/npm/v/generator-ng2-alfresco-component.svg" alt='npm version' >
  </a>
</p>

>Yeoman generator generating a Angular2 Alfresco Component scaffold

## Installation and use

First, install [Yeoman](http://yeoman.io) and generator-ng2-alfresco-component using [npm](https://www.npmjs.com/) (we assume you have pre-installed [node.js](https://nodejs.org/)).

```bash
npm install -g yo
npm install -g generator-ng2-alfresco-component
```

##  Generate your new project:

```bash
yo ng2-alfresco-component
```

Which will generate the following project structure:


    ├── .editorconfig
    ├── .gitignore
    ├── tsconfig.json
    ├── tslint.json
    ├── package.json
    ├── typings.json
    ├── LICENSE
    ├── README.md
    ├── my-element.ts
    ├── tests-runner.html
    ├── demo/demo.html
    ├── demo/app/main.ts
    ├── test/my-element-tests.component.ts
    └── src/my-element.component.ts

And run `npm install` for you to fetch all dependencies.

## Develop command list 

* To test your project

    ```sh
    $ npm run test
    ```

* To build the distribution files before releasing a new version.

    ```sh
    $ npm run build
    ```

* To provide a live demo

    ```sh
    $ npm run deploy
    ```
    
## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

## History

For detailed changelog, see [Releases](https://github.com/Alfresco/generator-ng2-alfresco-component/releases).

## Contributors

Contributor | GitHub profile | Twitter profile |
--- | --- | ---
Eugenio Romano (contributor)| [Eugenio Romano](https://github.com/eromano) | [@RomanoEugenio](https://twitter.com/RomanoEugenio)

All contributors [contributors](https://github.com/alfresco/generator-ng2-alfresco-component/graphs/contributors).

## License
[MIT](https://github.com/alfresco/generator-ng2-alfresco-component/blob/master/LICENSE)
 