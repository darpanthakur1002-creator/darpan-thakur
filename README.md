<div align="center">
  <img height="150" src="https://media.giphy.com/media/M9gbBd9nbDrOTu1Mqx/giphy.gif"  />
</div>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
    <title>Darpan Thakur | Portfolio</title>

    <style>
        *{
            margin:0;
            padding:0;
            box-sizing:border-box;
            font-family:Arial, sans-serif;
        }

        body{
            background:#0f172a;
            color:white;
            line-height:1.6;
        }

        nav{
            display:flex;
            justify-content:space-between;
            align-items:center;
            padding:20px 10%;
            background:#111827;
            position:sticky;
            top:0;
        }

        nav h1{
            color:#38bdf8;
        }

        nav ul{
            display:flex;
            list-style:none;
            gap:20px;
        }

        nav a{
            text-decoration:none;
            color:white;
            transition:0.3s;
        }

        nav a:hover{
            color:#38bdf8;
        }

        .hero{
            height:90vh;
            display:flex;
            justify-content:center;
            align-items:center;
            text-align:center;
            flex-direction:column;
            padding:20px;
        }

        .hero h2{
            font-size:50px;
        }

        .hero span{
            color:#38bdf8;
        }

        .hero p{
            margin-top:15px;
            max-width:600px;
            color:#cbd5e1;
        }

        .btn{
            margin-top:25px;
            display:inline-block;
            padding:12px 25px;
            background:#38bdf8;
            color:black;
            border-radius:8px;
            text-decoration:none;
            font-weight:bold;
        }

        section{
            padding:80px 10%;
        }

        .title{
            text-align:center;
            margin-bottom:40px;
            font-size:35px;
            color:#38bdf8;
        }

        .about p{
            text-align:center;
            max-width:700px;
            margin:auto;
            color:#cbd5e1;
        }

        .skills-container{
            display:grid;
            grid-template-columns:repeat(auto-fit,minmax(150px,1fr));
            gap:20px;
        }

        .skill{
            background:#1e293b;
            padding:20px;
            text-align:center;
            border-radius:10px;
            transition:0.3s;
        }

        .skill:hover{
            transform:translateY(-5px);
            background:#334155;
        }

        .projects-container{
            display:grid;
            grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
            gap:25px;
        }

        .project{
            background:#1e293b;
            padding:25px;
            border-radius:12px;
            transition:0.3s;
        }

        .project:hover{
            transform:scale(1.03);
        }

        .project h3{
            color:#38bdf8;
            margin-bottom:10px;
        }

        .contact{
            text-align:center;
        }

        .contact p{
            margin:10px 0;
            color:#cbd5e1;
        }

        footer{
            text-align:center;
            padding:20px;
            background:#111827;
            margin-top:40px;
            color:#94a3b8;
        }

        @media(max-width:768px){
            .hero h2{
                font-size:35px;
            }

            nav{
                flex-direction:column;
                gap:15px;
            }
        }
    </style>
</head>

<body>

    <nav>
        <h1>Darpan.</h1>

        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <section class="hero">
        <h2>Hello, I'm <span>Darpan Thakur</span></h2>

        <p>
            Diploma student passionate about Web Development,
            Java, Full Stack Development and modern technologies.
        </p>

        <a href="#projects" class="btn">View Projects</a>
    </section>

    <section class="about" id="about">
        <h2 class="title">About Me</h2>

        <p>
            I am a passionate developer who loves building websites,
            learning new technologies and improving programming skills.
            Currently learning Java, Frontend and Full Stack Development.
        </p>
    </section>

    <section id="skills">
        <h2 class="title">Skills</h2>

        <div class="skills-container">
            <div class="skill">HTML</div>
            <div class="skill">CSS</div>
            <div class="skill">JavaScript</div>
            <div class="skill">Java</div>
            <div class="skill">GitHub</div>
            <div class="skill">Responsive Design</div>
        </div>
    </section>

    <section id="projects">
        <h2 class="title">Projects</h2>

        <div class="projects-container">

            <div class="project">
                <h3>Portfolio Website</h3>
                <p>
                    Personal responsive portfolio website using HTML and CSS.
                </p>
            </div>

            <div class="project">
                <h3>Wallpaper Web App</h3>
                <p>
                    Website for browsing and downloading wallpapers.
                </p>
            </div>

            <div class="project">
                <h3>Java Mini Project</h3>
                <p>
                    Beginner Java project for learning OOP concepts.
                </p>
            </div>

        </div>
    </section>

    <section class="contact" id="contact">
        <h2 class="title">Contact</h2>

        <p>Email: darpanthakur1028@gmail.com</p>
        <p>Phone: 8459488744</p>

        <a class="btn" href="https://github.com/">
            Visit GitHub
        </a>
    </section>

    <footer>
        <p>© 2026 Darpan Thakur | All Rights Reserved</p>
    </footer>

</body>
</html>

![image alt](https://github.com/darpanthakur1002-creator/darpan-thakur/blob/a82688b2e722d5ba1fdce0a69913a0a7ec08f592/Screenshot%202026-05-21%20011339.png)
    <header>
        <h1>Darpan Thakur</h1>
        <p>Frontend Developer | Java Learner | Student</p>
    </header>
<p align="left">✨ Creating bugs since ...<br>📚 I'm currently learning ...<br>🎯 Goals: ...<br>🎲 Fun fact: ...</p>

   <h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://developer.android.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/android/android-original-wordmark.svg" alt="android" width="40" height="40"/> </a> <a href="https://www.blender.org/" target="_blank" rel="noreferrer"> <img src="https://download.blender.org/branding/community/blender_community_badge_white.svg" alt="blender" width="40" height="40"/> </a> <a href="https://www.cprogramming.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="c" width="40" height="40"/> </a> <a href="https://www.w3schools.com/cpp/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40"/> </a> <a href="https://www.figma.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="figma" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://www.adobe.com/in/products/illustrator.html" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/adobe_illustrator/adobe_illustrator-icon.svg" alt="illustrator" width="40" height="40"/> </a> <a href="https://www.java.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/> </a> <a href="https://www.linux.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/> </a> <a href="https://www.mathworks.com/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" alt="matlab" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://unity.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/unity3d/unity3d-icon.svg" alt="unity" width="40" height="40"/> </a> <a href="https://unrealengine.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/kenangundogan/fontisto/036b7eca71aab1bef8e6a0518f7329f13ed62f6b/icons/svg/brand/unreal-engine.svg" alt="unreal" width="40" height="40"/> </a> </p> <section class="about">
        <h2>About Me</h2>
        <p>
            I am a diploma student and passionate web developer.
            I love creating websites and learning Java, Full Stack,
            and modern technologies.
        </p>
    </section>

    <section class="skills">
        <h2>Skills</h2>
        <ul>
            <li>HTML</li>
            <li>CSS</li>
            <li>JavaScript</li>
            <li>Java</li>
            <li>GitHub</li>
        </ul>
    </section>

    <section class="projects">
        <h2>Projects</h2>

        <div class="card">
            <h3>Portfolio Website</h3>
            <p>A responsive personal portfolio website.</p>
        </div>

        <div class="card">
            <h3>Wallpaper Web App</h3>
            <p>A website for downloading wallpapers.</p>
        </div>
    </section>

    <section class="contact">
        <h2>Contact</h2>
        <p>Email: darpanthakur1028@gmail.com</p>
        <p>Phone: 8459488744</p>
    </section>

    <footer>
        <p>© 2026 Darpan Thakur</p>
    </footer>

</body>
</html>
