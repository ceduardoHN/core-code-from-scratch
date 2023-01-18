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
1. [Even or odd](): ``````
2. [A wolf in sheep's clothing](): ``````
3. [Decode the morse code](): ``````

## Miercoles
1. [Who likes it?](): ``````
2. [Bit counting](): ``````
3. [Your order, please](): ``````

## Jueves
1. [Countin duplicates](): ``````
2. [Encript this!](): ``````
3. [Valid parentheses](): ``````
4. [Convert string to camel case](): ``````
