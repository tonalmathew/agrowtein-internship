# Day 1 Homework Task

### Project: Personal Portfolio Page

Task: Create a simple personal portfolio page using only HTML. The page should include the following sections:

1. Header with your name
2. Navigation menu
3. About Me section
4. Skills section
5. Projects section (with at least two project entries)
6. Contact information
7. Footer


### Requirements:

- Use appropriate HTML5 semantic tags
- Include at least one table
- Use an unordered list and an ordered list
- Add at least one image
- Include a hyperlink to an external website
- Use appropriate headings (h1, h2, etc.)
- Add comments to explain the purpose of different sections


### Here's a basic structure to get them started:

```html
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Your Name - Portfolio</title>
    </head>
    <body>
        <!-- Header -->
        <header>
            <h1>Your Name</h1>
            <!-- Navigation -->
            <nav>
                <ul>
                    <li><a href="#about">About</a></li>
                    <li><a href="#skills">Skills</a></li>
                    <li><a href="#projects">Projects</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </header>

        <!-- Main content -->
        <main>
            <!-- About section -->
            <section id="about">
                <h2>About Me</h2>
                <p>Write a brief introduction about yourself here.</p>
            </section>

            <!-- Skills section -->
            <section id="skills">
                <h2>Skills</h2>
                <!-- Add your skills here using an unordered list -->
            </section>

            <!-- Projects section -->
            <section id="projects">
                <h2>Projects</h2>
                <!-- Add your projects here. Use article tags for each project -->
            </section>

            <!-- Contact section -->
            <section id="contact">
                <h2>Contact</h2>
                <!-- Add your contact information here -->
            </section>
        </main>

        <!-- Footer -->
        <footer>
            <p>&copy; 2025 Your Name. All rights reserved.</p>
        </footer>
    </body>
    </html>
```

### Submission Instructions:

1. Complete the HTML file with your personal information.
2. Make sure to fulfill all the requirements listed above.
3. Save the file as `index.html`.
4. Submit the file before the next class.


### Bonus Challenge:

- Add a simple form in the contact section (remember, we're not processing the form, just creating the HTML structure).
- Use the `<figure>` and `<figcaption>` tags for your image.
- Implement a table to showcase your education or work experience.
