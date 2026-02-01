<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aryan Srideep | Portfolio</title>
    <style>
        :root {
            --primary-blue: #0077b5;
            --ieee-blue: #00629b;
            --dark-gray: #333;
            --light-bg: #f8f9fa;
            --white: #ffffff;
        }

        body {
            font-family: 'Segoe UI', Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            background-color: var(--light-bg);
            color: var(--dark-gray);
        }

        header {
            background: var(--white);
            padding: 3rem 1rem;
            text-align: center;
            border-bottom: 4px solid var(--primary-blue);
        }

        .container {
            max-width: 900px;
            margin: 2rem auto;
            padding: 0 1.5rem;
        }

        .card {
            background: var(--white);
            padding: 2rem;
            border-radius: 12px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.05);
            margin-bottom: 2rem;
        }

        h1 { margin: 0; color: var(--primary-blue); font-size: 2.5rem; }
        h2 { color: var(--primary-blue); border-bottom: 2px solid #eee; padding-bottom: 10px; margin-top: 0; }
        h3 { margin-bottom: 5px; color: #444; }
        h4 { margin: 10px 0 5px 0; color: var(--ieee-blue); font-size: 1.1rem; }

        /* Links & Buttons */
        a { text-decoration: none; color: var(--primary-blue); transition: 0.3s; }
        .btn {
            display: inline-block;
            background: var(--primary-blue);
            color: white !important;
            padding: 12px 25px;
            border-radius: 25px;
            font-weight: bold;
            margin-top: 15px;
        }
        .btn:hover { opacity: 0.9; transform: translateY(-2px); }

        /* Societies Sub-section */
        .society-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 15px;
            margin-top: 15px;
        }
        .society-item {
            background: #f0f7ff;
            padding: 15px;
            border-radius: 8px;
            border: 1px solid #d0e3ff;
        }

        /* Skills Styling */
        .skills-container {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }
        .skill-badge {
            background: #e1e9ee;
            color: #004182;
            padding: 8px 15px;
            border-radius: 20px;
            font-size: 0.9rem;
            font-weight: 600;
        }

        .list-item {
            margin-bottom: 1.5rem;
            padding-left: 15px;
            border-left: 3px solid #ddd;
        }

        footer { text-align: center; padding: 2rem; color: #888; font-size: 0.9rem; }
    </style>
</head>
<body>

<header>
    <h1>Aryan Srideep</h1>
    <p>Engineering Student at <a href="https://geckkd.ac.in/" target="_blank">GEC Kozhikode</a></p>
    <a href="https://www.linkedin.com/in/aryan-srideep-6a6a4a37b" target="_blank" class="btn">Connect on LinkedIn</a>
</header>

<div class="container">

    <section class="card">
        <h2>Education</h2>
        <div class="list-item">
            <h3>Bachelor of Technology</h3>
            <p><a href="https://geckkd.ac.in/" target="_blank" style="font-weight: bold;">Government Engineering College Kozhikode</a><br>
            Focusing on technical excellence and engineering innovation.</p>
        </div>
    </section>

    <section class="card">
        <h2>Professional Memberships</h2>
        
        <div class="list-item">
            <h3>IEEE & IEEE SB GEC Kozhikode</h3>
            <p>Active member of the <a href="https://www.ieee.org/" target="_blank">IEEE</a> global network and the <a href="https://geckkd.ac.in/ieee.php" target="_blank">Student Branch at GECK</a>.</p>
            
            <h4>Technical Societies & Interest Groups:</h4>
            <div class="society-grid">
                <div class="society-item">
                    <strong>IEEE SIGHT</strong><br>
                    <small>Special Interest Group on Humanitarian Technology</small><br>
                    <a href="https://sight.ieee.org/" target="_blank">Official Site &rarr;</a>
                </div>
                <div class="society-item">
                    <strong>IEEE IAS</strong><br>
                    <small>Industry Applications Society</small><br>
                    <a href="https://ias.ieee.org/" target="_blank">Official Site &rarr;</a>
                </div>
                <div class="society-item">
                    <strong>IEEE RAS</strong><br>
                    <small>Robotics and Automation Society</small><br>
                    <a href="https://www.ieee-ras.org/" target="_blank">Official Site &rarr;</a>
                </div>
            </div>
        </div>

        <div class="list-item" style="margin-top: 2rem;">
            <h3>Other Affiliations</h3>
            <p>
                Member of <a href="https://geckkd.ac.in/iste.php" target="_blank">ISTE GECK Student Chapter</a> and 
                Contributor at <a href="https://mulearn.org/" target="_blank">µLearn GECK</a>.
            </p>
        </div>
    </section>

    <section class="card">
        <h2>Skills</h2>
        <div class="skills-container">
            <span class="skill-badge">Robotics (RAS)</span>
            <span class="skill-badge">Industrial Apps (IAS)</span>
            <span class="skill-badge">Humanitarian Tech (SIGHT)</span>
            <span class="skill-badge">Technical Leadership</span>
            <span class="skill-badge">C/C++</span>
            <span class="skill-badge">HTML/CSS</span>
            <span class="skill-badge">Community Building</span>
        </div>
    </section>

</div>

<footer>
    &copy; 2026 Aryan Srideep | Kozhikode, Kerala
</footer>

</body>
</html>
