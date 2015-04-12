# yuidoc-dropkick-theme

A simple [YUIDoc](http://yui.github.io/yuidoc/) theme for DropKick.js. This is based (and forked) off of [yuidoc-lucid-theme](http://naturalatlas.github.io/node-gdal/classes/gdal.html).

```sh
$ npm install yuidoc-dropkick-theme --save-dev
```

## Configuration

### Command-Line

When running yuidoc directly from the command line without a configuration file, specify the theme with the following two arguments:

 - `-t` Theme directory
 - `-H` Template helpers

```sh
$ yuidoc -t node_modules/yuidoc-dropkick-theme -H node_modules/yuidoc-bootstrap-theme/helpers/helpers.js
```

### Configuration File

If your project uses a "yuidoc.json" file for configuration, add:

```js
"themedir" : "node_modules/yuidoc-dropkick-theme",
"helpers" : ["node_modules/yuidoc-dropkick-theme/helpers/helpers.js"]
```

Example:

```json
{
    "name": "Example",
    "url": "www.example.com",
    "version": "0.1.0",
    "options": {
        "paths": "_location to parse_",
        "outdir": "build/docs",
        "exclude": "lib,docs,build",
        "themedir": "node_modules/yuidoc-dropkick-theme",
        "helpers": ["node_modules/yuidoc-dropkick-theme/helpers/helpers.js"]
    }
}
```
