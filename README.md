<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Kelvin Tech Lab</title>

    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: Arial, sans-serif;
            background: #0b1120;
            color: white;
            line-height: 1.6;
        }

        header {
            background: #111827;
            padding: 20px;
            text-align: center;
            border-bottom: 1px solid #263449;
        }

        header h1 {
            font-size: 30px;
        }

        header p {
            color: #9ca3af;
            margin-top: 5px;
        }

        nav {
            background: #0f172a;
            padding: 12px;
            text-align: center;
            position: sticky;
            top: 0;
            z-index: 10;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 10px;
            font-size: 14px;
        }

        nav a:hover {
            color: #38bdf8;
        }

        .hero {
            padding: 70px 20px;
            text-align: center;
            background: linear-gradient(135deg, #0b1120, #172554);
        }

        .hero h2 {
            font-size: 42px;
            margin-bottom: 15px;
        }

        .hero span {
            color: #38bdf8;
        }

        .hero p {
            max-width: 650px;
            margin: auto;
            color: #cbd5e1;
        }

        .button {
            display: inline-block;
            margin-top: 25px;
            padding: 12px 22px;
            background: #0284c7;
            color: white;
            text-decoration: none;
            border-radius: 8px;
        }

        section {
            padding: 50px 20px;
            max-width: 1100px;
            margin: auto;
        }

        section h2 {
            text-align: center;
            margin-bottom: 30px;
            font-size: 28px;
        }

        .cards {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            gap: 20px;
        }

        .card {
            background: #111827;
            padding: 25px;
            border-radius: 12px;
            border: 1px solid #263449;
        }

        .card h3 {
            color: #38bdf8;
            margin-bottom: 10px;
        }

        .card p {
            color: #cbd5e1;
            font-size: 15px;
        }

        .about {
            text-align: center;
            color: #cbd5e1;
            max-width: 750px;
            margin: auto;
        }

        .contact {
            text-align: center;
            background: #111827;
            border-radius: 15px;
        }

        footer {
            text-align: center;
            padding: 25px;
            background: #070b14;
            color: #94a3b8;
            font-size: 14px;
        }

        @media (max-width: 600px) {
            .hero h2 {
                font-size: 32px;
            }

            nav a {
                display: inline-block;
                margin: 5px;
            }
        }
    </style>
</head>

<body>

<header>
    <h1>⚡ KenTech Lab</h1>
    <p>Phone Technology • Repair • Electronics • Innovation</p>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#repair">Repair</a>
    <a href="#technology">Phone Tech</a>
    <a href="#projects">Projects</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
</nav>

<section class="hero" id="home">
    <h2>Welcome to <span>Kelvin Tech Lab</span></h2>

    <p>
        Exploring how phones work, how electronic components fail,
        and how technology can be repaired, modified and improved.
    </p>

    <a href="#projects" class="button">Explore Projects</a>
</section>

<section id="repair">
    <h2>🔧 Phone Repair</h2>

    <div class="cards">

        <div class="card">
            <h3>Charging Problems</h3>
            <p>
                Testing charging ports, USB lines, charging circuits,
                batteries and related components.
            </p>
        </div>

        <div class="card">
            <h3>Motherboard Repair</h3>
            <p>
                Component identification, circuit testing,
                fault tracing and motherboard diagnostics.
            </p>
        </div>

        <div class="card">
            <h3>Network Problems</h3>
            <p>
                Investigating weak network signals, antenna connections
                and communication circuits.
            </p>
        </div>

        <div class="card">
            <h3>Software Troubleshooting</h3>
            <p>
                Diagnosing software problems, freezes, boot issues
                and other smartphone faults.
            </p>
        </div>

    </div>
</section>

<section id="technology">
    <h2>📱 Phone Technology</h2>

    <div class="cards">

        <div class="card">
            <h3>USB & USB-C</h3>
            <p>
                Learn about VBUS, GND, D+ and D− and how USB communication
                works.
            </p>
        </div>

        <div class="card">
            <h3>Phone ICs</h3>
            <p>
                Explore the different integrated circuits found inside
                modern phones.
            </p>
        </div>

        <div class="card">
            <h3>Bluetooth & Wi-Fi</h3>
            <p>
                Understand wireless communication modules and how they
                connect with smartphones and computers.
            </p>
        </div>

        <div class="card">
            <h3>Audio Systems</h3>
            <p>
                Explore microphones, speakers, audio amplifiers and
                audio-processing circuits.
            </p>
        </div>

    </div>
</section>

<section id="projects">
    <h2>⚡ My Projects</h2>

    <div class="cards">

        <div class="card">
            <h3>Phone Repair Projects</h3>
            <p>
                Real repair cases, troubleshooting processes and
                component testing.
            </p>
        </div>

        <div class="card">
            <h3>Electronics Projects</h3>
            <p>
                Amplifiers, Arduino projects, USB experiments,
                Bluetooth projects and more.
            </p>
        </div>

        <div class="card">
            <h3>Tech Experiments</h3>
            <p>
                Testing and experimenting with electronic components
                and salvaged phone parts.
            </p>
        </div>

        <div class="card">
            <h3>Future Projects</h3>
            <p>
                New ideas in smartphone technology, electronics and
                automation.
            </p>
        </div>

    </div>
</section>

<section id="about">
    <h2>👨‍🔧 About Kelvin Tech Lab</h2>

    <p class="about">
        Kelvin Tech Lab is a technology project focused on smartphones,
        electronics, repair and practical experimentation.
        The goal is to understand technology from the component level
        and share useful knowledge with other tech enthusiasts.
    </p>
</section>

<section id="contact">
    <div class="contact">
        <h2>📞0754451735</h2>

        <p>
            Interested in phone technology, electronics or repair?
        </p>

        <a href="mailto:your-kelvinmacharia828@gmail.com" class="button">
            Contact Me 0754451735
        </a>
    </div>
</section>

<footer>
    © 2026 Kelvin Tech Lab. All rights reserved.
</footer>

</body>
</html>
