# Ex01 Portfolio
## Date:19-08-2026
## name:RIYAZ M


## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
## index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Riyaz M — Frontend Developer</title>
<link rel="stylesheet" href="style.css">
</head>
<body>

<nav>
  <div class="wrap nav-inner">
    <div class="logo">Joe<span>.</span></div>
    <div class="nav-links" id="navLinks">
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#portfolio">Portfolio</a>
      <a href="#experience">Experience</a>
      <a href="#contact">Contact</a>
    </div>
    <a href="#contact" class="btn btn-solid nav-cta">Let's Talk</a>
    <button class="menu-toggle" id="menuToggle" aria-label="Toggle menu">
      <span></span><span></span><span></span>
    </button>
  </div>
</nav>

<header id="home">
  <div class="wrap hero-grid">
    <div class="hero-text reveal">
      <p class="eyebrow">Frontend Developer</p>
      <h1>Hi, I'm <span class="accent">Riyaz M</span></h1>
      <p class="hero-copy">I design and build clean, fast interfaces that feel effortless to use. Four years of turning product ideas into interfaces people actually enjoy clicking through.</p>
      <div class="hero-actions">
        <a href="#contact" class="btn btn-solid">Hire Me</a>
        <a href="#portfolio" class="btn btn-outline">See Projects</a>
      </div>
      <div class="social-row">
        <a href="#" class="social-dot" aria-label="LinkedIn">in</a>
        <a href="#" class="social-dot" aria-label="Twitter">tw</a>
        <a href="#" class="social-dot" aria-label="Dribbble">dr</a>
      </div>
    </div>
    <div class="hero-art reveal">
      <img src="WhatsApp Image 2026-08-03 at 8.42.52 PM.jpeg" alt="Riyaz M portrait" class="hero-photo">
    </div>
  </div>
</header>

<section id="about">
  <div class="wrap">
    <p class="eyebrow center">About Me</p>
    <h2 class="section-title center">A little about how I work</h2>
    <div class="about-grid reveal">
      <p>I'm a frontend developer who cares about the details most people scroll past — the way a button responds when you press it, the half-second before a page settles into place. I studied Computer Science, then spent the last four years building interfaces for startups and small product teams.</p>
      <p>My approach is simple: understand what the user is trying to do, then get out of their way. I work mainly in React and TypeScript, and I'm just as comfortable turning a Figma file into pixel-accurate code as I am proposing a better layout from scratch.</p>
    </div>
    <div class="stats reveal">
      <div class="stat"><span class="stat-num">4+</span><span class="stat-label">Years experience</span></div>
      <div class="stat"><span class="stat-num">38</span><span class="stat-label">Projects shipped</span></div>
      <div class="stat"><span class="stat-num">21</span><span class="stat-label">Happy clients</span></div>
    </div>
  </div>
</section>

<section id="skills" class="alt">
  <div class="wrap">
    <p class="eyebrow center">What I Use</p>
    <h2 class="section-title center">Tools &amp; technologies</h2>
    <div class="skills-grid reveal">
      <div class="skill-pill">React</div>
      <div class="skill-pill">TypeScript</div>
      <div class="skill-pill">Next.js</div>
      <div class="skill-pill">Tailwind CSS</div>
      <div class="skill-pill">Figma</div>
      <div class="skill-pill">GraphQL</div>
      <div class="skill-pill">Node.js</div>
      <div class="skill-pill">Framer Motion</div>
    </div>
  </div>
</section>

