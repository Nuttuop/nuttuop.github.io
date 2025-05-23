
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Naitik's Digital Art Space</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@500&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Orbitron', sans-serif;
      background: linear-gradient(135deg, #0f0f0f, #1a1a1a);
      color: #fff;
      overflow-x: hidden;
      perspective: 1000px;
    }
    header {
      background-color: rgba(0, 0, 0, 0.7);
      text-align: center;
      padding: 3rem 1rem;
      animation: fadeInDown 1s ease-in-out forwards;
    }
    header h1 {
      font-size: 3rem;
      color: #00ffc8;
      text-shadow: 0 0 10px #00ffc8;
    }
    header p {
      font-size: 1.2rem;
      color: #ccc;
    }
    main {
      padding: 2rem;
      transform: rotateY(2deg);
      animation: slideIn 2s ease-in-out;
      max-width: 960px;
      margin: auto;
    }
    section {
      margin: 2rem 0;
      background: rgba(255, 255, 255, 0.05);
      padding: 2rem;
      border-radius: 20px;
      box-shadow: 0 10px 30px rgba(0, 255, 200, 0.2);
      backdrop-filter: blur(10px);
      transform-style: preserve-3d;
    }
    h2 {
      color: #00ffc8;
      margin-bottom: 1rem;
      text-shadow: 0 0 5px #00ffc8;
    }
    a {
      color: #00e0ff;
      text-decoration: none;
      font-weight: bold;
    }
    a:hover {
      text-shadow: 0 0 5px #00e0ff;
    }
    footer {
      text-align: center;
      padding: 2rem;
      background: #0f0f0f;
      border-top: 1px solid #222;
      color: #666;
    }
    .logo {
      width: 80px;
      height: 80px;
      margin: auto;
      display: block;
      margin-bottom: 1rem;
      filter: drop-shadow(0 0 5px #00ffc8);
    }
    ul {
      margin-left: 1.5rem;
    }
    .price-tag {
      background: #00ffc8;
      color: #000;
      display: inline-block;
      padding: 0.3rem 0.8rem;
      border-radius: 10px;
      font-weight: bold;
      box-shadow: 0 0 10px #00ffc8;
    }
    @keyframes fadeInDown {
      0% { opacity: 0; transform: translateY(-100px); }
      100% { opacity: 1; transform: translateY(0); }
    }
    @keyframes slideIn {
      0% { transform: translateX(-100%) rotateY(30deg); opacity: 0; }
      100% { transform: translateX(0) rotateY(2deg); opacity: 1; }
    }
  </style>
</head>
<body>
  <header>
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a7/React-icon.svg/1024px-React-icon.svg.png" alt="logo" class="logo">
    <h1>Welcome to Naitik's Digital Art Space</h1>
    <p>Where imagination meets innovation — in every pixel</p>
  </header>
  <main>
    <section>
      <h2>About Me</h2>
      <p>I'm <strong>Naitik</strong>, a digital designer driven by a passion to create stunning Instagram banners and social media visuals that captivate and inspire. With years of experience working with creators, influencers, and businesses, my art is more than just design—it's a message, a style, and an experience crafted uniquely for each audience.</p>
    </section>
    <section>
      <h2>Services & Pricing</h2>
      <p>I offer customized Instagram banners and social media graphics with pricing tailored to your influence and reach.</p>
      <ul>
        <li>Basic Banner (0–5K followers) — <span class="price-tag">$25</span></li>
        <li>Premium Banner (5K–20K followers) — <span class="price-tag">$35</span></li>
        <li>Elite Banner (20K+ followers) — <span class="price-tag">$50</span></li>
      </ul>
      <p>Each design includes:
        <ul>
          <li>High-resolution export</li>
          <li>2 free revisions</li>
          <li>Delivery within 48 hours</li>
        </ul>
      </p>
    </section>
    <section>
      <h2>Portfolio Highlights</h2>
      <p>Here are some recent design showcases that clients loved:</p>
      <ul>
        <li>Gaming-themed banner for a Twitch streamer (25K followers)</li>
        <li>Clean, minimalist promo post for a tech brand</li>
        <li>Vibrant, animated Instagram stories for influencers</li>
      </ul>
    </section>
    <section>
      <h2>Blog & Thoughts</h2>
      <p>Art isn’t just about color or shape—it's a visual language. I believe in telling stories that resonate with an audience emotionally. Through contrast, motion, and creative depth, I aim to capture attention in the most saturated digital spaces. In this blog, I will be sharing my thoughts, creative process, behind-the-scenes from my projects, and the latest trends in digital design.</p>
    </section>
    <section>
      <h2>Contact Me</h2>
      <p>If you're ready to elevate your social media look, let's work together!</p>
      <p>Instagram: <a href="https://instagram.com/nuttu.olds" target="_blank">@nuttu.olds</a></p>
      <p>Telegram: <a href="https://t.me/NN7WE" target="_blank">@NN7WE</a></p>
    </section>
  </main>
  <footer>
    <p>© 2025 Naitik. All rights reserved.</p>
  </footer>
</body>
</html>


