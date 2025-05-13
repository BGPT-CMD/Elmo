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
</html>





