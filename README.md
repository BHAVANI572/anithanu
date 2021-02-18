# anithanu

### function
function withuot parameters 
```javascript
function addition(){
var a=10;
var b=20;
var c=30;
return a+b+c;
}
addition()
60
```
function with parameters

```javascript
function subtraction(a,b){
return(a-b)
}
subtraction(8,3)
5
```

function with parameters

```javascript
function multiplication(a,b){
return(a*b)
}
multiplication(4,7)

28
```
anonymous functions
```javascript
var subtraction=function(a,b){
  return(a-b)
}
undefined
subtraction(4,5)
-1

arrow function

```javascript
var mul=(a,b)=>{
   return(a*b)
}
mul(2,3)
6
### higher order function (HOF)
*A function accepts another function as an argument*

```javascript
arr.map((item,index)=>{
    console.log(item+"is having index of : "+index)
})















