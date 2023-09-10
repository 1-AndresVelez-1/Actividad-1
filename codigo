<!DOCTYPE html>
<html>
<head>
    <title>Calculadora de Suma</title>
</head>
<body>
    <h1>Calculadora de Suma</h1>
    
    <label for="numero1">Número 1:</label>
    <input type="number" id="numero1"><br><br>
    
    <label for="numero2">Número 2:</label>
    <input type="number" id="numero2"><br><br>
    
    <button onclick="sumar()">Sumar</button><br><br>
    
    <p>Resultado: <span id="resultado"></span></p>

    <script>
        function sumar() {
            // Obtener los valores de los números ingresados por el usuario
            var numero1 = parseFloat(document.getElementById("numero1").value);
            var numero2 = parseFloat(document.getElementById("numero2").value);

            // Comprobar si los valores son números válidos
            if (!isNaN(numero1) && !isNaN(numero2)) {
                // Realizar la suma
                var resultado = numero1 + numero2;

                // Mostrar el resultado en la página
                document.getElementById("resultado").textContent = resultado;
            } else {
                alert("Por favor, ingrese números válidos.");
            }
        }
    </script>
</body>
</html>
