<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Positive Communication Platform</title>
    <link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>Welcome to the Positive Communication Platform</h1>
        <form action="#" method="post" id="loginForm">
            <label for="gender">Select your gender:</label>
            <select name="gender" id="gender">
                <option value="male">Male</option>
                <option value="female">Female</option>
            </select>
            <input type="button" value="Login" onclick="showSections()">
        </form>
    </div>

    <div id="textSection" class="hidden">
        <h2>Text Communication Section</h2>
        <!-- Add your HTML code for text communication here -->
    </div>

    <div id="voiceSection" class="hidden">
        <h2>Voice Communication Section</h2>
        <!-- Add your HTML code for voice communication here -->
    </div>

    <script src="script.js"></script>
</body>
</html>
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f0f0f0;
}

.container {
    max-width: 600px;
    margin: 50px auto;
    text-align: center;
    background-color: #fff;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

h1, h2 {
    color: #333;
}

form {
    margin-top: 20px;
}

select, input {
    padding: 8px;
    margin: 5px;
}

.hidden {
    display: none;
}
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f0f0f0;
}

.container {
    max-width: 600px;
    margin: 50px auto;
    text-align: center;
    background-color: #fff;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

h1, h2 {
    color: #333;
}

form {
    margin-top: 20px;
}

select, input {
    padding: 8px;
    margin: 5px;
}

.hidden {
    display: none;
}
function showSections() {
    var gender = document.getElementById('gender').value;

    if (gender === 'male') {
        document.getElementById('textSection').style.display = 'block';
        document.getElementById('voiceSection').style.display = 'none';
    } else if (gender === 'female') {
        document.getElementById('textSection').style.display = 'none';
        document.getElementById('voiceSection').style.display = 'block';
    }
}
# filling-good
future felling share
