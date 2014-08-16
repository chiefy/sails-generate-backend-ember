![image_squidhome@2x.png](http://i.imgur.com/RIvu9.png)

# sails-generate-backend-ember


A `backend` generator for use with the Sails command-line interface.


### Installation

Certain generators are installed by default in Sails, but they can be overridden.  Check the [Sails docs](http://sailsjs.org/#!documentation) for information on installing generator overrides / custom generators.

<!--
```sh
$ npm install sails-generate-backend-ember
```
-->


### Production Usage

##### On the command line

```sh
$ sails generate backend 
```

##### In a node script

```javascript
var path = require('path');
var sailsgen = require('sails-generate');
var scope = {
	rootPath: path.resolve(__dirname)
};
sailsgen(require('sails-generate-backend'), scope, function (err) {
	if (err) throw err;

	// It worked.
});
```
