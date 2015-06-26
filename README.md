AngularJS + Browserify sublime snippets
=======================================

There are few sublime filter snippets to generate code ready to work with angular and browserify.

Result code look like this:

```javascript
// index.js
/*
    Module you.app.module
*/
'use strict';

module.exports = angular.module('you.app.module', [

    require('../you.app.module.services'),
])

.factory('DataService', require('./DataService.factory'))
.directive('yourViewData', require('./ViewData.directive'))

.name;
```

How to install
--------------

Go to `Sublime > Preferences > Browse Packages`, and in the packages directory:

```bash
$ git clone https://github.com/drpicox/angularjs-browserify-sublime-snippets.git
```
