# Portfolio-gallery
Portfolio gallery
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Riya Patel Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <header class="header">
        <h1 id="name">Riya</h1>
        <h1>Patel</h1>
    </header>

    <main>
        <section class="main">
            <div class="about">
                <h2>Hi</h2>
                <h2>I'm Riya, a Frontend Developer</h2>
                <p>
                    I’m Riya Patel, a second-year BTech student at GL Bajaj, Greater Noida with a strong foundation in C,
                    C++, and Python. My journey in tech is complemented by a solid grasp of Data Structures and Algorithms.
                    I also bring creativity to the table with skills in HTML, CSS, and JavaScript. Passionate about
                    problem-solving and continuous learning, I am excited to leverage my diverse skill set to tackle new
                    challenges and contribute to innovative projects.
                </p>
            </div>
            <div class="image">
                <img src="RiyaPatel.jpg" alt="Riya Patel's Photo">
            </div>
        </section>

        <section class="skills">
            <h1>About My Skills</h1>
            <ul id="Skills">
                <li>HTML</li>
                <li>CSS</li>
                <li>JavaScript</li>
                <li>C++</li>
                <li>Python</li>
                <li>Quick Learner</li>
                <li>Good Communication Skills</li>
            </ul>
        </section>

        <section class="projects">
            <!-- Future Projects Go Here -->
        </section>

        <section class="resume common">
            <h1>Resume</h1>
            <ul>
                <li>
                    <a href="Riya_Patel_Resume.pdf" target="_blank">Resume</a>
                </li>
            </ul>
        </section>

        <section class="contact common">
            <h1>Contact</h1>
            <ul>
                <li>Mobile No. - 6398799286</li>
                <li>Email ID - <a href="mailto:riyu2020patel@gmail.com">riyu2020patel@gmail.com</a></li>
            </ul>
        </section>
    </main>
</body>

</html>
body {
    margin: 0;
    padding: 0;
    background-color: black;
    color: white;
    font-family: Arial, sans-serif;
}

.header {
    display: flex;
    justify-content: center;
    padding: 20px 0;
}

#name {
    color: red;
    padding-right: 15px;
}

.main {
    margin-top: 10rem;
    display: flex;
    align-items: center;
    margin: 100px;
    flex-wrap: wrap;
}

p {
    padding-top: 10px;
}

.about {
    margin-right: 100px;
    max-width: 600px;
}

img {
    width: 300px;
    border-radius: 50%;
}

.skills {
    padding: 25px;
    margin-left: 100px;
}

#Skills li {
    text-transform: capitalize;
    margin: 8px 0;
}

.common {
    margin-left: 100px;
    margin-top: 100px;
    padding: 25px;
}

a {
    color: #00d9ff;
    text-decoration: none;
}

a:hover {
    text-decoration: underline;
}

@media (max-width: 768px) {
    .main {
        flex-direction: column;
        margin: 2rem;
        text-align: center;
    }

    .about, .image {
        margin: 0;
    }

    img {
        width: 200px;
        margin-top: 20px;
    }

    .skills, .common {
        margin-left: 2rem;
    }
}
