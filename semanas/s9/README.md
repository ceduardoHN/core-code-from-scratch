# Semana 9
## Lunes
1. ("this" is a problem)[https://www.codewars.com/users/ceduardoHN/completed_solutions]: 
```
function NameMe(first,last){
    this.firstName=first;
    this.lastName=last;
    this.name=this.firstName +" "+ this.lastName;
}
```
2. ("Thinkful - List and Loop Drills: Lists of lists")[https://www.codewars.com/users/ceduardoHN/completed_solutions]: 
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
3. (Stop gninnipS My sdroW!)[https://www.codewars.com/users/ceduardoHN/completed_solutions]: 
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
1. ("this" is an other problem)[https://www.codewars.com/users/ceduardoHN/completed_solutions]: 
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
2. ("Who likes it?")[https://www.codewars.com/users/ceduardoHN/completed_solutions]: ``````
3. (Convert string to camel case)[https://www.codewars.com/users/ceduardoHN/completed_solutions]: ``````

## Miercoles
1. (Easy mathematical callback)[https://www.codewars.com/users/ceduardoHN/completed_solutions]: ``````
2. (Moving Zeros To The End)[https://www.codewars.com/users/ceduardoHN/completed_solutions]: ``````
3. (Valid Parentheses)[https://www.codewars.com/users/ceduardoHN/completed_solutions]: ``````

## Jueves

1. (The Hashtag Generator)[https://www.codewars.com/users/ceduardoHN/completed_solutions]: ``````
2. (String incrementer)[https://www.codewars.com/users/ceduardoHN/completed_solutions]: ``````
