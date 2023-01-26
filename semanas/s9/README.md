# Semana 9
## Lunes
1. ("this" is a problem)[]: 
```
function NameMe(first,last){
    this.firstName=first;
    this.lastName=last;
    this.name=this.firstName +" "+ this.lastName;
}
```
2. ("Thinkful - List and Loop Drills: Lists of lists")[]: 
```
function processData(data){
  let mult=1;
  for(let i=0;i<data.length;i++){
    let result=data[i][0]-data[i][1];
    mult=mult*result;
  }
  return mult;
}
```
3. (Stop gninnipS My sdroW!)[]: 
```
function spinWords(string){
  let words=string.split(" ");
  for(let i=0;i<=words.length-1;i++){
    if(words[i].length>=5){
      words[i]=words[i].split("").reverse().join("");
    }
  }
  return words.join(" ");
}
```

## Martes
1. ("this" is an other problem)[]: 
```
function NamedOne(first,last){
  this.firstName=first;
  this.lastName=last;
  
  Object.defineProperty(this,"fullName",{
    get: function(){
      return this.firstName +" "+ this.lastName;
    },
    set: function(fullName){
      const arrayName=fullName.split(" ");
      if(arrayName.length===2){
        this.firstName=arrayName[0];
        this.lastName=arrayName[1];
      }
    }
  });
}
```
2. ("Who likes it?")[]: ``````
3. (Convert string to camel case)[]: ``````

## Miercoles
1. (Easy mathematical callback)[]: ``````
2. (Moving Zeros To The End)[]: ``````
3. (Valid Parentheses)[]: ``````

## Jueves

1. (The Hashtag Generator)[]: ``````
2. (String incrementer)[]: ``````
