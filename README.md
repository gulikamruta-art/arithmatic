<!DOCTYPE html>
<html>
<head>
    <title>Arithmetic Operations</title>
</head>
<body>

<h2>Arithmetic Operations using Switch Case</h2>

<script>
    var num1 = parseInt(prompt("Enter first number:"));
    var num2 = parseInt(prompt("Enter second number:"));
    var choice = prompt("Enter operation (+, -, *, /):");

    switch(choice) {
        case '+':
            document.write("Result = " + (num1 + num2));
            break;

        case '-':
            document.write("Result = " + (num1 - num2));
            break;

        case '*':
            document.write("Result = " + (num1 * num2));
            break;

        case '/':
            if(num2 != 0)
                document.write("Result = " + (num1 / num2));
            else
                document.write("Division by zero not allowed");
            break;

        default:
            document.write("Invalid choice");
    }
</script>

</body>
</html>
