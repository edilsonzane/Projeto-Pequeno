# HTML<!DOCTYPE html>



<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <script src="https://kit.fontawesome.com/2c2ad2f977.js" crossorigin="anonymous"></script>
    <link rel="stylesheet" href="Style.css">
    <title>Calculadora</title>
</head>
<body>
    <div class="conteudo">
        <div class="calculator">
            <p class="result" id="resultado"></p>
            <table>
                <tr>
                    <td><button class="btn ac" style="width: 106px;" onclick="clean()">AC</button></td>
                    <td><button class="btn neg" onclick="backspace()"><i class="fa-solid fa-delete-left"></i></button></td>
                    <td><button class="btn especial" onclick="insert('/')"><i class="fa-solid fa-divide"></i></button></td>
                </tr>
                <tr>
                    <td><button class="btn"onclick="insert('7')">7</button></td>
                    <td><button class="btn"onclick="insert('8')">8</button></td>
                    <td><button class="btn"onclick="insert('9')">9</button></td>
                    <td><button class="btn especial"onclick="insert('*')">x</button></td>
                </tr>
                <tr>
                    <td><button class="btn"onclick="insert('4')">4</button></td>
                    <td><button class="btn"onclick="insert('5')">5</button></td>
                    <td><button class="btn"onclick="insert('6')">6</button></td>
                    <td><button class="btn especial"onclick="insert('-')">-</button></td>
                </tr>
                <tr>
                    <td><button class="btn"onclick="insert('1')">1</button></td>
                    <td><button class="btn"onclick="insert('2')">2</button></td>
                    <td><button class="btn"onclick="insert('3')">3</button></td>
                    <td><button class="btn especial"onclick="insert('+')">+</button></td>
                </tr>
                <tr>
                    <td><button class="btn"onclick="insert('0')">0</button></td>
                    <td><button class="btn"onclick="insert('.')">.</button></td>
                    <td><button class="btn igual" style="width: 106px;"onclick="confirma()">=</button></td>
                </tr>    



            </table>




        </div>
    </div>
    <script src="./Script.js"></script>
</body>
</html>

