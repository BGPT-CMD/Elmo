# Elmo
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Reveal Address</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h1>Welcome!</h1>
        <button id="revealBtn">Click to See Address</button>
        <p id="address" class="hidden">1234 Your Street, Your City, Country</p>
    </div>

    <script>
        document.getElementById("revealBtn").addEventListener("click", function() {
            document.getElementById("address").classList.remove("hidden");
        });
    </script>
</body>
</html>body {
    font-family: Arial, sans-serif;
    text-align: center;
    margin-top: 50px;
    background-color: #f0f0f0;
}

.container {
    background: white;
    padding: 30px;
    border-radius: 10px;
    display: inline-block;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
}

button {
    padding: 10px 20px;
    font-size: 16px;
    cursor: pointer;
}

.hidden {
    display: none;
}

#address {
    margin-top: 20px;
    font-size: 18px;
    color: #333;
}




