## object
#### declare a object
> var myObject = {
>	"name":"Fred",
>	"date-of-birth":"1974-03-18"
> };

#### construct a object
> var myObject = function() {
>	this.name = "Fred";
>	this.date-of-birth = "1974-03-18";
> };

#### construct a object with variebles
> var myObject = function(name,birthdate) {
>	this.name = name;
>	this.date-of-birth = birthdate;
> };

## Math
> Math.random();
> Math.floor();

## functions
#### map
> var newArray = oldArray.map(function (val) {
>   return val * 2;
> }
> );
#### reduce
> var singleVal = array.reduce(function (previousVal,currentVal) {
>   return previousVal + currentVal;
> },0
> );