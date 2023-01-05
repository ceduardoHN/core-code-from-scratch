# Semana 6
## Martes
1. [Variables](https://www.jshero.net/en/koans/var.html): ```let firstname="Lata";```
2. [What is x?](https://www.jshero.net/en/koans/jsx01.html): ```"Geeta"```
3. [Several Variables](https://www.jshero.net/en/koans/var2.html): 
```
let flower="rose";
let tree="maple";
```
4. [Reassignment](https://www.jshero.net/en/koans/jsx02.html): ```"Toe"```
5. [Assign Variables](https://www.jshero.net/en/koans/jsx03.html): ```"Hardy"```

## Miercoles
1. [Functions](https://www.jshero.net/en/koans/function.html):
```
function hello(){
   return "Hello world!";
}
```
2. [Multiple Functions](https://www.jshero.net/en/koans/function2.html):
```
function a(){
   return "Hello a!";
}

function b(){
   return "Hello b!";
}
```
3. [Function calls](https://www.jshero.net/en/koans/functioncall.html):
```
function greet(){
   return "Haydo!";
}

let salutation=greet();
```
4. [What is x?](https://www.jshero.net/en/koans/jsx04.html) (Function version): ```"Hi!"```
5. [Parameters](https://www.jshero.net/en/koans/parameter.html):
```
function echo(p){
   return p;
}
```

## Jueves
1. [Strings](https://www.jshero.net/en/koans/string.html):
```
function greet(name){
   return "Hello "+name+"!";
}
```
2. [String: length](https://www.jshero.net/en/koans/stringlength.html): 
```
function length(string){
   let result=string.length;
   return result;
}
```
3. [String: toUpperCase()](https://www.jshero.net/en/koans/stringupper.html): 
```
function toCase(string){
   let stringInLC=string.toLowerCase();
   let stringInUC=string.toUpperCase();
   return stringInLC+"-"+stringInUC;
}
```
4. [String: charAt()](https://www.jshero.net/en/koans/stringcharat.html): 
```
function shortcut(string1,string2){
   return string1.charAt(0)+string2.charAt(0);
}
```
5. [String: indexOf()](https://www.jshero.net/en/koans/stringindexof.html): 
```
function indexOfIgnoreCase(string1,string2){
   let string1L=string1.toLowerCase();
   let string2L=string2.toLowerCase();
   return string1L .indexOf(string2L);
}
```
