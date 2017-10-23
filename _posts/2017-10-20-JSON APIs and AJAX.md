#### jquery.getJSON()
> $.getJSON(JSON,functions(JSON){});
#### stringify and parse
> JSON.stringify(json)
> JSON.parse(string)
#### forEach
> json.forEach(function(val){
> });
#### Object.keys()
> keys = Object.keys(val);
#### filter
> json.filter(function(val){
});
#### navigator.geolocation
> if (navigator.geolocation) {
  navigator.geolocation.getCurrentPosition(function(position) {
    $("#data").html("latitude: " + position.coords.latitude + "<br>longitude: " + position.coords.longitude);
  });
}
#### try catch finally
> function inIframe { try {} catch(e) {} finally {} }
#### jquery.ajax
> $.ajax({
> headers:{
> "xxx-key":rtyui9op,
> Accept:"Application/json",
> "Content-Type":"application/x-www-form-urlencoded"
> },
> url:'',
> success:function(r){}
> });
#### animate
> $(".quote-text").animate ({opacity:0},500,function(){
> $(this)
> 