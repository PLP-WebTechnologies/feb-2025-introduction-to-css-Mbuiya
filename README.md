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



<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Styled Page</title>
    <!-- Link to External CSS File -->
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header id="main-header">
        <h1>Welcome to My Styled Page</h1>
    </header>

    <section class="content">
        <h2>About Us</h2>
        <p>We are a creative agency that specializes in web development and design.</p>
    </section>

    <section>
        <h2>Our Services</h2>
        <ul>
            <li>Web Design</li>
            <li>SEO Optimization</li>
            <li>Brand Identity</li>
        </ul>
    </section>

    <section>
        <img src="https://via.placeholder.com/300" alt="Placeholder Image" class="image-style">
    </section>

    <footer>
        <p>&copy; 2025 My Creative Agency</p>
    </footer>
    
</body>
</html>

Happy Coding! 💻✨
