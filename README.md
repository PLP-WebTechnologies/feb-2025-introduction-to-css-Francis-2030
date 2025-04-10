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

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Introduction</title>
    <!-- Task 1: Link external CSS file -->
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header id="main-header">
        <h1>Welcome to CSS Styling</h1>
    </header>
    
    <main class="content">
        <section>
            <h2 class="highlight">About This Page</h2>
            <p>This page demonstrates basic CSS styling techniques including:</p>
            <ul>
                <li>Selectors (element, class, ID)</li>
                <li>Colors and typography</li>
                <li>Spacing with margins and padding</li>
                <li>Border styling</li>
            </ul>
        </section>
        
        <section>
            <h2>Styled Image</h2>
            <!-- Task: Style an image -->
            <img src="https://via.placeholder.com/400x300" alt="Example image" class="featured-image">
        </section>
    </main>
    
    <footer>
        <p>CSS Practice Exercise</p>
    </footer>
</body>
</html>

/* Task 2: Apply at least 3 different selectors */
/* 1. Element selector */
body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    line-height: 1.6;
    color: #333;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

/* 2. ID selector */
#main-header {
    background-color: #2c3e50;
    color: white;
    text-align: center;
    padding: 1rem;
    margin-bottom: 2rem;
}

/* 3. Class selector */
.highlight {
    color: #e74c3c;
    font-weight: bold;
}

/* Task: Style an image */
.featured-image {
    border: 3px solid #3498db;
    border-radius: 8px;
    display: block;
    margin: 0 auto;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

/* Task: Margin, Padding & Borders */
.content {
    background-color: white;
    width: 80%;
    margin: 0 auto;
    padding: 2rem;
    border: 1px solid #ddd;
    border-radius: 5px;
}

/* Different font for headings */
h1, h2 {
    font-family: 'Georgia', serif;
}

/* Additional spacing for readability */
p, ul {
    margin-bottom: 1.5rem;
}

footer {
    text-align: center;
    margin-top: 2rem;
    padding: 1rem;
    background-color: #2c3e50;
    color: white;
}
