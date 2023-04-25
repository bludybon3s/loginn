<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login Js</title>
    
    <style>

        *{
            box-sizing: border-box;
        }

        body{
            width: 100%;
            height: 100%;
        }

        form{
            width: 300px;
            margin: 200px auto;
            text-align: center;
        }

        input{
            display: block;
            margin: 10px auto;
            width: 300px;
            height: 28px;
        }
    </style>
</head>
<body>
    <form>
        <h3>Login</h3>
        <input type="text" placeholder="Login" id="login">
        <input type="password" placeholder="Senha" id="senha">
        <input type="submit" onclick="logar()">
    </form>

    <script>
        function logar(){

            var login = document.getElementById('login').value;
            var senha = documento.getElementById('senha').value;

            if(login == "admin" && senha == "123456"){
                alert('sucesso!');
            }else{
                alert('nao deu trouxa');
            }
        }
    </script>
</body>
</html>
