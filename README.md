<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8" />
</head>
<body>
    <h1>Exemplo de Código ES6</h1>
    <h3>Função para calcular salário</h3>
    <pre>
        function calculaSalario(){
            var valor = document.getElementById("valor").value;
            var quantidade = document.getElementById("quantidade").value;
            var salario = valor*quantidade;
            alert(salario);
        }
    </pre>
    <h1>Exemplo de Código TypeScript</h1>
    <h3>Exemplo de operações matemáticas</h3>
    <pre>
        var num1:number = 10;
        var num2:number = 2;
        var res :number = 0;
        res = num1 + num2;
        console.log("Sum: "+res);
        res = num1 - num2;
        console.log("Difference: " + res);
        res = num1*num2;
        console.log("Product: " + res);
        res = num1/num2;
        console.log("Quotient: " + res);
        res = num1%num2;
        console.log("Remainder: " + res);
        num1++;
        console.log("Value of num1 after increment "+num1);
        num2--;
        console.log("Value of num2 after decrement "+num2);
    </pre>
</body>
</html>
