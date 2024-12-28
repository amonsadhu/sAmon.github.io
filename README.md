<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Technical Projects</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --bg-color: #f8ebe8; /* Beige */
            --primary-color: #f7c6d9; /* Light Pink */
            --text-color: #333;
            --accent-color: #d9a6b3; /* Soft Pink */
        }

        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: var(--bg-color);
            color: var(--text-color);
        }

        header {
            background-color: var(--primary-color);
            padding: 20px 0;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        header h1 {
            margin: 0;
            font-size: 2.5rem;
            color: var(--text-color);
        }

        main {
            max-width: 800px;
            margin: 40px auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        section {
            margin-bottom: 30px;
        }

        section h2 {
            font-size: 2rem;
            margin-bottom: 10px;
            color: var(--accent-color);
        }

        .project {
            margin-bottom: 20px;
        }

        .project h3 {
            font-size: 1.5rem;
            margin: 0;
        }

        .project p {
            margin: 5px 0 15px;
        }

        .project a {
            text-decoration: none;
            color: var(--primary-color);
            font-weight: bold;
        }

        .code-snippet {
            background-color: #f4f4f4;
            padding: 10px;
            border-left: 4px solid var(--primary-color);
            font-family: 'Courier New', Courier, monospace;
            margin: 15px 0;
            overflow-x: auto;
        }

        footer {
            text-align: center;
            padding: 10px 0;
            background-color: var(--primary-color);
            margin-top: 20px;
            color: var(--text-color);
        }

        footer a {
            color: var(--accent-color);
            text-decoration: none;
        }

        @media (max-width: 600px) {
            header h1 {
                font-size: 2rem;
            }

            section h2 {
                font-size: 1.5rem;
            }

            .project h3 {
                font-size: 1.2rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>My Technical Projects</h1>
    </header>

    <main>
        <section>
            <h2>About Me</h2>
            <p>Hello! I am a computer science and electronics student passionate about building impactful projects. Below are three of my favorite technical projects.</p>
        </section>

        <section>
            <h2>Projects</h2>
            <div class="project">
                <h3>Project 1: Virtual Herbal Garden</h3>
                <p>An interactive platform showcasing medicinal plants used in AYUSH systems of healthcare.</p>
                <div class="code-snippet">
                    <pre><code>// Sample Code from the Project
function displayPlantInfo(plant) {
    console.log(`Plant Name: ${plant.name}`);
    console.log(`Medicinal Uses: ${plant.uses}`);
}
                    </code></pre>
                </div>
                <a href="https://github.com/yourusername/virtual-herbal-garden" target="_blank">View on GitHub</a>
            </div>
            <div class="project">
                <h3>Project 2: SwasthTick</h3>
                <p>A web application promoting sustainable industry practices with actionable insights.</p>
                <div class="code-snippet">
                    <pre><code>// Sample Data Visualization Code
const chartData = {
    labels: ['Energy', 'Water', 'Waste'],
    datasets: [{
        data: [40, 30, 30],
        backgroundColor: ['#f7c6d9', '#d9a6b3', '#f8ebe8']
    }]
};
createPieChart(chartData);
                    </code></pre>
                </div>
                <a href="https://github.com/yourusername/sustainable-dashboard" target="_blank">View on GitHub</a>
            </div>
            <div class="project">
                <h3>Project 3: TriRobo</h3>
                <p>A portal helping students find internships and job opportunities tailored to their profiles.</p>
                <div class="code-snippet">
                    <pre><code>// Example API Call from the Project
fetch('https://api.example.com/internships')
    .then(response => response.json())
    .then(data => console.log(data));
                    </code></pre>
                </div>
                <a href="https://github.com/yourusername/internship-finder" target="_blank">View on GitHub</a>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 <a href="https://github.com/Amon Sadhu" target="_blank">Amon</a>. All rights reserved.</p>
    </footer>
</body>
</html>
