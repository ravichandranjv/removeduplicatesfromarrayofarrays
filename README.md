# removeduplicatesfromarrayofarrays
The package removes duplicate string values from the array of arrays supplied to it.

Constructor: removeduplicatesfromarrayofarrays

Parameter: Array of arrays

Language: es6

Pre-requisites

1. npm Install babel-core, babel-cli, babel-preset-es2015 as given in the package.json 
2. add .bablerc file to the root of this installation with preset value {"presets": "es2015"}

##Install 
Install with [npm](http://npmjs.com)

v1.0.5 is @unmerged  
v1.0.6 is @merged
@latest is v1.0.5 ie.returns unmerged arrays as supplied to th library

```javascript
$ npm install --save-dev removeduplicatesfromarrayofarrays@unmerged
$ npm install --save-dev removeduplicatesfromarrayofarrays@merged
$ npm install --save-dev removeduplicatesfromarrayofarrays - defaults to @latest version
```

## Dependency
deduplicatearrayofstrings - v1.0.12

![Test Result](https://github.com/ravichandranjv/removeduplicatesfromarrayofarrays/blob/master/test1.GIF)
![Test Result](https://github.com/ravichandranjv/removeduplicatesfromarrayofarrays/blob/master/test3.GIF)


```javascript
$ npm install --save-dev deduplicatearrayofstrings
```
usage

```javascript
    const gen=require('removeduplicatesfromarrayofarrays')
    var duplicateArray1=['en','es','en','fr','es','en','en','fr','fr']
    var duplicateArray2=['Spectre','Pirates of the Caribbean','Spectre','Avatar','Avatar']
    var duplicateArray3=['Sam Worthington','Denzel Washington','Sam Worthington','Sigourney Weaver','Denzel Washington','Sam Worthington']
    var duplicateArrayOfArrays=[]
    duplicateArrayOfArrays.push(duplicateArray1)
    duplicateArrayOfArrays.push(duplicateArray2)
    duplicateArrayOfArrays.push(duplicateArray3)

    var iterable=new gen(duplicateArrayOfArrays)
    for (let x of iterable)
    console.log("De-duplicated values - " + x)

```test results & usage


##Author: **Ravichandran JV**
*License: ISC*
