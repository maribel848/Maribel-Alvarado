HTML!!!

<!DOCTYPE html>
<html lang="es">

<head>
    <title>Calculadora Simple</title>
    <meta charset="utf-8" />
    <link rel="stylesheet" href="style.css" />

</head>

<body>
    <div class="nombre">
        <h1 class="titulo">Calculadora</h1>
    </div>
    <div class="container">

        <div class="calculator">
            <form>
                <div class="display">
                    <input type="text" name="display"/>
                
                </div>

                <div>
                    <input type="button" value="AC" onclick="display.value = ''" class="operator" />
                    <input type="button" value="DEL" onclick="display.value = display.value.toString().slice(0, -1)" class="operator" />
                    <input type="button" value="." onclick="display.value += '.'" class="operator" />
                </div>
                <div>
                    <input type="button" value="7" onclick="display.value += '7'" />
                    <input type="button" value="8" onclick="display.value += '8'" />
                    <input type="button" value="9" onclick="display.value += '9'" />
                    <input type="button" value="*" onclick="display.value += '*'" class="operator" />
                </div>
                <div>
                    <input type="button" value="4" onclick="display.value += '4'" />
                    <input type="button" value="5" onclick="display.value += '5'" />
                    <input type="button" value="6" onclick="display.value += '6'" />
                    <input type="button" value="-" onclick="display.value += '-'" class="operator" />
                </div>
                <div>
                    <input type="button" value="1" onclick="display.value += '1'" />
                    <input type="button" value="2" onclick="display.value += '2'" />
                    <input type="button" value="3" onclick="display.value += '3'" />
                    <input type="button" value="+" onclick="display.value += '+'" class="operator" />
                </div>
                <div>
                    <input type="button" value="00" onclick="display.value += '00'" />
                    <input type="button" value="0" onclick="display.value += '0'" />
                    <input type="button" value="=" class="equal" onclick="display.value = eval(display.value)" />
                    <input type="button" value="/" onclick="display.value += '/'" />
                    
                </div>
            </form>
        </div>
    </div>
</body>

</html>



CSS


* { 
    margin: 0;
    padding: 0;
    border: 0;
    outline: 0;
    font-family: "helvetica", sans-serif;
    box-sizing: border-box;
}

.container {
    width: 100%;
    min-height: 100vh;
    background-color: rgba(105, 179, 92, 0.676);
    display: flex;
    align-items:center;
    justify-content: center;

}

.calculator {
    background-color: rgba(8, 163, 54, 0.847);
    padding: 20px;
    border-radius:15px;
    border:  8px solid #f0f0f063;

}

    .calculator form input{
        width: 75px;
        height: 75px;
        border-radius: 15px;
        margin: 10px;
        font-size: 27px;
        background: rgba(60,146,146,0.826); 
        color:white;
        box-shadow: -8px -8px 15px rgba(255, 255, 255, 0.1),
                5px 5px 15px rgba(0,0,0,0.2); 
        
        }

        form .display{
            display: flex;
            justify-content: flex-end;
            margin: 20px 0;
        }

            form .display input{
            text-align: right;
            flex: 1;
            font-size: 40px;
            padding: 20px
        }

        form input.equal{
            width: 145;

        }

        form input.operator{
            color:rgba(127,236,255,0.826);
        }
    
    .nombre{ 
        background-color: rgba(60,146,146,0.826);
        align-items:center;
        justify-content: center;

    }

    .titulo{
        text-align: center;

    }
