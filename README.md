# JavaScript
# jQuery
grab jQuery cdn
Need to load jQuery before Java Script
$("empty-div).html("<h1>Hello friends</h1>");

$("empty-div).append("A pleasure to meet you");

Explanation: ****
created an empty-div
gave it h1 tag with Hello friends
append A pleasure to meet you text and make it a child of empty-div
var newDiv = $("<div>");
newDiv.text("A pleasure to meet you");
$("empty-div).append(newDiv);

created new div
gave it a text of A pleasure to meet you
append it to make it a child of empty-div

newDiv.attr("class", "fancy");
or
newDiv.addClass("fancy cool");
add multiple classes by adding space between to classes inside the same ""(same as how you would do it HTML)

gave it a class attribute using shorthand attr

jQuery.each method

$(document).ready(function(){
  $("#click-me").on("click". function(e){
    alert("I've been clicked!);
    var response = prompt("Hello");
    console.log(response);
  });
});


prepend is to push something before
