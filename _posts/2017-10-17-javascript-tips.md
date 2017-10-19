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

## array functions
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
#### filter
> var newArray = oldArray.filter(function (val) {
>  return val <= 5;
> });
#### sort
> array.sort(function (a,b) {
>  return a - b;
> });
#### reverse
> newArray = array.reverse();
#### concat
> newArray = oldArray.concat(concatMe);
#### split
> array = string.split(' ');
#### join
> joinedString = joinMe.join(" ");
#### upper and lower case
> str.toUpperCase();
> str,toLowerCase();
#### value to string
> String(val)
> "" + val
> val.toString()
#### substr and substring
> str.substr(start,length)
> str.substring(start,end)
#### slice and splice
> array.slice(start,end)
> string.slice(start,end)
> delete = array.splice(start,deleteCount,item,,,)
#### Array.from
> var args = Array.from(arguments).slice(1);
#### array.includes
> arr.includes(val)
#### charCodeAt & fromCharCode
str.charCodeAt(pos)
String.fromCharCode(num)


