# Code Sample
This is some of my skills that I have learned as an IT student. I am writing a common code called FizzBuzz.

<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Fizz Buzz</title>
<script>

function fizzbuzz() {
	var display = document.getElementById('display');
	var displayHTML = "";
	for (i = 0; i < 100; i++) {
		displayHTML += "<p>" + i + "</p>";
	}
	display.innerHTML = displayHTML;
}

</script>

</head>

<body onload="fizzbuzz()">
<div id="display">

</div>
</body>

</html>

[Return to home page](./README.md)
	
