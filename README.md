<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Abdul Rehman — Profile</title>
  <style>
    body {
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial;
      color: #e6eef6;
      background: #0b1220;
      padding: 32px;
      line-height: 1.45;
    }
    .container { max-width: 900px; margin: 0 auto; }

    h1 { text-align:center; font-size:2rem; color:#00bfff; margin-bottom:6px; }
    h3 { text-align:center; color:#a9c6d8; font-weight:500; margin-top:0; }

    /* 👋 Wavy Hand Animation */
    .wave-hand {
      display: inline-block;
      animation: wave 2.5s infinite;
      transform-origin: 70% 70%;
      font-size: 1.6rem;
      vertical-align: middle;
    }
    @keyframes wave {
      0% { transform: rotate(0deg); }
      10% { transform: rotate(14deg); }
      20% { transform: rotate(-8deg); }
      30% { transform: rotate(14deg); }
      40% { transform: rotate(-4deg); }
      50% { transform: rotate(10deg); }
      60%,100% { transform: rotate(0deg); }
    }

    /* Floating Motion for icons */
    @keyframes float { 0%{transform:translateY(0)}50%{transform:translateY(-6px)}100%{transform:translateY(0)} }

    .icons { text-align:center; margin:12px 0; }
    .icons img { border-radius:50%; margin:0 6px; width:48px; height:48px; vertical-align:middle; transition:all .25s ease; }
    .icons img:hover { box-shadow: 0 0 14px rgba(0,191,255,.45); transform: translateY(-6px); }

    /* Remove visible gap by setting margin to 0 for "no-gap" feel */
    .no-gap img { margin: 0; }

    /* Typing effect */
    .typing {
      width: 28ch;
      white-space: nowrap;
      overflow: hidden;
      border-right: 3px solid #00bfff;
      margin: 8px auto 16px;
      animation: typing 3s steps(28), blink .6s step-end infinite alternate;
      text-align:center;
      font-weight:600;
      color:#cfefff;
    }
    @keyframes typing { from { width: 0; } to { width: 28ch; } }
    @keyframes blink { 50% { border-color: transparent; } }

    .card { background: rgba(255,255,255,0.02); padding:16px; border-radius:12px; margin-bottom:12px; box-shadow: 0 2px 10px rgba(2,6,23,.4); }
    a { color:#7ad0ff; text-decoration:none; }
    p.center { text-align:center; }
  </style>
</head>
<body>
  <div class="container">
    <h1>
      <span class="typing">Hi there, I'm Abdul Rehman</span>
      <span class="wave-hand">👋</span>
    </h1>

    <h3>🎓 BSCS Student at <a href="https://szabist.edu.pk" target="_blank">SZABIST Karachi</a> — Future Software Engineer</h3>

    <div class="card">
      <h4>✨ About Me</h4>
      <p>🎯 Computer Science student passionate about creating impactful solutions. I work with Java, Python, C/C#, HTML/CSS, and more. I use IntelliJ, VSCode, and I run Ubuntu on VMware.</p>
    </div>

    <div class="card">
      <h4>🌐 Connect</h4>
      <p class="icons">
        <a href="mailto:abdulrehman06012@gmail.com"><img src="https://skillicons.dev/icons?i=gmail" alt="Gmail" /></a>
        <a href="https://www.linkedin.com/in/abdul-rehman-653b5a367/"><img src="https://skillicons.dev/icons?i=linkedin" alt="LinkedIn" /></a>
        <a href="https://github.com/abdul-rehman-2312410"><img src="https://skillicons.dev/icons?i=github" alt="GitHub" /></a>
      </p>

      <h5>Languages</h5>
      <p class="icons no-gap">
        <img src="https://skillicons.dev/icons?i=java" alt="Java" />
        <img src="https://skillicons.dev/icons?i=python" alt="Python" />
        <img src="https://skillicons.dev/icons?i=c" alt="C" />
        <img src="https://skillicons.dev/icons?i=cs" alt="C#" />
        <img src="https://skillicons.dev/icons?i=html" alt="HTML" />
        <img src="https://skillicons.dev/icons?i=css" alt="CSS" />
      </p>

      <h5>Tools</h5>
      <p class="icons no-gap">
        <img src="https://skillicons.dev/icons?i=vscode" alt="VSCode" />
        <img src="https://skillicons.dev/icons?i=intellij" alt="IntelliJ" />
        <img src="https://skillicons.dev/icons?i=git" alt="Git" />
        <img src="https://skillicons.dev/icons?i=github" alt="GitHub" />
        <img src="https://skillicons.dev/icons?i=figma" alt="Figma" />
        <img src="https://skillicons.dev/icons?i=postman" alt="Postman" />
        <img src="https://skillicons.dev/icons?i=ubuntu" alt="Ubuntu" />
        <img src="https://skillicons.dev/icons?i=vmware" alt="VMware" />
      </p>
    </div>

    <div class="card">
      <h4>🚆 Featured Project</h4>
      <p><a href="https://github.com/abdul-rehman-2312410/TrainReservationSystem">Train Reservation System (Java)</a> — console based booking & reservation app (OOP, Collections, Sorting).</p>
    </div>

    <p class="center">“Push yourself, because no one else is going to do it for you.” 🚀</p>

  </div>
</body>
</html>
