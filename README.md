<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Profile Card</title>
<style>
    body {
        font-family: Arial, sans-serif;
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
        margin: 0;
        background-color: #f3f4f6;
    }
    .card {
        background: #fff;
        border-radius: 10px;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        width: 300px;
        padding: 20px;
        text-align: center;
    }
    .card h2 {
        margin: 0;
        color: #333;
    }
    .card p {
        color: #777;
        margin: 10px 0;
    }
    .card ul {
        list-style: none;
        padding: 0;
        margin: 20px 0;
    }
    .card ul li {
        margin: 8px 0;
    }
    .card ul li span {
        font-weight: bold;
        color: #555;
    }
    .social-icons a {
        margin: 0 10px;
        color: #555;
        text-decoration: none;
    }
    .social-icons a:hover {
        color: #333;
    }
</style>
</head>
<body>

<div class="card">
    <h2>Hi there 👋</h2>
    <p>I'm Guilherme Krüger Andrade, a UI/UX designer, frontend developer, and musician.</p>
    
    <ul>
        <li><span>🔭 Currently working on:</span> Frontend & UI/UX design</li>
        <li><span>🌱 Learning:</span> Advanced CSS & JavaScript frameworks</li>
        <li><span>👯 Open to collaborate on:</span> Creative design projects</li>
        <li><span>💬 Ask me about:</span> UI/UX, frontend dev, and music</li>
    </ul>
    
    <div class="social-icons">
        <a href="mailto:your-email@example.com">📧 Email</a>
        <a href="https://www.linkedin.com/in/your-linkedin" target="_blank">LinkedIn</a>
    </div>
</div>

</body>
</html>
