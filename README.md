<!DOCTYPE html>
<html>
<head>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            color: #333;
            line-height: 1.6;
        }
        .header {
            text-align: center;
            margin-bottom: 30px;
        }
        h1 {
            color: #2c3e50;
            margin-bottom: 10px;
        }
        h2 {
            color: #3498db;
            border-bottom: 2px solid #f1f1f1;
            padding-bottom: 5px;
        }
        h3 {
            color: #9b59b6;
        }
        .badge-container {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin: 15px 0;
        }
        .badge {
            padding: 6px 12px;
            border-radius: 20px;
            font-size: 14px;
            font-weight: bold;
            color: white;
            text-decoration: none;
            display: inline-block;
        }
        .social-links {
            display: flex;
            justify-content: center;
            gap: 15px;
            margin: 25px 0;
        }
        .social-link {
            padding: 10px 20px;
            border-radius: 5px;
            text-decoration: none;
            color: white;
            font-weight: bold;
            transition: transform 0.3s;
        }
        .social-link:hover {
            transform: translateY(-3px);
        }
        .quote {
            font-style: italic;
            text-align: center;
            margin: 20px 0;
            padding: 15px;
            background-color: #f9f9f9;
            border-left: 4px solid #3498db;
        }
        .goals {
            list-style-type: none;
            padding-left: 0;
        }
        .goals li {
            margin-bottom: 10px;
            padding-left: 25px;
            position: relative;
        }
        .goals li:before {
            content: "🎯";
            position: absolute;
            left: 0;
        }
        .footer {
            text-align: center;
            margin-top: 30px;
            padding-top: 15px;
            border-top: 1px solid #eee;
            font-size: 14px;
            color: #777;
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>👋 Hi there, I'm Laras Agustin</h1>
        <h3>✨ Laravel Developer from Indonesia ✨</h3>
        <div class="badge-container">
            <span class="badge" style="background-color: #777BB4;">PHP Developer</span>
            <span class="badge" style="background-color: #FF2D20;">Laravel Enthusiast</span>
            <span class="badge" style="background-color: #9b59b6;">Web Development</span>
            <span class="badge" style="background-color: #3498db;">Full Stack Learner</span>
        </div>
    </div>

    <hr>

    <h2>🎯 About Me</h2>
    <p>Halo! Aku Laras, seorang Laravel enthusiast dari Indonesia!</p>
    <ul>
        <li><strong>💻 Tech Stack:</strong> PHP, Laravel, HTML, CSS, JavaScript</li>
        <li><strong>🚀 Sedang fokus:</strong> Tugas Akhir</li>
        <li><strong>🎵 Coding vibe:</strong> Sambil dengerin lagu chill biar fokus</li>
        <li><strong>💫 Goal:</strong> Jadi Full-Stack Developer yang handal!</li>
    </ul>
    
    <div class="quote">
        "Progress, not perfection!" ✨
    </div>

    <h2>🛠️ Tech Stack</h2>
    <div class="badge-container">
        <span class="badge" style="background-color: #777BB4;">PHP</span>
        <span class="badge" style="background-color: #FF2D20;">Laravel</span>
        <span class="badge" style="background-color: #E34F26;">HTML5</span>
        <span class="badge" style="background-color: #1572B6;">CSS3</span>
        <span class="badge" style="background-color: #F7DF1E; color: black;">JavaScript</span>
        <span class="badge" style="background-color: #4479A1;">MySQL</span>
        <span class="badge" style="background-color: #F05032;">Git</span>
        <span class="badge" style="background-color: #181717;">GitHub</span>
    </div>

    <h2>🌟 Current Goals</h2>
    <ul class="goals">
        <li>Buat portfolio website personal</li>
        <li>Bangun project real dengan PHP & Laravel</li>
        <li>Pelajari React.js untuk frontend</li>
        <li>Kontribusi ke open source project</li>
    </ul>

    <h2>🌟 Let's Be Friends!</h2>
    <div class="social-links">
        <a href="https://instagram.com/0lag8_" target="_blank" class="social-link" style="background-color: #E4405F;">Instagram</a>
        <a href="mailto:agstinin0128@gmail.com" class="social-link" style="background-color: #D14836;">Email</a>
        <a href="https://github.com/larasagustin" target="_blank" class="social-link" style="background-color: #181717;">GitHub</a>
    </div>

    <div class="footer">
        <p>Made with ❤️ by Laras Agustin</p>
    </div>
</body>
</html>
