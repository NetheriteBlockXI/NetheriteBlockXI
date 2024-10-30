<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NetheriteBlockXI's Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 20px;
            display: flex;
            flex-direction: column;
            align-items: center;
            transition: background-color 0.3s;
        }

        h1 {
            color: #333;
            margin-bottom: 10px;
        }

        h2 {
            color: #007BFF;
            margin: 20px 0 10px;
        }

        p {
            color: #555;
            max-width: 600px;
            text-align: center;
        }

        .links {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            margin: 20px 0;
        }

        .link-item {
            background-color: white;
            padding: 10px 15px;
            border-radius: 5px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            margin: 5px;
            text-align: center;
            transition: transform 0.3s;
        }

        .link-item:hover {
            transform: translateY(-5px);
        }

        .projects {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            margin-top: 20px;
        }

        .project {
            background-color: white;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            margin: 10px;
            max-width: 300px;
            text-align: center;
            transition: transform 0.3s;
        }

        .project:hover {
            transform: translateY(-5px);
        }

        .project h3 {
            margin: 0;
            color: #007BFF;
        }

        .about-me {
            background-color: #f9f9f9;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            margin-top: 40px;
            text-align: center;
            max-width: 600px;
        }

        .contact {
            margin-top: 40px;
            text-align: center;
        }

        a {
            color: #007BFF;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }

        .discord-icon, .github-icon {
            width: 64px;
            height: 64px;
            vertical-align: middle;
            margin-right: 10px;
        }

        .avatar {
            width: 400px;
            height: 163px;
            margin-bottom: 20px;
        }

        .favorite-game-img {
            width: 64px;
            height: 64px;
            margin-top: 10px;
        }
    </style>
</head>
<body>

<img src="img/avatar.png" alt="Avatar" class="avatar">
<h1>NetheriteBlockXI AKA Zig</h1>

<h2>Links</h2>
<div class="links">
    <div class="link-item"><a href="https://github.com/NetheriteBlockXI/" target="_blank">GitHub Profile</a></div>
    <div class="link-item"><a href="https://3xp1.carrd.co" target="_blank">Old Portfolio Site</a></div>
    <div class="link-item"><a href="https://example.com" target="_blank">Empty</a></div>
</div>

<h2>Welcome to My Portfolio</h2>
<p>I'm a passionate developer who loves creating innovative solutions. Here are some of my projects:</p>

<div class="projects">
    <div class="project">
        <h3>Portfolio+</h3>
        <p>An app for making portfolios and bios.</p>
        <a href="https://github.com/NetheriteBlockXI/portfolioplus" target="_blank">View Project</a>
    </div>
    <div class="project">
        <h3>Tower Defense - Revamped</h3>
        <p>A revamped tower defense game that adds a lot of new features.</p>
        <a href="https://xpstu.itch.io/xe-td-rev" target="_blank">View Project</a>
    </div>
    <div class="project">
        <h3>Xenon OS</h3>
        <p>A fake OS made in TurboWarp.</p>
        <a href="https://xpstu.itch.io/xenon-os" target="_blank">View Project</a>
    </div>
    <div class="project">
        <h3>Forge Clicker</h3>
        <p>A clicker game about forging and crafting.</p>
        <a href="https://xpstu.itch.io/forge-clicker" target="_blank">View Project</a>
    </div>
    <div class="project">
        <h3>Printer Clicker</h3>
        <p>A clicker game focused solely on clicking, featuring printers.</p>
        <a href="https://xpstu.itch.io/printer-clicker" target="_blank">View Project</a>
    </div>
    <div class="project">
        <h3>FastForgeSkript</h3>
        <p>A fake but semi-working language (no ifs).</p>
        <a href="https://xpstu.itch.io/fastforgeskript" target="_blank">View Project</a>
    </div>
    <div class="project">
        <h3>ZIGP Format</h3>
        <p>A new image format.</p>
        <a href="https://xpstu.itch.io/zigp-format" target="_blank">View Project</a>
    </div>
</div>

<div class="about-me">
    <h2>About Me</h2>
    <p><strong>Username:</strong> NetheriteBlockXI</p>
    <p><strong>Interests:</strong> Coding and game development</p>
    <p><strong>Orientation:</strong> Straight</p>
    <p><strong>Favorite Game:</strong> Decaying Winter</p>
    <img src="img/dw0.png" alt="Favorite Game Icon" class="favorite-game-img">
    <p><strong>Fun Facts:</strong><br>
       I'm passionate about exploring new coding challenges and expanding my programming skills.<br>
       I have a liking for survival games and complex game mechanics, especially in Decaying Winter.
    </p>
    <p><strong>Things I Dislike:</strong><br>
       🧅 Onions<br>
       🍅 Tomatoes
    </p>
    <p>Feel free to explore my repositories and projects, and don't hesitate to reach out if you'd like to collaborate or discuss coding ideas!</p>
    <p><strong>AKA:</strong> Zig, 3xp (or _3xp), xenon, void</p>
</div>

<div class="contact">
    <h2>Contact Me</h2>
    <p>
        <img src="img/git.png" alt="GitHub" class="github-icon"> 
        Contact me on GitHub: <a href="https://github.com/NetheriteBlockXI" target="_blank">GitHub Profile</a>
    </p>
    <p>
        <img src="img/discord.png" alt="Discord" class="discord-icon"> 
        Contact me on Discord, username being <strong>_3xp</strong>
    </p>
</div>

<script>
    window.addEventListener('scroll', function () {
        const scrollTop = window.scrollY;
        const maxScroll = document.documentElement.scrollHeight - window.innerHeight;
        const scrollFraction = scrollTop / maxScroll;
        const darkness = Math.min(scrollFraction * 0.5, 0.5);
        document.body.style.backgroundColor = `rgb(${244 - darkness * 244}, ${244 - darkness * 244}, ${244 - darkness * 244})`;

        const elements = document.querySelectorAll('.link-item, .project, .about-me');
        elements.forEach(element => {
            const darkenAmount = Math.min(scrollFraction * 0.4, 0.4);
            const baseColor = 255 - darkenAmount * 200;
            element.style.boxShadow = `0 2px 10px rgba(0, 0, 0, ${0.1 + (0.2 * scrollFraction)})`;
            element.style.backgroundColor = `rgb(${baseColor}, ${baseColor}, ${baseColor})`;
        });
    });
</script>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NetheriteBlockXI's Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 20px;
            display: flex;
            flex-direction: column;
            align-items: center;
            transition: background-color 0.3s;
        }

        h1 {
            color: #333;
            margin-bottom: 10px;
        }

        h2 {
            color: #007BFF;
            margin: 20px 0 10px;
        }

        p {
            color: #555;
            max-width: 600px;
            text-align: center;
        }

        .links {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            margin: 20px 0;
        }

        .link-item {
            background-color: white;
            padding: 10px 15px;
            border-radius: 5px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            margin: 5px;
            text-align: center;
            transition: transform 0.3s;
        }

        .link-item:hover {
            transform: translateY(-5px);
        }

        .projects {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            margin-top: 20px;
        }

        .project {
            background-color: white;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            margin: 10px;
            max-width: 300px;
            text-align: center;
            transition: transform 0.3s;
        }

        .project:hover {
            transform: translateY(-5px);
        }

        .project h3 {
            margin: 0;
            color: #007BFF;
        }

        .about-me {
            background-color: #f9f9f9;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            margin-top: 40px;
            text-align: center;
            max-width: 600px;
        }

        .contact {
            margin-top: 40px;
            text-align: center;
        }

        a {
            color: #007BFF;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }

        .discord-icon, .github-icon {
            width: 64px;
            height: 64px;
            vertical-align: middle;
            margin-right: 10px;
        }

        .avatar {
            width: 400px;
            height: 163px;
            margin-bottom: 20px;
        }

        .favorite-game-img {
            width: 64px;
            height: 64px;
            margin-top: 10px;
        }
    </style>
</head>
<body>

<img src="img/avatar.png" alt="Avatar" class="avatar">
<h1>NetheriteBlockXI AKA Zig</h1>

<h2>Links</h2>
<div class="links">
    <div class="link-item"><a href="https://github.com/NetheriteBlockXI/" target="_blank">GitHub Profile</a></div>
    <div class="link-item"><a href="https://3xp1.carrd.co" target="_blank">Old Portfolio Site</a></div>
    <div class="link-item"><a href="https://example.com" target="_blank">Empty</a></div>
</div>

<h2>Welcome to My Portfolio</h2>
<p>I'm a passionate developer who loves creating innovative solutions. Here are some of my projects:</p>

<div class="projects">
    <div class="project">
        <h3>Portfolio+</h3>
        <p>An app for making portfolios and bios.</p>
        <a href="https://github.com/NetheriteBlockXI/portfolioplus" target="_blank">View Project</a>
    </div>
    <div class="project">
        <h3>Tower Defense - Revamped</h3>
        <p>A revamped tower defense game that adds a lot of new features.</p>
        <a href="https://xpstu.itch.io/xe-td-rev" target="_blank">View Project</a>
    </div>
    <div class="project">
        <h3>Xenon OS</h3>
        <p>A fake OS made in TurboWarp.</p>
        <a href="https://xpstu.itch.io/xenon-os" target="_blank">View Project</a>
    </div>
    <div class="project">
        <h3>Forge Clicker</h3>
        <p>A clicker game about forging and crafting.</p>
        <a href="https://xpstu.itch.io/forge-clicker" target="_blank">View Project</a>
    </div>
    <div class="project">
        <h3>Printer Clicker</h3>
        <p>A clicker game focused solely on clicking, featuring printers.</p>
        <a href="https://xpstu.itch.io/printer-clicker" target="_blank">View Project</a>
    </div>
    <div class="project">
        <h3>FastForgeSkript</h3>
        <p>A fake but semi-working language (no ifs).</p>
        <a href="https://xpstu.itch.io/fastforgeskript" target="_blank">View Project</a>
    </div>
    <div class="project">
        <h3>ZIGP Format</h3>
        <p>A new image format.</p>
        <a href="https://xpstu.itch.io/zigp-format" target="_blank">View Project</a>
    </div>
</div>

<div class="about-me">
    <h2>About Me</h2>
    <p><strong>Username:</strong> NetheriteBlockXI</p>
    <p><strong>Interests:</strong> Coding and game development</p>
    <p><strong>Orientation:</strong> Straight</p>
    <p><strong>Favorite Game:</strong> Decaying Winter</p>
    <img src="img/dw0.png" alt="Favorite Game Icon" class="favorite-game-img">
    <p><strong>Fun Facts:</strong><br>
       I'm passionate about exploring new coding challenges and expanding my programming skills.<br>
       I have a liking for survival games and complex game mechanics, especially in Decaying Winter.
    </p>
    <p><strong>Things I Dislike:</strong><br>
       🧅 Onions<br>
       🍅 Tomatoes
    </p>
    <p>Feel free to explore my repositories and projects, and don't hesitate to reach out if you'd like to collaborate or discuss coding ideas!</p>
    <p><strong>AKA:</strong> Zig, 3xp (or _3xp), xenon, void</p>
</div>

<div class="contact">
    <h2>Contact Me</h2>
    <p>
        <img src="img/git.png" alt="GitHub" class="github-icon"> 
        Contact me on GitHub: <a href="https://github.com/NetheriteBlockXI" target="_blank">GitHub Profile</a>
    </p>
    <p>
        <img src="img/discord.png" alt="Discord" class="discord-icon"> 
        Contact me on Discord, username being <strong>_3xp</strong>
    </p>
</div>

<script>
    window.addEventListener('scroll', function () {
        const scrollTop = window.scrollY;
        const maxScroll = document.documentElement.scrollHeight - window.innerHeight;
        const scrollFraction = scrollTop / maxScroll;
        const darkness = Math.min(scrollFraction * 0.5, 0.5);
        document.body.style.backgroundColor = `rgb(${244 - darkness * 244}, ${244 - darkness * 244}, ${244 - darkness * 244})`;

        const elements = document.querySelectorAll('.link-item, .project, .about-me');
        elements.forEach(element => {
            const darkenAmount = Math.min(scrollFraction * 0.4, 0.4);
            const baseColor = 255 - darkenAmount * 200;
            element.style.boxShadow = `0 2px 10px rgba(0, 0, 0, ${0.1 + (0.2 * scrollFraction)})`;
            element.style.backgroundColor = `rgb(${baseColor}, ${baseColor}, ${baseColor})`;
        });
    });
</script>

</body>
</html>
