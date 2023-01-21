# Semana 8
## Lunes
1. [Training JS #7: if..else and ternary operator](https://www.codewars.com/users/ceduardoHN/completed_solutions): 
```
function saleHotdogs(n){
  if(n<5){
    let  payment=n*100;
    return payment;
  }
  else if(n>=5 && n<10){
    let  payment=n*95;
    return payment;  
  }
  else{
    let payment=n*90;
    return payment;
  }
}
```
2. [Training JS #8: conditional statement--switch](https://www.codewars.com/users/ceduardoHN/completed_solutions): 
```
function howManydays(month){
  var days;
  switch (month){
      case 2:
          days=28;
          break;
      case 1:
      case 3:
      case 5:
      case 7:
      case 8:
      case 10:
      case 12:
          days=31;
          break;
      case 4:
      case 6:
      case 9:
      case 11:
          days=30;
          break;
      default:
          return "Enter a number from 1 to 12.";      
  }
  return days;
}
```
3. [Basic Calculator](https://www.codewars.com/users/ceduardoHN/completed_solutions): 
```
function calculate(num1, operation, num2) {
  var result;
  if(operation=="+" || operation=="-" || operation=="*" || operation=="/"){
    switch(operation){
        case "+":
            result=num1+num2;
            break;
        case "-":
            result=num1-num2;
            break;
        case "*":
            result=num1*num2;
            break;
        case "/":
            if(num2!=0){
              result=num1/num2;;
            }
            else{
              return null;
            }
            break;
    }
    return result;
  }
  else{
    return null;
  }
}
```

## Martes
1. [Even or odd](https://www.codewars.com/users/ceduardoHN/completed_solutions): 
```
function evenOrOdd(number) {
  if(number%2===0) return "Even";
  return "Odd";
}
```
2. [A wolf in sheep's clothing](https://www.codewars.com/users/ceduardoHN/completed_solutions): 
```
function warnTheSheep(queue) {
  let wolfPos=queue.indexOf("wolf");
  let sheepPos=queue.length-(wolfPos+1);
  if(wolfPos===queue.length-1){
    return "Pls go away and stop eating my sheep";
  }     
  return "Oi! Sheep number "+ sheepPos +"! You are about to be eaten by a wolf!";  
}
```
3. [Decode the morse code](https://www.codewars.com/users/ceduardoHN/completed_solutions): 
```
let decodeMorse=function(morseCode){
  let phrase=[];
  let words=morseCode.trim().split("   ");
  let letters=[];
  for(let i=0;i<words.length;i++){
    letters=words[i].split(" ");
    for (let j=0;j<letters.length;j++) {
      letters[j]=MORSE_CODE[letters[j]];
    }
    phrase.push(letters.join(""));
  }
  return phrase.join(" ").trim();
};
```

## Miercoles
1. [Who likes it?](https://www.codewars.com/users/ceduardoHN/completed_solutions): 
```
function likes(names) {
  let result="";
  if(names.length===0) return "no one likes this";
  if(names.length===1){
    result=names[0]+" likes this";
    return result;
  }
  if(names.length===2){
    result=names[0] +" and "+ names[1]+ " like this";
    return result;
  }
  if(names.length===3){
    result=names[0] +", "+ names[1] +" and "+ names[2] +" like this";
    return result;
  }
  result=names[0] +", "+ names[1] +" and "+ (names.length-2) +" others like this";
  return result;
}
```
2. [Bit counting](https://www.codewars.com/users/ceduardoHN/completed_solutions): 
```
var countBits = function(n) {
  let binaryNum=n.toString(2);
  let bitOneCounter=0;
  for(let i=0;i<=binaryNum.length-1;i++){
    if(binaryNum[i]==="1"){
      bitOneCounter++;
    }
  }
  return bitOneCounter;
};
```
3. [Your order, please](https://www.codewars.com/users/ceduardoHN/completed_solutions): 
```
function order(words) {
  let array=words.split(" ");
  let sortedArray=[];
  for(let i=0;i<=array.length;i++){
    for (let j=0;j<array.length;j++){
      if(array[j].indexOf(i)>=0){
        sortedArray.push(array[j]);
      }
    }
  }
  return sortedArray.join(" ");
```

## Jueves
1. [Countin duplicates](https://www.codewars.com/users/ceduardoHN/completed_solutions): 
```
function duplicateCount(text){
  let countDupls=0;
  text=text.toLowerCase();
  for(let i=0;i<text.length;i++){
    if(text.indexOf(text[i]) !== text.lastIndexOf(text[i])){
      countDupls++;
      let regExp=new RegExp(text[i],"g");
      text=text.replace(regExp,"");
      i--;
    }
  }
  return countDupls;
}
```
2. [Encript this!](https://www.codewars.com/users/ceduardoHN/completed_solutions): 
```
function encryptWord(word){
  if(word.length===1){
    return word.charCodeAt(0);
  }
  const secondLetter=word[1];
  word=word.replace(word[0],word.charCodeAt(0));
  word=word.replace(secondLetter,word[word.length-1]);
  word=word.replace(/\w$/,secondLetter);
  return word;
}

var encryptThis=function(text){
  const textArray=text.split(" ");
  let result="";
  textArray.forEach((word) => {
    result=result+" "+encryptWord(word);
  });
  return result.trim();
};
```
3. [Valid parentheses](https://www.codewars.com/users/ceduardoHN/completed_solutions): 
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
4. [Convert string to camel case](https://www.codewars.com/users/ceduardoHN/completed_solutions): 
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
