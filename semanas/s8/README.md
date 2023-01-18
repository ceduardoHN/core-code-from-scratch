# Semana 7
## Lunes
1. [Training JS #7: if..else and ternary operator](https://www.codewars.com/kata/57202aefe8d6c514300001fd/train/javascript): 
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
2. [Training JS #8: conditional statement--switch](https://www.codewars.com/kata/572059afc2f4612825000d8a/train/javascript): 
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
3. [Basic Calculator](): 
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
1. [Even or odd](https://www.codewars.com/kata/53da3dbb4a5168369a0000fe/train/javascript): 
```
function evenOrOdd(number) {
  if(number%2===0) return "Even";
  return "Odd";
}
```
2. [A wolf in sheep's clothing](https://www.codewars.com/kata/5c8bfa44b9d1192e1ebd3d15/train/javascript): 
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
3. [Decode the morse code](https://www.codewars.com/kata/54b724efac3d5402db00065e/train/javascript): 
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
1. [Who likes it?](https://www.codewars.com/kata/5266876b8f4bf2da9b000362/train/javascript): 
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
2. [Bit counting](https://www.codewars.com/kata/526571aae218b8ee490006f4/train/javascript): 
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
3. [Your order, please](): ``````

## Jueves
1. [Countin duplicates](): ``````
2. [Encript this!](): ``````
3. [Valid parentheses](): ``````
4. [Convert string to camel case](): ``````
