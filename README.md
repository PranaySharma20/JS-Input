# JS-Input
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>User Input</title>
</head>
<body>
    <input type="text" id="text1" placeholder="Enter Password">
    <br>
    <button id="Btn" onclick="len()">Click here</button>
    
</body>
<script>
    function len(){
       var a = document.getElementById("text1").value;
        b = a.length
        console.log(b)
    }
</script>
</html>
