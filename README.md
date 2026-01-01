<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Rui Niles – CV</title>


<style>
    /* ---------- THEME VARIABLES ---------- */
    :root {
        --bg: #ffffff;
        --text: #1b1b1b;
        --subtle-text: #555;
        --link: #005fcc;
        --border: #e5e5e5;

        --section-bg: #f7f9fc;     
        --card-bg: #fafafa;
    }

    @media (prefers-color-scheme: dark) {
        :root {
            --bg: #111;
            --text: #f0f0f0;
            --subtle-text: #bbbbbb;
            --link: #4da3ff;
            --border: #2a2a2a;

            --section-bg: #1a1a1a;
            --card-bg: #181818;
        }
    }

    /* ---------- BASE STYLING ---------- */
    body {
        font-family: Arial, Helvetica, sans-serif;
        background: var(--bg);
        color: var(--text);
        margin: 40px auto;
        max-width: 800px;
        line-height: 1.6;
    }

    h1 {
        text-align: center;
        font-size: 36px;
        margin-bottom: 0;
        letter-spacing: 1px;
    }

    .subtitle {
        text-align: center;
        font-size: 18px;
        margin-top: 5px;
        color: var(--subtle-text);
    }

    .links {
        text-align: center;
        margin: 10px 0 30px;
    }

    .links a {
        color: var(--link);
        text-decoration: none;
        margin: 0 10px;
        font-weight: 500;
    }

    .links a:hover {
        text-decoration: underline;
    }

    /* ---------- SECTION HEADERS ---------- */
    h2 {
        background: var(--section-bg);
        padding: 10px 12px;
        border-left: 5px solid var(--link);
        margin-top: 40px;
        text-transform: uppercase;
        font-size: 20px;
        letter-spacing: 0.5px;
    }

    /* ---------- CARD / BLOCK STYLING ---------- */
    .block {
        background: var(--card-bg);
        padding: 15px 20px;
        border-radius: 8px;
        margin-top: 15px;
        border: 1px solid var(--border);
    }

    ul {
        padding-left: 20px;
    }

    .job-title {
        font-weight: bold;
        font-size: 18px;
    }

    .company {
        font-style: italic;
        color: var(--subtle-text);
    }

    .date-location {
        color: var(--subtle-text);
        margin-bottom: 8px;
    }

    .education-title {
        font-weight: bold;
        font-size: 17px;
    }
</style>
</head>

<body>

<h1>Rui Niles</h1>
<p class="subtitle">Software Developer</p>

<div class="links">
    <a href="mailto:ruiniles141@gmail.com">Email</a> |
    <a href="https://www.linkedin.com/in/rui-niles-829b371b9/">LinkedIn</a> |
    <a href="https://github.com/RuiNiles/">GitHub</a>
</div>

<h2>Summary</h2>
<p>Detail‑oriented backend developer with strong expertise in Java and Kotlin, along with deep experience in Spring Boot and HK2. Skilled in designing APIs, integrating CI/CD pipelines, and working with containerised environments. Committed to writing clean, maintainable code and collaborating effectively in agile teams.</p>

<h2>Skills</h2>
<ul>
    <li><strong>Languages:</strong> Java, Kotlin</li>
    <li><strong>Frameworks:</strong> Spring Boot, HK2</li>
    <li><strong>Database:</strong> OracleDB, Flyway</li>
    <li><strong>Tools:</strong> Docker, Kubernetes, Git, TeamCity, GoCD, Splunk</li>
    <li><strong>Cloud:</strong> GCP</li>
    <li><strong>Other:</strong> ActiveMQ, Kafka</li>
</ul>

<h2>Experience</h2>

<p class="job-title">Software Engineer</p>
<p class="company">Sky UK — London</p>
<p class="date-location">09/2023 – Present</p>
<ul>
    <li>Delivered projects introducing new provisioning systems for broadband and telephony services in the Republic of Ireland and Italy.</li>
    <li>Supported critical application releases and ensured system stability.</li>
    <li>Onboarded and mentored newly hired developers.</li>
</ul>

<p class="job-title">Software Developer Internship</p>
<p class="company">Sky UK — London</p>
<p class="date-location">09/2021 – 09/2022</p>
<ul>
    <li>Developed and maintained internet and telephony provisioning systems for UK customers.</li>
    <li>Collaborated in a highly agile environment, utilising pair programming and continuous feedback cycles.</li>
    <li>Assisted with recruitment and technical evaluations for new interns.</li>
</ul>

<h2>Certifications</h2>
<ul>
    <li>Certified SAFe® 6 Practitioner (2024–2025)</li>
</ul>

<h2>Education</h2>
<p class="education-title">BSc Computer Science with a Year in Industry — First (Distinction)</p>
<p class="date-location">2019 – 2023 — University of Kent</p>

</body>
</html>
