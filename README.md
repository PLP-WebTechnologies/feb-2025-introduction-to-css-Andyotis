/* General body styling */
body {
    font-family: 'Poppins', sans-serif;
    background-color: #f2f6ff;
    margin: 0;
    padding: 0;
}

/* Styling a class */
.container {
    width: 80%;
    margin: 50px auto;
    padding: 20px;
    background-color: #ffffff;
    border: 2px solid #d1d9e6;
    border-radius: 8px;
}

/* Styling an ID */
#main-heading {
    color: #2a4d9b;
    text-align: center;
    margin-bottom: 20px;
}

/* Styling an image */
img.profile-pic {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    border: 3px solid #2a4d9b;
    display: block;
    margin: 0 auto 20px;
}

/* Styling paragraph */
p {
    font-size: 18px;
    color: #333;
    line-height: 1.6;
}

/* Styling a button */
button {
    background-color: #2a4d9b;
    color: #fff;
    border: none;
    padding: 10px 20px;
    margin-top: 15px;
    border-radius: 5px;
    cursor: pointer;
}

button:hover {
    background-color: #1e3875;
}
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Styled Page Example</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="container">
    <h1 id="main-heading">Welcome to My Page</h1>
    <img src="profile.jpg" alt="Profile Picture" class="profile-pic">
    <p>Hello! I'm excited to learn more about styling webpages with CSS. This paragraph shows different typography and padding.</p>
    <button>Click Me</button>
</div>

</body>
</html>
