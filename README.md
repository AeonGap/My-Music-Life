<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Æon Gap | Official Website</title>
    <style>
        body {
            background-color: #121212;
            color: #e0e0e0;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        header {
            text-align: center;
            padding: 50px 0;
            border-bottom: 1px solid #333;
        }
        header h1 {
            font-size: 3em;
            color: #fff;
        }
        nav {
            text-align: center;
            padding: 20px 0;
        }
        nav a {
            color: #e0e0e0;
            margin: 0 15px;
            text-decoration: none;
            font-size: 1.2em;
        }
        nav a:hover {
            color: #fff;
        }
        section {
            padding: 50px 0;
            border-bottom: 1px solid #333;
        }
        section h2 {
            text-align: center;
            font-size: 2em;
            margin-bottom: 20px;
        }
        .music, .videos, .bio, .contact {
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .music audio, .videos iframe {
            width: 80%;
            margin: 20px 0;
        }
        footer {
            text-align: center;
            padding: 20px 0;
            border-top: 1px solid #333;
        }
        footer p {
            margin: 0;
            color: #777;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Æon Gap</h1>
        </header>
        <nav>
            <a href="#music">Music</a>
            <a href="#videos">Videos</a>
            <a href="#bio">Biography</a>
            <a href="#contact">Contact</a>
        </nav>
        <section id="music" class="music">
            <h2>Music</h2>
            <!-- Add your music here -->
            <audio controls>
                <source src="path_to_your_song.mp3" type="audio/mpeg">
                Your browser does not support the audio element.
            </audio>
        </section>
        <section id="videos" class="videos">
            <h2>Videos</h2>
            <!-- Add your videos here -->
            <iframe width="560" height="315" src="https://www.youtube.com/embed/video_id" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </section>
        <section id="bio" class="bio">
            <h2>Biography</h2>
            <p>Æon Gap is a versatile music artist with a passion for creating unique and compelling sounds that resonate with listeners. With a style that blends dark, atmospheric elements with aggressive and energetic tones, Æon Gap stands out in the music scene.</p>
        </section>
        <section id="contact" class="contact">
            <h2>Contact</h2>
            <p>For inquiries, please contact: <a href="mailto:your_email@example.com">your_email@example.com</a></p>
        </section>
        <footer>
            <p>&copy; 2024 Æon Gap. All rights reserved.</p>
        </footer>
    </div>
</body>
</html>
