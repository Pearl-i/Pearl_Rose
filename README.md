# Pearl_Rose
I love Computer Science.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Dynamic Webpages with JavaScript (Fixed)</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <h1>Dynamic Webpages with JavaScript</h1>
    <button onclick="showMessage()">Click Me</button>
    <p id="demo"></p>
    <script>
        function showMessage() {
            document.getElementById('demo').innerHTML = "Hello, this is dynamic JavaScript!";
        }
    </script>
</body>
</html>
