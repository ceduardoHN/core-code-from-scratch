# Semana 9
## Lunes
1. ["this" is a problem](https://www.codewars.com/users/ceduardoHN/completed_solutions): 
```
function NameMe(first,last){
    this.firstName=first;
    this.lastName=last;
    this.name=this.firstName +" "+ this.lastName;
}
```
2. ["Thinkful - List and Loop Drills: Lists of lists"](https://www.codewars.com/users/ceduardoHN/completed_solutions): 
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
3. [Stop gninnipS My sdroW!](https://www.codewars.com/users/ceduardoHN/completed_solutions): 
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
1. ["this" is an other problem](https://www.codewars.com/users/ceduardoHN/completed_solutions): 
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
2. ["Who likes it?"](https://www.codewars.com/users/ceduardoHN/completed_solutions): 
```
function likes(names) {
  switch(names.length){
      case 0:
        return "no one likes this";
        break;
      case 1:
        return names[0]+" likes this";
        break;
      case 2:
        return names[0] +" and "+ names[1] +" like this";
        break;
      case 3:
        return `${names.slice(0,2).join(", ")} and ${names[2]} like this`;
        break;
      default:
        return `${names.slice(0,2).join(", ")} and ${names.length-2} others like this`;
        break;
  }
}
```
3. [Convert string to camel case](https://www.codewars.com/users/ceduardoHN/completed_solutions): 
```
function toCamelCase(str){
  let result="";
  for(let i=0;i<=str.length-1;i++){
    if(i!=0 && (str[i-1]==="-" || str[i-1]==="_")){
      result=result+str[i].toUpperCase();
    }
    else if(str[i]!="-" && str[i]!="_"){
      result=result+str[i];
    }
  }
  return result;
}
```

## Miercoles
1. [Easy mathematical callback](https://www.codewars.com/users/ceduardoHN/completed_solutions): 
```
function processArray(arr,callback) {
  let resultArray=[];
  for(let i=0;i<=arr.length-1;i++){
    resultArray[i]=callback(arr[i]);
  }
  return resultArray;
}
```
2. [Moving Zeros To The End](https://www.codewars.com/users/ceduardoHN/completed_solutions): 
```
function moveZeros(arr) {
  let zerosArray=[];
  let noZerosArray=[];
  for(let i=0;i<=arr.length-1;i++){
    if(arr[i]===0){
      zerosArray.push(arr[i]);
    }
    else{
      noZerosArray.push(arr[i]);
    }
  }
  return noZerosArray.concat(zerosArray);  
}
```
3. [Valid Parentheses](https://www.codewars.com/users/ceduardoHN/completed_solutions): 
```
function validParentheses(parens) {
  let validation=0;
  for(let i=0;i<=parens.length-1;i++){
    if(parens[i]==="(") validation++;
    if(parens[i]===")") validation--;
    if(validation<0){
      return false;
    }
  }
  return validation==0;
}
```

## Jueves

1. [The Hashtag Generator](https://www.codewars.com/users/ceduardoHN/completed_solutions): 
```
function generateHashtag(str){
  if(str.length===0) return false;
  let result=str.split(" ")
    .reduce(
      (prevVal,currVal)=>(prevVal+=currVal.charAt(0).toUpperCase()+currVal.slice(1)),"#"
    );  
  if(result.length>140) return false;
  return result;
}
```
2. [String incrementer](https://www.codewars.com/users/ceduardoHN/completed_solutions): 
```
function incrementString(str){
  let match=str.match(/\d+$/);
  if(!match){
    return str+"1";
  }
  let num=match[0];
  let newNum=(parseInt(num)+1).toString();
  while(newNum.length<num.length){
    newNum="0"+newNum;
  }
  return str.replace(/\d+$/,newNum);
}
```
