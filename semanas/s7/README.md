# Semana 7
## Lunes
1. [String: substr()](https://www.jshero.net/en/koans/stringsubstr.html): 
```
function firstWord(string){
   let firstSpace=string.indexOf(" ");
   let word=string.substr(0,firstSpace);
   return word;
}
```
2. [String: replace()](https://www.jshero.net/en/koans/replace.html): 
```
function normalize(dateString){
   let newDate=dateString.replace("-","/").replace("-","/");
   return newDate;
}
```
3. [Increment](https://www.jshero.net/en/koans/increment.html): ```7```
4. [Fahrenheit](https://www.jshero.net/en/koans/fahrenheit.html): 
```
function toFahrenheit(celsius){
   let fahrenheit=(celsius*(9/5))+32;
   return fahrenheit;
}
```
5. [Boolean](https://www.jshero.net/en/koans/bool.html): 
```
function nand(boolean1,boolean2){
   if(boolean1===true && boolean2===true){
      return false;
   }
   else{
      return true;
   }
}
```

## Martes
1. [Objects](https://www.codewars.com/kata/571f1eb77e8954a812000837/train/javascript): 
```
function animal(obj){
  let result="This "+obj.color+" "+obj.name+" has "+obj.legs+" legs.";
  return result;
}
```
2. [Return to Sanity](https://www.codewars.com/kata/514a7ac1a33775cbb500001e/train/javascript): 
```
function mystery() {
  var results = { sanity: "Hello" };
  return results;
}
```
3. [Object Syntax Debug](https://www.codewars.com/kata/56d8ae9237123036d3001b54/train/javascript): 
```
var rooms = {
  first: {
    description: "This is the first room",
    items: {
      chair: "The old chair looks comfortable",
      lamp: "This lamp looks ancient"
    }
  },
  second: {
    description: "This is the second room",
    items: {
      couch: "This couch looks like it would hurt your back",
      table: "On the table there is an unopened bottle of water"
    }
  }
};
```

## Miercoles
1. [Count Strings in Objects](https://www.codewars.com/kata/565b3542af398bfb50000003/train/javascript): 
```
function strCount(obj){
  let count=0;
  for(let key in obj){
    if(typeof obj[key]=="string"){
      count++;
    }
    if(typeof obj[key]=="object"){
      count+=strCount(obj[key]);
    }
  } 
  return count;
}
```
2. [Extending JavaScript Objects: Get First & Last Array Element](https://www.codewars.com/kata/581351c40d8f13bc450008b8/train/javascript): 
```
Array.prototype.first=function(){
  return this[0];
};
Array.prototype.last=function(){
  return this[this.length-1];
};
```
3. [Object Oriented Piracy](https://www.codewars.com/kata/54fe05c4762e2e3047000add/train/javascript): 
```
function Ship(draft,crew) {
  this.draft = draft;
  this.crew = crew;
  
  this.isWorthIt=function(){
    return (this.draft-this.crew*1.5)>20;
  };
}

```

## Jueves
1. [Convert a String to a Number!](): ``````
2. [Convert a Number to Reversed Arrar of Digits](): ``````
3. [Truthy and Falsy](): ``````
4. [Training JS #4: Basic Data types--Array](): ``````
