# Autosuggest.js

Add autocomplete functionality to input elements.

## Usage

```js

var $ = function( id ) {return document.getElementById( id ) }

var suggestions = ["jquery", "mootools", "dojo", "nodejs", "angularjs", "yui3", "yui2"]

var newS = suggestions.concat(["express"])

var suggest = Autosuggest($('input'), newS)

    suggest.set(newS.concat(["prototype.js"]))

```