<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome to my Profile Page!</title>
    <style>
        body {
            font-family: 'Monospaced', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #D0E0D0;
            color: #3B3B3B;
            line-height: 1.6;
        }

        .header-container {
            display: flex;
            align-items: center;
            padding: 1rem;
            background-color: #D0E0D0;
            border-bottom: 3px solid #4A6E4A;
        }

        .profile-pic {
            width: 50px;
            height: 50px;
            border-radius: 50%;
            margin-right: 1rem;
        }

        .header-text {
            flex-grow: 1;
        }

        .header-text h1 {
            font-size: 2rem;
            margin: 0;
            color: #4A6E4A;
        }

        .header-text p {
            margin: 0.5rem 0 0;
            font-size: 1rem;
            color: #1C2A1C;
        }

        .welcome {
            text-align: center;
            margin-top: 0.5rem;
            font-size: 1.2rem;
            color: #4A6E4A;
        }

        main {
            padding: 2rem;
            max-width: 800px;
            margin: auto;
        }

        section {
            margin-bottom: 2rem;
        }

        h2 {
            border-bottom: 2px solid #006400;
            padding-bottom: 0.5rem;
            color: #1C2A1C;
        }

        p {
            margin: 0.5rem 0;
        }

        .resume-download {
            display: flex;
            justify-content: center;
            margin-top: 1rem;
            gap: 1rem;
        }

        .resume-download a {
            text-decoration: none;
            background-color: #4A6E4A;
            color: #f5f5f5;
            padding: 0.8rem 2rem;
            border-radius: 5px;
            font-size: 1rem;
            width: 180px;
            text-align: center;
            display: flex;
            align-items: center;
            justify-content: center;
            transition: background-color 0.3s ease;
        }

        .resume-download a:hover {
            background-color: #006400;
        }

        .interests {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 1rem;
            margin-top: 2rem;
        }

        .interests img {
            width: 150px;
            height: 150px;
            border-radius: 10px;
            object-fit: cover;
        }

        footer {
            text-align: center;
            padding: 1rem;
            background-color: #8FBC8F;
            color: #3B3B3B;
            border-top: 3px solid #4A6E4A;
        }

        footer a {
            color: #1C2A1C;
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <div class="header-container">
        <img src="images/EDD Profile.png" alt="EDD Profile" class="EDD Profile.png">
        <div class="header-text">
            <h1>Eileen Devereux Dailey</h1>
            <p>Product Manager | MBA | BSIE</p>
        </div>
    </div>

    <div class="welcome">
        Welcome to my Profile Page!
    </div>

    <main>
        <section>
            <h2>About Me</h2>
            <p>Hello! I'm Eileen Devereux Dailey, a Product Manager with 14 years of experience in the B2B SaaS industry, developing product-oriented projects for technology startups, doing market & customer research and financial analysis. Most recently as a Platform PM at a technology company specializing in communication applications for education organizations, where I led the Platform Engineering Team overseeing the application’s authentication and user management system.</p>
        </section>

        <section>
            <h2>Key Skills</h2>
            <p>Strong communication, customer empathy, strategic thinking, data analysis, roadmapping prioritization, cross-functional collaboration, story mapping, lean methodology, performance metric analysis.</p>
        </section>

        <section>
            <h2>Resume</h2>
            <p>Explore my professional journey, achievements, and skills in detail. Click below to download my resume or connect with me on LinkedIn.</p>
            <div class="resume-download">
                <a href="Resume_Eileen%20Devereux.pdf" download>Download Resume</a>
                <a href="https://www.linkedin.com/in/eileen-devereux-2a747913" target="_blank">View LinkedIn</a>
            </div>
        </section>

        <section>
            <h2>Personal Interests</h2>
            <div class="interests">
            <img src="images/Gardening.jpeg" alt="Gardening.jpeg">
            <img src="images/cooking.jpeg" alt="cooking.jpeg">

            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Eileen Devereux Dailey. Leading with empathy and analytical thinking.</p>
        <p><a href="mailto:eileenddm@gmail.com">eileenddm@gmail.com</a></p>
    </footer>
</body>
</html>
