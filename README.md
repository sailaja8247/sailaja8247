
<!DOCTYPE html>
<html>
    <head>
    <title> checkbox</title>
    <script>
        function checkanswer(){
            var answer = document.getElementById("input").value.toLowerCase();
            if ( answer ==="ol"){
                document.getElementById("result").innerHTML="correct!";
                document.getElementById("result").style.color="green";
            }
            else{
                document.getElementById("result").innerHTML="incorrect Answer!";
                document.getElementById("result").style.color="red";
            }
        }
    </script>
    </head>
    <body>
        <p>what tag is used to Createan ordered list ?</p>
        <input type="text" id="input">
        <button class=" btn btn-info" onclick="checkanswer()"> check Answer</button>
        <p id ="result"></p>

    </body>
</html>
