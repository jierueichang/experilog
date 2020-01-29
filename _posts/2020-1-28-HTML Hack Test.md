
<!DOCTYPE html>
<html>
    <head><title>Experilog-Post</title></head>
    <body>
        <style>
        html,body{
            font-family:"Segoe UI",Roboto,Helvetica,Arial,sans-serif;
            margin:0px;
            background-color:black;
        }
        h1{
            font-family:"Segoe UI",Roboto,Helvetica,Arial,sans-serif;
            font-size: 50pt;
            font-weight:lighter;
            color:white;
        }
        hr{
            height:2px;
            background-color:black;
            color:white;
            border:none;
        }
        input{
            border-radius:10px;
            border:none;
            font-size:30pt;
            font-family:"Segoe UI",Roboto,Helvetica,Arial,sans-serif;
            padding:10px;
            background-color:black;
            color:white;
        }
        input[type=text]:hover{
            background-color:rgb(210, 236, 147);
            color:black;
        }
        input[type=submit]{
            padding:10px;
            background-color:lightseagreen;
            font-size:20pt;
            margin-top:10px;
        }
        input[type=submit]:hover{
            background-color:rgb(90, 233, 226);
        }
        textarea{
            width:100%;
            height:300px;
            border-radius:10px;
            font-family:"Segoe UI",Roboto,Helvetica,Arial,sans-serif;
            font-size:15pt;
            border:none;
            padding:10px;
        }
        .container{
            width:60%;
            margin-left:20%;
            margin-right:20%;
        }
        .message{
            padding:10px;
            background-color:lightseagreen;
            font-size:10pt;
            margin:10px;
        }
        </style>
        <div class='container'>
            
            
            
            <br>
            <h1>Experilog Poster</h1>
            <form method = post>
                <input type="text" name=title placeholder="Title">
                <hr>
                <textarea name='content'></textarea>
                <hr>
                <input type='submit'>
            </form>
        </div>
    </body>
</html>