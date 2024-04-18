<html>
<head>
<title>Fibonacci Series</title>
</head>
<body>
<script>
    var a = 0, b = 1, c, i;
    var n = parseInt(prompt("Enter limit for Fibonacci series:", ""));
    document.write("<h2>Fibonacci Series:</h2><br>");
    document.write(a + " " + b + " ");
    for (i = 2; i < n; i++) {
        c = a + b;
        document.write(c + " ");
        a = b;
        b = c;
    }
</script>
</body>
</html>
