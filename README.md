# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file.
Apply CSS to a HTML page.
Style elements using:
Classes and IDs.
Color and typography.
Margins, paddings, and borders.

>[!NOTE]
>  - Include at least:
>  - Use of 3 selectors
>  - Style an image
>  - Margin, Padding & Borders
>  - Different font

# Tasks
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.

Happy Coding! 💻✨
1. Index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Introduction to CSS</title>
    <link rel="stylesheet" href="style.css"> <!-- Linking external CSS -->
</head>
<body>

    <h1 class="title">Welcome to CSS Styling</h1>

    <p class="description">
        This is an example of how to apply CSS styling using an external stylesheet.
    </p>

    <img src="image.jpg" alt="Styled Example Image" id="styled-image">

    <div class="box">
        <p>This box demonstrates margin, padding, and borders.</p>
    </div>

</body>
</html>
2. CSS File (style.css)
/* Applying a different font */
body {
    font-family: 'Verdana', sans-serif;
    background-color: #f4f4f4;
    text-align: center;
    color: #333;
}

/* Selector 1: Class - Styling the title */
.title {
    font-size: 2rem;
    font-weight: bold;
    color: #1e90ff;
    margin-top: 20px;
}

/* Selector 2: ID - Styling an image */
#styled-image {
    width: 300px;
    border: 5px solid #71B34A;
    border-radius: 10px;
    margin: 20px 0;
}

/* Selector 3: Class - Styling a div with margin, padding & border */
.box {
    background-color: white;
    padding: 20px;
    margin: 20px auto;
    border: 2px solid #F7931E;
    width: 50%;
    border-radius: 8px;
    box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1);
}


