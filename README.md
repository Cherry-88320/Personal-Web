<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>[Your Name] | Portfolio</title>
    <style>
        :root {
            --bg-color: #f8fafc;
            --text-color: #0f172a;
            --accent-color: #2563eb;
            --card-bg: #ffffff;
        }
        body {
            font-family: system-ui, -apple-system, sans-serif;
            line-height: 1.6;
            background-color: var(--bg-color);
            color: var(--text-color);
            margin: 0;
            padding: 0;
        }
        header, section, footer {
            max-width: 800px;
            margin: 0 auto;
            padding: 2rem 1rem;
        }
        .hero { text-align: center; padding: 4rem 1rem; }
        .hero h1 { font-size: 2.5rem; margin-bottom: 0.5rem; }
        .accent { color: var(--accent-color); }
        .btn {
            display: inline-block;
            background: var(--accent-color);
            color: white;
            padding: 0.75rem 1.5rem;
            text-decoration: none;
            border-radius: 0.5rem;
            font-weight: bold;
            margin-top: 1rem;
        }
        .project-card {
            background: var(--card-bg);
            padding: 1.5rem;
            border-radius: 0.75rem;
            box-shadow: 0 4px 6px -1px rgba(0,0,0,0.1);
            margin-bottom: 1.5rem;
        }
        .links a { margin-right: 1rem; color: var(--accent-color); text-decoration: none; font-weight: 500; }
        .links a:hover { text-decoration: underline; }
    </style>
</head>
<body>

    <header class="hero">
        <h1>Hi, I'm <span class="accent">[Your Name]</span></h1>
        <p style="font-size: 1.25rem;">A passionate <strong>[Your Profession]</strong> focused on building impactful digital experiences.</p>
        <div class="links">
            <a href="#">LinkedIn</a> | <a href="#">GitHub</a> | <a href="#">Resume</a>
        </div>
        <a href="mailto:your.email@email.com" class="btn">Get In Touch</a>
    </header>

    <hr style="border: 0; border-top: 1px solid #e2e8f0;">

    <section id="about">
        <h2>About Me</h2>
        <p>I specialize in bridging the gap between complex problems and seamless user experiences. With a background in [Your Field], I love writing clean code, collaborating with cross-functional teams, and continuously learning new technologies.</p>
    </section>

    <section id="projects">
        <h2>Featured Projects</h2>
        
        <div class="project-card">
            <h3>🚀 Project One Name</h3>
            <p><strong>The Challenge:</strong> Briefly describe the problem you were trying to solve here.</p>
            <p><strong>The Solution:</strong> Explain the tech stack used and your core implementation.</p>
            <p><strong>The Result:</strong> Quantify the success (e.g., "Boosted user engagement by 25%").</p>
            <div class="links">
                <a href="#">Live Demo &rarr;</a>
                <a href="#">View Code &rarr;</a>
            </div>
        </div>

        <div class="project-card">
            <h3>🛠️ Project Two Name</h3>
            <p><strong>The Challenge:</strong> Briefly describe the problem you were trying to solve here.</p>
            <p><strong>The Solution:</strong> Explain the tech stack used and your core implementation.</p>
            <p><strong>The Result:</strong> Quantify the success.</p>
            <div class="links">
                <a href="#">Live Demo &rarr;</a>
                <a href="#">View Code &rarr;</a>
            </div>
        </div>
    </section>

    <footer style="text-align: center; color: #64748b; font-size: 0.875rem;">
        <p>&copy; 2026 [Your Name]. Built with precision.</p>
    </footer>

</body>
</html>
