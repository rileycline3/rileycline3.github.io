rileycline3.github.io
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Riley's Futuristic Page</title>
  <style>
    /* General Styles */
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      background: #0a0a0f;
      color: #e0e0ff;
      scroll-behavior: smooth;
    }

    /* Header */
    header {
      background: linear-gradient(90deg, #3a0ca3, #4361ee, #4cc9f0);
      padding: 2rem;
      text-align: center;
      box-shadow: 0 0 20px #4cc9f0;
    }
    header h1 {
      font-size: 3rem;
      margin: 0;
      color: #fff;
      text-shadow: 0 0 15px #00f5d4, 0 0 25px #4cc9f0;
    }
    header p {
      margin: 0.5rem 0 0;
      color: #d0d0ff;
      font-style: italic;
    }

    /* Navigation */
    nav {
      display: flex;
      justify-content: center;
      background: #1b1b2f;
      padding: 0.8rem;
      position: sticky;
      top: 0;
      z-index: 1000;
      box-shadow: 0 0 15px #3a0ca3;
    }
    nav a {
      color: #e0e0ff;
      text-decoration: none;
      margin: 0 20px;
      font-weight: bold;
      font-size: 1.1rem;
      position: relative;
      transition: color 0.3s;
    }
    nav a::after {
      content: "";
      display: block;
      width: 0;
      height: 2px;
      background: #4cc9f0;
      transition: width 0.3s;
      position: absolute;
      bottom: -5px;
      left: 0;
    }
    nav a:hover {
      color: #4cc9f0;
    }
    nav a:hover::after {
      width: 100%;
    }

    /* Sections */
    section {
      padding: 3rem 2rem;
      max-width: 1000px;
      margin: auto;
    }
    h2 {
      color: #4cc9f0;
      font-size: 2rem;
      text-shadow: 0 0 10px #3a0ca3;
    }

    /* Vocabulary */
    .vocab-list {
      columns: 2;
      column-gap: 2rem;
    }
    .vocab-list p {
      margin: 0.5rem 0;
      padding: 0.5rem;
      background: rgba(255, 255, 255, 0.05);
      border-left: 3px solid #4cc9f0;
      border-radius: 5px;
      transition: transform 0.3s, background 0.3s;
    }
    .vocab-list p:hover {
      transform: translateX(10px);
      background: rgba(76, 201, 240, 0.1);
    }

    /* Images */
    img {
      max-width: 100%;
      border-radius: 12px;
      margin: 1.5rem 0;
      box-shadow: 0 0 20px #3a0ca3;
      transition: transform 0.3s;
    }
    img:hover {
      transform: scale(1.05);
    }

    /* Footer */
    footer {
      background: #1b1b2f;
      color: #aaaaff;
      text-align: center;
      padding: 1.5rem;
      margin-top: 3rem;
      font-size: 0.9rem;
      letter-spacing: 1px;
      box-shadow: 0 -3px 15px #3a0ca3;
    }
  </style>
</head>
<body>
  <header>
    <h1>Riley</h1>
    <p>My Journey & Learning</p>
  </header>

  <nav>
    <a href="#plans">Future Plans</a>
    <a href="#vocab">Vocabulary</a>
    <a href="#video">Video</a>
  </nav>

  <section id="plans">
    <h2>Future Plans</h2>
    <p>
      After high school, I want to study <strong>Sports Marketing</strong>. 
      Just like data is broken into <em>bits</em> and <em>bytes</em>, I want to break down 
      strategies that connect athletes and fans. Sports events are like computer networks — 
      people, media, and technology working together through many <em>paths</em> and <em>protocols</em>. 
      My goal is to be part of that system and help it grow with <em>scalability</em>.
    </p>
  </section>

  <section id="vocab">
    <h2>Unit 1 & 2 Vocabulary</h2>
    <div class="vocab-list">
      <p><strong>Bit:</strong> A binary digit, 0 or 1.</p>
      <p><strong>Byte:</strong> A sequence of 8 bits.</p>
      <p><strong>Roundoff:</strong> Error from limited precision.</p>
      <p><strong>Analog Data:</strong> Smooth, continuous values.</p>
      <p><strong>Lossless:</strong> Compression with no lost data.</p>
      <p><strong>Lossy:</strong> Compression that removes data.</p>
      <p><strong>Metadata:</strong> Data about data.</p>
      <p><strong>Computing Device:</strong> Runs programs.</p>
      <p><strong>Computer Network:</strong> Linked devices.</p>
      <p><strong>Path:</strong> Connections from sender to receiver.</p>
      <p><strong>Protocol:</strong> Rules for communication.</p>
      <p><strong>Fault Tolerant:</strong> Keeps working if parts fail.</p>
      <p><strong>Scalability:</strong> Ability to grow.</p>
      <p><strong>Bandwidth:</strong> Transmission capacity.</p>
      <p><strong>URL:</strong> Easy-to-remember web address.</p>
      <p><strong>IP:</strong> Assigns addresses/routes data.</p>
      <p><strong>TCP:</strong> Reliable, checked delivery.</p>
      <p><strong>UDP:</strong> Faster, lightweight delivery.</p>
      <p><strong>Packets:</strong> Data split into chunks.</p>
      <p><strong>Routers:</strong> Forward data paths.</p>
      <p><strong>DNS:</strong> Translates domain to IP.</p>
      <p><strong>HTTP:</strong> Webpage protocol.</p>
      <p><strong>WWW:</strong> System of linked pages.</p>
    </div>

    <h3>Visuals</h3>
    <img src="https://cdn-icons-png.flaticon.com/512/2721/2721290.png" alt="Cartoon data graphic">
    <img src="https://cdn-icons-png.flaticon.com/512/3069/3069186.png" alt="Cartoon network graphic">
  </section>

  <section id="video">
    <h2>Learn More</h2>
    <p>
      Watch this futuristic breakdown of how the internet works:  
      <a href="https://www.youtube.com/watch?v=7_LPdttKXPc" target="_blank">How the Internet Works</a>
    </p>
  </section>

  <footer>
    <p>© 2025 Riley | Futuristic GitHub Pages Design</p>
  </footer>
</body>
</html>
