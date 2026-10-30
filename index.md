To complete this assignment, you will need to add an images folder to your project directory, place three images inside it, and update your portfolio webpage to display them using the correct <img> attributes (src, alt, width, and height).

Step 1: File & Folder Structure
Make sure your project folder looks like this:

Plaintext
your-project-folder/
│
├── index.html
├── about.html
└── images/
    ├── portfolio-preview.jpg
    ├── coding-workspace.jpg
    └── nature-hike.jpg
(Note: You can use any 3 images of your choice, just make sure to rename or match their filenames in your HTML code below).

Step 2: Updated index.html (Portfolio Page with Images)
Here is your portfolio page updated to include the required Images Section with semantic <figure> and <figcaption> elements, proper image paths, and descriptive alt texts:

HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home - Alex Morgan Portfolio</title>
</head>
<body>

    <!-- Navigation Bar -->
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
            </ul>
        </nav>
        <h1>Welcome to My Portfolio</h1>
        <p>Explore my background, projects, and photo gallery below.</p>
    </header>

    <main>
        <!-- About Me Snippet -->
        <section>
            <h2>About Me</h2>
            <p>Hello! I am Alex Morgan, an aspiring front-end web developer building my skills step by step.</p>
        </section>

        <!-- Images / Gallery Section (Assignment 3.2 Requirement) -->
        <section>
            <h2>My Gallery & Projects</h2>
            <p>Here are a few snapshots representing my work, workspace, and personal interests:</p>

            <!-- Image 1 -->
            <figure>
                <img src="images/portfolio-preview.jpg" alt="Screenshot of a personal portfolio website homepage displayed cleanly on a laptop screen" width="400" height="250">
                <figcaption>Figure 1: My first portfolio website project.</figcaption>
            </figure>

            <!-- Image 2 -->
            <figure>
                <img src="images/coding-workspace.jpg" alt="A well-organized wooden desk setup featuring a dual-monitor computer displaying HTML code, a mechanical keyboard, and a ceramic mug of coffee" width="400" height="250">
                <figcaption>Figure 2: My daily coding workspace setup.</figcaption>
            </figure>

            <!-- Image 3 -->
            <figure>
                <img src="images/nature-hike.jpg" alt="A scenic view of a sunlit mountain hiking trail surrounded by lush green pine trees on a clear weekend morning" width="400" height="250">
                <figcaption>Figure 3: Enjoying nature during a weekend hike.</figcaption>
            </figure>
        </section>

        <!-- External Link Requirement from previous assignments -->
        <section>
            <h2>Helpful Resources</h2>
            <p>Learn more about HTML syntax at <a href="https://developer.mozilla.org" target="_blank" rel="noopener noreferrer">MDN Web Docs</a>.</p>
        </section>
    </main>

    <footer>
        <p>&copy; 2026 Alex Morgan</p>
    </footer>

</body>
</html>
Step 3: Submission Checklist
Images Folder: Ensure a folder named images exists inside your project directory.

Three Images: Verify that at least 3 image files are placed inside the images folder and that their file extensions (e.g., .jpg, .png) match the src paths in your HTML.

Attributes Checked: Confirm that every <img> tag includes:

src="..." (correct relative path pointing to the folder)

alt="..." (meaningful, descriptive alternative text)

width and height properties

Browser Test: Open index.html in your web browser to check that all three images load properly and look neat.

Final Submission: Package your entire project folder (including index.html, about.html, and the images folder) for your submission!