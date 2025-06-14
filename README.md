<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Dinh Duong - Backend Developer & AI Enthusiast</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;500;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #1c1c1c;
            color: white;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        h1 {
            text-align: center;
            color: #ff5722;
            font-size: 3rem;
            margin-bottom: 30px;
        }

        h2 {
            color: #ff5722;
            font-size: 2rem;
            margin-bottom: 15px;
        }

        .tech-stack {
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 20px;
            flex-wrap: wrap;
            margin-bottom: 40px;
        }

        .tech-stack img {
            border-radius: 10px;
            transition: all 0.3s ease;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.1);
        }

        .tech-stack img:hover {
            transform: scale(1.1);
            box-shadow: 0 0 20px rgba(255, 87, 34, 0.4);
        }

        .project {
            margin-bottom: 40px;
            padding: 20px;
            background-color: #333;
            border-radius: 10px;
        }

        .project h3 {
            color: #ff5722;
            margin-bottom: 15px;
        }

        .project p {
            color: #ddd;
            margin-bottom: 10px;
        }

        .project a {
            color: #ff5722;
            text-decoration: none;
            font-weight: bold;
        }

        .github-stats {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-bottom: 40px;
        }

        .github-stats img {
            width: 100%;
            max-width: 500px;
            border-radius: 10px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.2);
        }

        .contact {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-bottom: 40px;
        }

        .contact a {
            color: #ff5722;
            font-size: 1.2rem;
            text-decoration: none;
        }

        .contact a:hover {
            text-decoration: underline;
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: #111;
            color: #999;
        }

        .fun-fact {
            font-style: italic;
            text-align: center;
            margin-top: 40px;
            color: #ff9800;
        }

        .github-stats,
        .tech-stack {
            gap: 30px;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Hi there, I'm Dinh Duong 👋</h1>
            <p>I am a passionate <strong>Backend Developer</strong> and <strong>AI Enthusiast</strong> who thrives on building scalable systems and creating intelligent solutions. I specialize in high-performance backend architectures and developing machine learning models. Let's connect and innovate together!</p>
        </header>

        <section>
            <h2>🔧 Tech Stack</h2>

            <h3>Backend Development</h3>
            <div class="tech-stack">
                <img src="https://img.shields.io/badge/Laravel-%23FF2D20.svg?style=for-the-badge&logo=laravel&logoColor=white&labelColor=transparent" alt="Laravel" title="Laravel: A PHP framework for building robust web applications.">
                <img src="https://img.shields.io/badge/NestJS-%23E0234E.svg?style=for-the-badge&logo=nestjs&logoColor=white&labelColor=transparent" alt="NestJS" title="NestJS: A progressive Node.js framework for building efficient, reliable, and scalable server-side applications.">
                <img src="https://img.shields.io/badge/Spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white&labelColor=transparent" alt="Spring" title="Spring: A powerful Java-based framework for creating enterprise-grade applications.">
            </div>

            <h3>Artificial Intelligence</h3>
            <div class="tech-stack">
                <img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" alt="Python">
                <img src="https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=tensorflow&logoColor=white" alt="TensorFlow">
                <img src="https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch">
                <img src="https://img.shields.io/badge/OpenCV-%23FF3C00.svg?style=for-the-badge&logo=opencv&logoColor=white" alt="OpenCV">
                <img src="https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Scikit-learn">
            </div>
        </section>

        <section>
            <h2>🚀 Projects</h2>

            <div class="project">
                <h3>🧠 AI-Powered Personal Assistant</h3>
                <p>A <strong>machine learning-based assistant</strong> to streamline daily tasks, from email filtering to scheduling and answering queries. Built using <strong>TensorFlow</strong>, <strong>Python</strong>, and <strong>NLP</strong> techniques.</p>
                <p><strong>Tech Stack:</strong> Python, TensorFlow, Scikit-learn, Flask</p>
                <a href="https://github.com/yourusername/ai-assistant" target="_blank">View Project</a>
            </div>

            <div class="project">
                <h3>💻 Scalable E-commerce Backend</h3>
                <p>A fully-featured, <strong>high-performance backend</strong> for an e-commerce platform. This project supports thousands of concurrent users and integrates with payment services and user authentication.</p>
                <p><strong>Tech Stack:</strong> Node.js, NestJS, MongoDB, Redis, AWS</p>
                <a href="https://github.com/yourusername/ecommerce-backend" target="_blank">View Project</a>
            </div>
        </section>

        <section class="github-stats">
            <img src="https://github-readme-stats.vercel.app/api?username=DinhDuong1610&theme=dark&hide_border=true&show_icons=true" alt="DinhDuong1610's GitHub Stats">
            <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=DinhDuong1610&theme=dark&hide_border=true&layout=compact" alt="Top Languages">
        </section>

        <section class="contact">
            <a href="https://www.linkedin.com/in/dinhduong" target="_blank">LinkedIn</a>
            <a href="mailto:youremail@example.com">Email</a>
            <a href="https://facebook.com/yourprofile" target="_blank">Facebook</a>
            <a href="https://www.tiktok.com/@yourprofile" target="_blank">TikTok</a>
        </section>

        <footer>
            <p class="fun-fact">I believe in the power of <strong>AI</strong> to solve real-world problems and the beauty of <strong>backend systems</strong> in delivering seamless user experiences. Constantly learning and exploring new technologies to stay ahead of the curve. Let's code the future!</p>
        </footer>
    </div>
</body>
</html>
