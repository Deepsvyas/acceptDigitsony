# acceptDigitsony
Digit accepts only or find event characters for the keys from key board
<!DOCTYPE html>
<html>
<body>

<p>Press a key on the keyboard in the input field to get the Unicode character code of the pressed key.</p>

<input type="text" size="40" onkeypress="myFunction(event)">

<p id="demo"></p>

<p><strong>Note:</strong> The charCode property is not supported in IE8 and earlier versions.</p>

<script>
function myFunction(event) {
    var x = event.charCode;
    document.getElementById("demo").innerHTML = "The Unicode value is: " + x;
}
</script>

</body>
</html>
