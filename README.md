<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --baby-pink: #f7c6d9;
            --dark-beige: #d9bba5;
            --light-beige: #f8ebe8;
            --text-pink: #d08c9a;
            --white: #ffffff;
        }

        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: var(--white);
        }

        header {
            background-color: var(--baby-pink);
            padding: 20px 0;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        header h1 {
            margin: 0;
            font-size: 2.5rem;
            color: var(--white);
        }

        h1 {
            text-align: center;
            color: var(--baby-pink);
            font-size: 3rem;
            margin-top: 20px;
        }

        .description-box {
            background-color: var(--dark-beige);
            color: var(--white);
            margin: 20px auto;
            padding: 20px;
            max-width: 800px;
            border-radius: 10px;
            text-align: center;
        }

        h2 {
            text-align: center;
            color: var(--text-pink);
            font-size: 2.5rem;
            margin: 40px 0 20px;
        }

        .sub-heading {
            background-color: var(--light-beige);
            color: var(--dark-beige);
            padding: 10px;
            margin-left: 20px;
            display: inline-block;
            border-radius: 5px;
            font-weight: bold;
        }

        .project-box {
            background-color: var(--light-beige);
            color: var(--text-pink);
            margin: 20px auto;
            padding: 15px;
            max-width: 600px;
            border-radius: 8px;
            text-align: center;
            font-weight: bold;
            font-size: 1.2rem;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        footer {
            text-align: center;
            padding: 10px 0;
            background-color: var(--baby-pink);
            margin-top: 20px;
            color: var(--white);
        }

        footer a {
            color: var(--white);
            text-decoration: none;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Portfolio</h1>
    </header>

    <h1>Your Name</h1>

    <div class="description-box">
        Hello! I am a computer science and electronics student with a keen interest in building impactful projects. I specialize in web development, software engineering, and data analysis. My passion lies in creating innovative solutions to real-world problems through technology. With a strong foundation in programming and a creative mindset, I am constantly exploring new technologies and frameworks to enhance my skills and broaden my horizons.
    </div>

    <h2>My Technical Projects</h2>

    <div class="sub-heading">Projects</div>

    <div class="project-box">Virtual Herbal Garden</div>
    <div class="project-box">Sustainable Development Dashboard</div>
    <div class="project-box">Internship Finder</div>

    <footer>
        <p>&copy; 2024 <a href="https://github.com/Amon Sadhu" target="_blank">Amon</a>. All rights reserved.</p>
    </footer>
</body>
</html>
