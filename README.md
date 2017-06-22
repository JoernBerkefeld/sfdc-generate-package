# sfdc-generate-package

generate package.xml from source

## Getting Started

Works in Unix like system.
Windows is not tested.

### Installing

```
npm install -g sfdc-generate-package
```

or

```
yarn globally add sfdc-generate-package
```

## Usage

### Command Line

```
$ sgp -h

  Usage: sgp [options]

  generate package.xml from source

  Options:

    -h, --help                   output usage information
    -V, --version                output the version number
    -s, --src                    salesforce src directory path [./src]
    -a, --api-version            salesforce API version [39.0]
    -o, --output                 salesforce package.xml directory path [./src]
```

### Module

```
  var sgp = require('sfdc-generate-package');

  sgp({
    'src':'', // salesforce src directory path : ./src
    '39.0':'', // salesforce API verion : 39.0
    'src':'' // salesforce src directory path : ./src
  }, console.log);
```


## Built With

* [commander](https://github.com/tj/commander.js/) - The complete solution for node.js command-line interfaces, inspired by Ruby's commander.
* [xml2js](https://github.com/Leonidas-from-XIV/node-xml2js) - XML to JavaScript object converter.
* [directory-tree](https://github.com/mihneadb/node-directory-tree) - Creates a JavaScript object representing a directory tree..

## Versioning

[SemVer](http://semver.org/) is used for versioning.

## Authors

* **Sebastien Colladon** - *Initial work* - [scolladon](https://github.com/scolladon)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details