<section id="portfolio">
  <div class="wrap">
    <p class="eyebrow center">Portfolio</p>
    <h2 class="section-title center">Recent work</h2>
    <div class="portfolio-grid reveal">

      <article class="proj-card">
        <div class="proj-thumb thumb-1"></div>
        <div class="proj-body">
          <span class="proj-tag">Web App</span>
          <h3>Northstar Analytics</h3>
          <p>A dashboard for tracking product metrics, redesigned from the ground up for clarity and speed.</p>
        </div>
      </article>

      <article class="proj-card">
        <div class="proj-thumb thumb-2"></div>
        <div class="proj-body">
          <span class="proj-tag">E-commerce</span>
          <h3>Loomery</h3>
          <p>A storefront for an independent textile brand, built with a focus on fast product discovery.</p>
        </div>
      </article>

      <article class="proj-card">
        <div class="proj-thumb thumb-3"></div>
        <div class="proj-body">
          <span class="proj-tag">Marketing Site</span>
          <h3>Fieldnote</h3>
          <p>Landing page and blog for a note-taking startup, launched ahead of their public beta.</p>
        </div>
      </article>

      <article class="proj-card">
        <div class="proj-thumb thumb-4"></div>
        <div class="proj-body">
          <span class="proj-tag">Mobile Web</span>
          <h3>Ridewell</h3>
          <p>A booking flow for a bike-share app, rebuilt to cut checkout time by nearly half.</p>
        </div>
      </article>

    </div>
  </div>
</section>

<section id="experience" class="alt">
  <div class="wrap">
    <p class="eyebrow center">Experience</p>
    <h2 class="section-title center">Where I've worked</h2>
    <div class="timeline reveal">
      <div class="tl-item">
        <span class="tl-date">2023 — Present</span>
        <h3>Senior Frontend Developer</h3>
        <span class="tl-role">Northgate Labs</span>
        <p>Leading frontend architecture for the company's core analytics product, and mentoring two junior developers.</p>
      </div>
      <div class="tl-item">
        <span class="tl-date">2021 — 2023</span>
        <h3>Frontend Developer</h3>
        <span class="tl-role">Fieldstone Studio</span>
        <p>Built marketing sites and product UIs for a range of startup clients, from first sketch to launch.</p>
      </div>
      <div class="tl-item">
        <span class="tl-date">2020 — 2021</span>
        <h3>Junior Developer</h3>
        <span class="tl-role">Orbital Co.</span>
        <p>Started out fixing bugs and shipping small features, and left knowing how to run a whole sprint.</p>
      </div>
    </div>
  </div>
</section>

<section id="contact">
  <div class="wrap contact-wrap reveal">
    <div class="contact-text">
      <p class="eyebrow">Contact</p>
      <h2 class="section-title">Let's build something together</h2>
      <p class="hero-copy">Have a project in mind, or just want to talk shop? My inbox is open.</p>
      <div class="contact-details">
        <a href="mailto:joe.greyson@example.com">joe.greyson@example.com</a>
        <a href="#">github.com/joegreyson</a>
        <a href="#">linkedin.com/in/joegreyson</a>
      </div>
    </div>
    <form class="contact-form" onsubmit="return false;">
      <label for="cname">Name</label>
      <input type="text" id="cname" placeholder="Your name">
      <label for="cemail">Email</label>
      <input type="email" id="cemail" placeholder="you@example.com">
      <label for="cmsg">Message</label>
      <textarea id="cmsg" rows="4" placeholder="What are you looking to build?"></textarea>
      <button type="submit" class="btn btn-solid full">Send Message</button>
    </form>
  </div>
</section>

<footer>
  <div class="wrap footer-inner">
    <div class="logo">Riyaz<span>.</span></div>
    <p>© 2026 Riyaz M. Built with care.</p>
  </div>
</footer>

<script src="script.js"></script>
</body>
</html>
```
style.css
```
:root{
  --bg:#f4f2fa;
  --bg-alt:#ede8fa;
  --card:#ffffff;
  --text:#241f36;
  --text-dim:#6b6680;
  --purple:#7c5cff;
  --purple-dark:#5b3ce0;
  --purple-light:#efe9fd;
  --border:#e3ddf5;
  --radius:16px;
  --sans:'Poppins','Segoe UI',sans-serif;
  --body:'Inter','Segoe UI',sans-serif;
}

