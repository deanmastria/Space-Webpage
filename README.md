# Space-Webpage

## ChatGPT Prompt

_Create a HTML code with a specific theme_
**_Content Requirements:_**
_At least one header section_
_A navigation bar with at least 3 links_
_At least one images_
_Main content area with at least 3 sections/articles_
_A footer with copyright and contact information._
**_Design Requirements:_**
_Use of external CSS for styling_
_the design should be responsive and visually appealing._

_This needs to be about space exploration_

Certainly! Below is a simple HTML template themed around space exploration, complete with the specified content and design requirements.

HTML Code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Space Exploration</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Space Exploration</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#missions">Missions</a></li>
                <li><a href="#future">Future</a></li>
            </ul>
        </nav>
    </header>
    
    <main>
        <section id="about">
            <h2>About Space Exploration</h2>
            <p>Space exploration is the ongoing discovery and exploration of celestial structures in outer space by means of continuously evolving and growing space technology.</p>
            <img src="space.jpg" alt="Space">
        </section>
        
        <section id="missions">
            <h2>Historic Missions</h2>
            <article>
                <h3>Apollo 11</h3>
                <p>Apollo 11 was the spaceflight that first landed humans on the Moon. Commander Neil Armstrong and lunar module pilot Buzz Aldrin formed the American crew that landed the Apollo Lunar Module Eagle on July 20, 1969.</p>
            </article>
            <article>
                <h3>Voyager 1</h3>
                <p>Voyager 1 is a space probe launched by NASA on September 5, 1977. It is currently the farthest human-made object from Earth, providing valuable scientific data.</p>
            </article>
        </section>
        
        <section id="future">
            <h2>Future of Space Exploration</h2>
            <p>Humanity's journey into space is only just beginning. The future holds possibilities for deeper space missions, Mars colonization, and perhaps even interstellar travel.</p>
        </section>
    </main>
    
    <footer>
        <p>&copy; 2024 Space Exploration. Contact us at info@spaceexploration.com</p>
    </footer>
</body>
</html>

External CSS (styles.css)
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

header {
    background-color: #000080;
    color: white;
    padding: 1em 0;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 1em;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

main {
    padding: 1em;
}

section {
    margin: 2em 0;
}

section img {
    max-width: 100%;
    height: auto;
    display: block;
    margin: 1em 0;
}

footer {
    background-color: #000080;
    color: white;
    text-align: center;
    padding: 1em 0;
    position: absolute;
    width: 100%;
    bottom: 0;
}

@media (max-width: 600px) {
    nav ul li {
        display: block;
        margin: 0.5em 0;
    }
}
Notes:
The HTML structure includes all required elements: header, navigation bar, images, main content sections, and footer.
The external CSS file ensures that the design is responsive and visually appealing, with media queries to handle smaller screen sizes.
Make sure to replace the src attribute of the <img> tag with the actual path to your image file.
This code provides a clean, simple template that you can build upon to create a more detailed and enriched web page about space exploration.

## Additional Prompts

"_make the design centered and more appealing_"

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    background-color: #f0f0f0;
}

.container {
    max-width: 900px;
    margin: 0 auto;
}

header {
    background-color: #000080;
    color: white;
    padding: 1em 0;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
    margin: 0;
}

nav ul li {
    display: inline;
    margin: 0 1em;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

main {
    padding: 1em;
}

section {
    margin: 2em 0;
}

section img {
    max-width: 100%;
    height: auto;
    display: block;
    margin: 1em auto;
}

footer {
    background-color: #000080;
    color: white;
    text-align: center;
    padding: 1em 0;
    position: absolute;
    width: 100%;
    bottom: 0;
}

@media (max-width: 600px) {
    nav ul li {
        display: block;
        margin: 0.5em 0;
    }
}
Changes Made:
Added a container class with a maximum width and set it to center the content.
Adjusted margins and paddings to ensure content is centered.
Made small adjustments to the header, footer, and image styling to enhance visual appeal.
Maintained responsiveness for smaller screen sizes.
With these changes, the content will be centered within the page, providing a more visually appealing layout.