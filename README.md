# removeduplicatesfromarrayofarrays
The package removes duplicate string values from the array supplied to it and returns the original array with blanks for the duplicates.

Constructor: removeduplicatesfromarrayofarrays

Parameter: Array of arrays

Language: es6

Pre-requisites

1. npm Install babel-core, babel-cli, babel-preset-es2015 as given in the package.json 
2. add .bablerc file to the root of this installation with preset value {"presets": "es2015"}

![Test Result](https://github.com/ravichandranjv/removeduplicatesfromarrayofarrays/blob/master/test-pass.GIF)

usage 
```javascript
    const gen=require('removeduplicatesfromarrayofarrays')
    var arr1=['en','es','en','fr','es','en','en','fr','fr']
    var arr2=['Spectre','Pirates of the Caribbean','Spectre','Avatar','Avatar']
    var arr3=['Sam Worthington','Denzel Washington','Sam Worthington','Sigourney Weaver','Denzel Washington','Sam Worthington']
    var arr5=[]
    arr5.push(arr1)
    arr5.push(arr2)
    arr5.push(arr3)
    var arr4=[]
    var iterable=new gen(arr5)
    for (let x of iterable)
    console.log(x)

```

##Install 
Install with [npm](http://npmjs.com)

```javascript
$ npm intall --save-dev removeduplicatesfromarrayofarrays
```

## Dependency
deduplicatearrayofstrings - v1.0.12

##Author: **Ravichandran JV**
*License: ISC*
