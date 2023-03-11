operation.js Module
```
function suma(a,b){
    var s=a+b;
    return s;
}

function resta(a,b){
    var r=a-b;
    return r;

}

module.exports={suma,resta};
```

main.js Module
```
const {suma,resta}=require("./operation");

let a=1;
let b=2;
let s1=suma(a,b);
let s2=suma(s1,b);
let r1=resta(s1,a);
let r2=resta(s2,b);

console.log("N1: ",a);
console.log("N2: ",b);
console.log("Suma: ",s1);
console.log("Suma: ",s2);
console.log("Resta: ",r1);
console.log("Resta: ",r2);
```
![imagen](https://user-images.githubusercontent.com/116420679/224516010-6c6724ac-8318-4e35-8d36-7c2b19aa4d4d.png)
![imagen](https://user-images.githubusercontent.com/116420679/224515989-d8ac971c-0a24-456e-bd47-ddd36a0f79db.png)
