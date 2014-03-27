ngHammer
========

Angular directives for all touch events handled by hammer.js: http://eightmedia.github.io/hammer.js/

#About

This plugin creates directives for each event handled by hammer.js. Functionality is the same as native angular event directives.

# Usage
Include hammer.js, nghammer.js, and angular.js on your page. Then simply add ```ngHammer``` as a dependcy in your angular module. Then use the directives just like you would ```ng-click="expression"```

``` js
angular.module('myApp', ['ngHammer']);
```

``` html
<div ng-drag="expression" ng-swipeup="expression" ng-tap="expression"></div>
```