*{margin:0;padding:0;box-sizing:border-box;}
html{scroll-behavior:smooth;}
body{
  font-family:var(--body);
  color:var(--text);
  background:var(--bg);
  line-height:1.65;
  -webkit-font-smoothing:antialiased;
}
a{color:inherit;text-decoration:none;}
img,svg{max-width:100%;display:block;}
::selection{background:var(--purple);color:#fff;}
:focus-visible{outline:2px solid var(--purple-dark);outline-offset:3px;}

.wrap{max-width:1140px;margin:0 auto;padding:0 24px;}

h1,h2,h3,.logo{font-family:var(--sans);}

/* ---------- BUTTONS ---------- */
.btn{
  display:inline-flex;
  align-items:center;
  justify-content:center;
  padding:13px 28px;
  border-radius:999px;
  font-weight:600;
  font-size:14.5px;
  font-family:var(--sans);
  transition:transform .18s ease, box-shadow .18s ease, background .18s ease;
  cursor:pointer;
  border:2px solid transparent;
}
.btn-solid{
  background:var(--purple);
  color:#fff;
  box-shadow:0 10px 24px -8px rgba(124,92,255,0.55);
}
.btn-solid:hover{
  background:var(--purple-dark);
  transform:translateY(-2px);
}
.btn-outline{
  background:transparent;
  border-color:var(--purple);
  color:var(--purple);
}
.btn-outline:hover{
  background:var(--purple-light);
  transform:translateY(-2px);
}
.btn.full{width:100%;}

/* ---------- NAV ---------- */
nav{
  position:sticky;
  top:0;
  z-index:100;
  background:rgba(244,242,250,0.85);
  backdrop-filter:blur(10px);
  border-bottom:1px solid var(--border);
}
.nav-inner{
  display:flex;
  align-items:center;
  justify-content:space-between;
  height:80px;
  gap:24px;
}
.logo{
  font-size:22px;
  font-weight:700;
  color:var(--text);
  flex-shrink:0;
}
.logo span{color:var(--purple);}
.nav-links{
  display:flex;
  gap:32px;
  flex:1;
  justify-content:center;
  font-weight:500;
  font-size:15px;
}
.nav-links a{
  color:var(--text);
  position:relative;
  padding:4px 0;
  transition:color .2s;
}
.nav-links a:hover{color:var(--purple);}
.nav-cta{padding:11px 24px;font-size:14px;flex-shrink:0;}
.menu-toggle{
  display:none;
  flex-direction:column;
  gap:5px;
  background:none;
  border:none;
  cursor:pointer;
  padding:4px;
}
.menu-toggle span{
  width:24px;height:2px;background:var(--text);border-radius:2px;
}

@media(max-width:860px){
  .nav-cta{display:none;}
  .menu-toggle{display:flex;}
  .nav-links{
    position:absolute;
    top:80px;left:0;right:0;
    background:var(--bg);
    flex-direction:column;
    align-items:center;
    padding:20px 0;
    gap:18px;
    border-bottom:1px solid var(--border);
    display:none;
  }
  .nav-links.open{display:flex;}
}

/* ---------- HERO ---------- */
header{padding:70px 0 60px;}
.hero-grid{
  display:grid;
  grid-template-columns:1fr 0.9fr;
  gap:40px;
  align-items:center;
}
.eyebrow{
  font-family:var(--sans);
  font-weight:600;
  font-size:14px;
  color:var(--purple);
  text-transform:uppercase;
  letter-spacing:1.5px;
  margin-bottom:10px;
}
.eyebrow.center{text-align:center;}
h1{
  font-size:44px;
  font-weight:700;
  line-height:1.15;
  margin-bottom:14px;
}
.accent{color:var(--purple);}
.hero-copy{
  color:var(--text-dim);
  font-size:16px;
  max-width:46ch;
  margin-bottom:28px;
}
.hero-actions{
  display:flex;
  gap:16px;
  margin-bottom:32px;
  flex-wrap:wrap;
}
.social-row{display:flex;gap:12px;}
.social-dot{
  width:40px;height:40px;
  border-radius:50%;
  background:var(--purple);
  color:#fff;
  display:flex;
  align-items:center;
  justify-content:center;
  font-size:12px;
  font-weight:700;
  text-transform:uppercase;
  transition:transform .2s, background .2s;
}
.social-dot:hover{background:var(--purple-dark);transform:translateY(-3px);}

.hero-svg{width:100%;height:auto;}
.hero-photo{width:100%;height:auto;border-radius:24px;object-fit:cover;box-shadow:0 24px 56px rgba(44,39,64,0.18);}
.floaty{animation:float 4s ease-in-out infinite;}
.floaty-2{animation-delay:.6s;}
.floaty-3{animation-delay:1.2s;}
@keyframes float{
  0%,100%{transform:translateY(0);}
  50%{transform:translateY(-12px);}
}

@media(max-width:860px){
  .hero-grid{grid-template-columns:1fr;text-align:center;}
  .hero-actions,.social-row{justify-content:center;}
  .hero-copy{margin-left:auto;margin-right:auto;}
  h1{font-size:36px;}
  .hero-art{order:-1;max-width:320px;margin:0 auto;}
}

/* ---------- SECTIONS ---------- */
section{padding:90px 0;}
section.alt{background:var(--bg-alt);}
.section-title{
  font-size:32px;
  font-weight:700;
  margin-bottom:44px;
}
.section-title.center{text-align:center;}

/* ---------- ABOUT ---------- */
.about-grid{
  display:grid;
  grid-template-columns:1fr 1fr;
  gap:36px;
  max-width:900px;
  margin:0 auto 56px;
}
.about-grid p{color:var(--text-dim);font-size:15.5px;}
.stats{
  display:flex;
  justify-content:center;
  gap:64px;
  flex-wrap:wrap;
}
.stat{text-align:center;}
.stat-num{
  display:block;
  font-family:var(--sans);
  font-size:36px;
  font-weight:700;
  color:var(--purple);
}
.stat-label{
  font-size:13.5px;
  color:var(--text-dim);
}

@media(max-width:700px){
  .about-grid{grid-template-columns:1fr;}
}

/* ---------- SKILLS ---------- */
.skills-grid{
  display:flex;
  flex-wrap:wrap;
  gap:14px;
  justify-content:center;
}
.skill-pill{
  background:var(--card);
  border:1px solid var(--border);
  padding:12px 26px;
  border-radius:999px;
  font-weight:600;
  font-size:14.5px;
  color:var(--text);
  transition:border-color .2s, color .2s, transform .2s;
}
.skill-pill:hover{
  border-color:var(--purple);
  color:var(--purple);
  transform:translateY(-3px);
}

/* ---------- PORTFOLIO ---------- */
.portfolio-grid{
  display:grid;
  grid-template-columns:repeat(2,1fr);
  gap:28px;
}
@media(max-width:700px){.portfolio-grid{grid-template-columns:1fr;}}

.proj-card{
  background:var(--card);
  border-radius:var(--radius);
  overflow:hidden;
  border:1px solid var(--border);
  transition:transform .25s ease, box-shadow .25s ease;
}
.proj-card:hover{
  transform:translateY(-6px);
  box-shadow:0 24px 40px -20px rgba(36,31,54,0.18);
}
.proj-thumb{
  height:180px;
  background-size:cover;
}
.thumb-1{background:linear-gradient(135deg,#7c5cff,#c9b8ff);}
.thumb-2{background:linear-gradient(135deg,#ff9d8a,#ffd3a8);}
.thumb-3{background:linear-gradient(135deg,#5be7c4,#8fd6ff);}
.thumb-4{background:linear-gradient(135deg,#ffb6d9,#c9b8ff);}
.proj-body{padding:24px;}
.proj-tag{
  display:inline-block;
  font-size:12px;
  font-weight:700;
  color:var(--purple);
  background:var(--purple-light);
  padding:4px 12px;
  border-radius:999px;
  margin-bottom:12px;
}
.proj-body h3{font-size:19px;margin-bottom:8px;}
.proj-body p{color:var(--text-dim);font-size:14.5px;}

/* ---------- EXPERIENCE ---------- */
.timeline{
  max-width:720px;
  margin:0 auto;
  border-left:3px solid var(--purple-light);
}
.tl-item{
  position:relative;
  padding:0 0 40px 32px;
}
.tl-item:last-child{padding-bottom:0;}
.tl-item::before{
  content:'';
  position:absolute;
  left:-9px;top:4px;
  width:15px;height:15px;
  border-radius:50%;
  background:var(--purple);
  border:3px solid var(--bg-alt);
}
.tl-date{
  font-size:13px;
  font-weight:600;
  color:var(--purple);
}
.tl-item h3{font-size:18px;margin:6px 0 2px;}
.tl-role{
  display:block;
  font-size:13.5px;
  color:var(--text-dim);
  margin-bottom:8px;
}
.tl-item p{color:var(--text-dim);font-size:14.5px;}

/* ---------- CONTACT ---------- */
.contact-wrap{
  display:grid;
  grid-template-columns:1fr 1fr;
  gap:56px;
  align-items:start;
}
.contact-details{
  display:flex;
  flex-direction:column;
  gap:10px;
  margin-top:20px;
}
.contact-details a{
  font-weight:600;
  color:var(--purple);
}
.contact-form{
  background:var(--card);
  border:1px solid var(--border);
  border-radius:var(--radius);
  padding:32px;
  display:flex;
  flex-direction:column;
  gap:6px;
}
.contact-form label{
  font-size:13px;
  font-weight:600;
  margin-top:12px;
}
.contact-form input,.contact-form textarea{
  border:1px solid var(--border);
  border-radius:10px;
  padding:12px 14px;
  font-family:var(--body);
  font-size:14.5px;
  background:var(--bg);
  color:var(--text);
  resize:vertical;
}
.contact-form input:focus,.contact-form textarea:focus{
  outline:2px solid var(--purple);
  outline-offset:1px;
}
.contact-form .btn{margin-top:18px;}

@media(max-width:800px){
  .contact-wrap{grid-template-columns:1fr;}
}

/* ---------- FOOTER ---------- */
footer{
  padding:32px 0;
  border-top:1px solid var(--border);
}
.footer-inner{
  display:flex;
  justify-content:space-between;
  align-items:center;
  flex-wrap:wrap;
  gap:12px;
}
footer p{color:var(--text-dim);font-size:13.5px;}

/* ---------- REVEAL ---------- */
.reveal{opacity:0;transform:translateY(18px);transition:opacity .6s ease, transform .6s ease;}
.reveal.in{opacity:1;transform:none;}

@media(prefers-reduced-motion:reduce){
  *{animation:none !important;transition:none !important;}
  .reveal{opacity:1;transform:none;}
}
```







## OUTPUT
<img width="1896" height="1193" alt="Screenshot 2026-08-07 145559" src="https://github.com/user-attachments/assets/aadb869e-5ea2-4e6f-9ed5-a48a678e8a9a" />
<img width="1917" height="1196" alt="Screenshot 2026-08-07 145609" src="https://github.com/user-attachments/assets/5e32cde6-5d69-40a0-9a80-350942c424ce" />
<img width="1898" height="1190" alt="Screenshot 2026-08-07 145618" src="https://github.com/user-attachments/assets/7ce8adcc-f577-48b7-a897-626070277f0c" />
<img width="1917" height="1195" alt="Screenshot 2026-08-07 145650" src="https://github.com/user-attachments/assets/acc7e051-c693-4760-afce-54ca4b73f9b0" />
<img width="1917" height="1195" alt="Screenshot 2026-08-07 145658" src="https://github.com/user-attachments/assets/bf2ef656-8fd8-4348-a348-289590b07e7a" />










## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
