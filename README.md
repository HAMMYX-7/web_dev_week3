# web_dev_week3
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Styled Page</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header id="main-header">
        <h1>Welcome to My Page</h1>
    </header>

    <section class="content">
        <p>This is a paragraph styled with CSS to demonstrate margins, padding, and typography.</p>
        <img src="https://via.placeholder.com/300" alt="Placeholder Image" class="styled-image">
    </section>

    <footer>
        <p class="footer-text">Thank you for visiting!</p>
    </footer>

</body>
</html>
/* Style for ID selector */
#main-header {
    background-color: #4CAF50;
    color: white;
    text-align: center;
    padding: 20px;
    font-family: 'Arial', sans-serif;
}

/* Style for class selector */
.content {
    margin: 40px;
    padding: 20px;
    background-color: #f9f9f9;
    font-family: 'Georgia', serif;
    font-size: 18px;
    border: 2px solid #ddd;
}

/* Style an image */
.styled-image {
    display: block;
    margin: 20px auto;
    border: 5px solid #4CAF50;
    border-radius: 10px;
    width: 300px;
}

/* Style for footer text */
.footer-text {
    text-align: center;
    color: #777;
    margin-top: 50px;
    font-size: 16px;
}
