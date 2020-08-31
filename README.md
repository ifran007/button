# button
<!DOCTYPE html>
<html>
<body>

<ul id="myList">

</ul>

<input type="text" id="myText" value="">

<button onclick="myFunction()">SUbmit</button>

<script>
function myFunction() {
var element = document.createElement("li");
var textnode = document.createTextNode(myText.value);
element.appendChild(textnode);

var list = document.getElementById("myList");
list.insertBefore(element, list.childNodes[0]);
}
</script>

</body>
</html>
