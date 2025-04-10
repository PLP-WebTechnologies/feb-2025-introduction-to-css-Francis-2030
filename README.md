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
    <!-- External CSS Link -->
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header id="main-header">
        <h1>CSS Styling Exercise</h1>
    </header>
    
    <main class="content-box">
        <section>
            <h2 class="section-title">Key Features</h2>
            <p>Demonstrating fundamental CSS techniques:</p>
            <ul class="feature-list">
                <li>Multiple selector types</li>
                <li>Color and typography</li>
                <li>Box model properties</li>
            </ul>
        </section>
        
        <section>
            <h2 class="section-title">Styled Elements</h2>
            <img src="https://via.placeholder.com/400x300" alt="CSS Demo" class="styled-image">
            <p class="image-caption">This image showcases border and shadow effects</p>
        </section>
    </main>
    
    <footer id="page-footer">
        <p>CSS Practice Project</p>
    </footer>
</body>
</html>
/* ===== BASE STYLES ===== */
/* Element Selector */
body {
    font-family: 'Arial', sans-serif;
    line-height: 1.6;
    color: #333;
    background-color: #f9f9f9;
    margin: 0;
    padding: 0;
}

/* ===== HEADER STYLES ===== */
/* ID Selector */
#main-header {
    background-color: #2c3e50;
    color: #ecf0f1;
    text-align: center;
    padding: 1.5rem 0;
    margin-bottom: 2rem;
    border-bottom: 3px solid #e74c3c;
}

/* ===== MAIN CONTENT ===== */
/* Class Selector */
.content-box {
    width: 85%;
    margin: 0 auto 2rem;
    padding: 2rem;
    background: white;
    border: 1px solid #ddd;
    border-radius: 5px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

.section-title {
    color: #2c3e50;
    font-family: 'Georgia', serif;
    border-left: 4px solid #e74c3c;
    padding-left: 10px;
}

/* ===== IMAGE STYLING ===== */
.styled-image {
    display: block;
    max-width: 100%;
    height: auto;
    margin: 1.5rem auto;
    border: 2px solid #3498db;
    border-radius: 4px;
    padding: 5px;
    background: #ecf0f1;
}

.image-caption {
    text-align: center;
    font-style: italic;
    color: #7f8c8d;
    margin-top: -1rem;
}

/* ===== LIST STYLING ===== */
.feature-list {
    padding-left: 1.5rem;
}

.feature-list li {
    margin-bottom: 0.5rem;
    padding-left: 0.5rem;
}

/* ===== FOOTER STYLING ===== */
#page-footer {
    background-color: #2c3e50;
    color: #ecf0f1;
    text-align: center;
    padding: 1rem;
    margin-top: 2rem;
    border-top: 3px solid #e74c3c;
}
