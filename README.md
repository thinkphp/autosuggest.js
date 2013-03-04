# Autosuggest.js

Add autocomplete functionality to input elements.

## API

   var suggest = new Autosuggest(element, [array_of_suggestions])

## Usage

```js

//return an element from id
var $ = function( id ) {return document.getElementById( id ) }

//array of suggestions
var suggestions = ["jquery", "mootools", "dojo", "nodejs", "angularjs", "yui3", "yui2"]

//concatenation with old array
var newS = suggestions.concat(["express"])

//create an autosuggest instance
var suggest = Autosuggest($('input'), newS)

    //change the array of suggestions
    suggest.set(newS.concat(["prototype.js"]))

```

### Demo:

* [http://thinkphp.github.com/autosuggest.js]!

[http://thinkphp.github.com/autosuggest.js]: http://thinkphp.github.com/autosuggest.js
