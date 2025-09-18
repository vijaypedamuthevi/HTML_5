# HTML_5
HTML code for function
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Declaring function </title>
    <style>
        .out{color:blue; font-weight: bold;}
    </style>
</head>
<body>
    <h2>Function with user-name</h2>
    <p id="demo1" class="out"></p>
    <script>
        function hi(){
            return "hello students! How are you";
        }
        document.getElementById("demo1").innerText=hi();
    </script>
</body>
</html>
