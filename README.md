
# Kashan — Full-Stack Developer

<div align="center">

<svg width="100%" viewBox="0 0 1180 610" xmlns="http://www.w3.org/2000/svg">

  <defs>

```
<!-- Accent gradient -->
<linearGradient id="accent" x1="0%" y1="0%" x2="100%" y2="0%">
  <stop offset="0%" stop-color="#7C3AED">
    <animate attributeName="stop-color"
      values="#7C3AED;#22D3EE;#10B981;#7C3AED"
      dur="8s" repeatCount="indefinite"/>
  </stop>
  <stop offset="50%" stop-color="#22D3EE">
    <animate attributeName="stop-color"
      values="#22D3EE;#10B981;#7C3AED;#22D3EE"
      dur="8s" repeatCount="indefinite"/>
  </stop>
  <stop offset="100%" stop-color="#10B981">
    <animate attributeName="stop-color"
      values="#10B981;#7C3AED;#22D3EE;#10B981"
      dur="8s" repeatCount="indefinite"/>
  </stop>
</linearGradient>

<!-- ASCII gradient -->
<linearGradient id="asciiGradient" x1="0%" y1="0%" x2="100%" y2="100%">
  <stop offset="0%" stop-color="#22D3EE">
    <animate attributeName="stop-color"
      values="#22D3EE;#7C3AED;#22D3EE"
      dur="7s" repeatCount="indefinite"/>
  </stop>
  <stop offset="50%" stop-color="#7C3AED">
    <animate attributeName="stop-color"
      values="#7C3AED;#10B981;#7C3AED"
      dur="7s" repeatCount="indefinite"/>
  </stop>
  <stop offset="100%" stop-color="#10B981">
    <animate attributeName="stop-color"
      values="#10B981;#22D3EE;#10B981"
      dur="7s" repeatCount="indefinite"/>
  </stop>
</linearGradient>

<!-- Background glows -->
<radialGradient id="purpleGlow">
  <stop offset="0%" stop-color="#7C3AED" stop-opacity=".22"/>
  <stop offset="100%" stop-color="#7C3AED" stop-opacity="0"/>
</radialGradient>

<radialGradient id="cyanGlow">
  <stop offset="0%" stop-color="#22D3EE" stop-opacity=".18"/>
  <stop offset="100%" stop-color="#22D3EE" stop-opacity="0"/>
</radialGradient>

<radialGradient id="greenGlow">
  <stop offset="0%" stop-color="#10B981" stop-opacity=".13"/>
  <stop offset="100%" stop-color="#10B981" stop-opacity="0"/>
</radialGradient>

<!-- Glass -->
<linearGradient id="glass" x1="0%" y1="0%" x2="100%" y2="100%">
  <stop offset="0%" stop-color="#FFFFFF" stop-opacity=".075"/>
  <stop offset="50%" stop-color="#FFFFFF" stop-opacity=".025"/>
  <stop offset="100%" stop-color="#FFFFFF" stop-opacity=".055"/>
</linearGradient>

<!-- Border -->
<linearGradient id="borderGradient" x1="0%" y1="0%" x2="100%" y2="0%">
  <stop offset="0%" stop-color="#7C3AED" stop-opacity=".15"/>
  <stop offset="35%" stop-color="#22D3EE" stop-opacity=".7"/>
  <stop offset="65%" stop-color="#10B981" stop-opacity=".55"/>
  <stop offset="100%" stop-color="#7C3AED" stop-opacity=".15">
    <animate attributeName="stop-opacity"
      values=".15;.8;.15"
      dur="4s" repeatCount="indefinite"/>
  </stop>
</linearGradient>

<!-- Glow -->
<filter id="glow" x="-100%" y="-100%" width="300%" height="300%">
  <feGaussianBlur stdDeviation="5" result="blur"/>
</filter>

<filter id="softGlow" x="-100%" y="-100%" width="300%" height="300%">
  <feGaussianBlur stdDeviation="12" result="blur"/>
</filter>

<!-- Clip -->
<clipPath id="heroClip">
  <rect x="0" y="0" width="1180" height="610" rx="30"/>
</clipPath>

<!-- Scanline -->
<linearGradient id="scanline" x1="0%" y1="0%" x2="0%" y2="100%">
  <stop offset="0%" stop-color="#22D3EE" stop-opacity="0"/>
  <stop offset="45%" stop-color="#22D3EE" stop-opacity=".04"/>
  <stop offset="50%" stop-color="#22D3EE" stop-opacity=".18"/>
  <stop offset="55%" stop-color="#22D3EE" stop-opacity=".04"/>
  <stop offset="100%" stop-color="#22D3EE" stop-opacity="0"/>
</linearGradient>
```

  </defs>

  <!-- ========================================================= -->

  <!-- BACKGROUND -->

  <!-- ========================================================= -->

  <rect width="1180" height="610" rx="30" fill="#030712"/>

  <g clip-path="url(#heroClip)">

```
<!-- Ambient gradients -->
<circle cx="110" cy="100" r="310" fill="url(#purpleGlow)">
  <animateTransform
    attributeName="transform"
    type="translate"
    values="0 0;35 20;0 0"
    dur="12s"
    repeatCount="indefinite"/>
</circle>

<circle cx="900" cy="80" r="350" fill="url(#cyanGlow)">
  <animateTransform
    attributeName="transform"
    type="translate"
    values="0 0;-30 30;0 0"
    dur="15s"
    repeatCount="indefinite"/>
</circle>

<circle cx="850" cy="570" r="280" fill="url(#greenGlow)">
  <animateTransform
    attributeName="transform"
    type="translate"
    values="0 0;30 -25;0 0"
    dur="11s"
    repeatCount="indefinite"/>
</circle>

<!-- Tiny particles -->
<g fill="#22D3EE">

  <circle cx="54" cy="90" r="1.4">
    <animate attributeName="opacity"
      values=".1;.8;.1" dur="3s" repeatCount="indefinite"/>
    <animateTransform attributeName="transform"
      type="translate" values="0 0;0 -18;0 0"
      dur="5s" repeatCount="indefinite"/>
  </circle>

  <circle cx="320" cy="70" r="1">
    <animate attributeName="opacity"
      values=".1;.7;.1" dur="4s" repeatCount="indefinite"/>
  </circle>

  <circle cx="1050" cy="150" r="1.3">
    <animate attributeName="opacity"
      values=".1;.9;.1" dur="3.5s" repeatCount="indefinite"/>
  </circle>

  <circle cx="980" cy="500" r="1">
    <animate attributeName="opacity"
      values=".05;.8;.05" dur="4.5s" repeatCount="indefinite"/>
  </circle>

  <circle cx="430" cy="550" r="1.3">
    <animate attributeName="opacity"
      values=".1;.7;.1" dur="3s" repeatCount="indefinite"/>
  </circle>

  <circle cx="720" cy="50" r="1">
    <animate attributeName="opacity"
      values=".1;.8;.1" dur="5s" repeatCount="indefinite"/>
  </circle>

</g>

<!-- Glass reflection -->
<rect x="-100" y="-100" width="650" height="850"
  fill="#FFFFFF" opacity=".018"
  transform="rotate(18 200 300)">
  <animateTransform
    attributeName="transform"
    type="translate"
    values="-650 0;1250 0;-650 0"
    dur="14s"
    repeatCount="indefinite"/>
</rect>

<!-- ======================================================= -->
<!-- LEFT PANEL -->
<!-- ======================================================= -->

<rect x="28" y="28" width="425" height="554"
  rx="25"
  fill="url(#glass)"
  stroke="rgba(255,255,255,.08)"
  stroke-width="1"/>

<!-- Left glowing edge -->
<rect x="28" y="28" width="425" height="554"
  rx="25"
  fill="none"
  stroke="url(#borderGradient)"
  stroke-width="1.2"
  opacity=".75"/>

<!-- Terminal label -->
<text x="58" y="66"
  fill="#64748B"
  font-family="monospace"
  font-size="11"
  letter-spacing="2">
  KASHAN@DEV ~ /PROFILE
</text>

<circle cx="395" cy="61" r="4" fill="#10B981">
  <animate attributeName="opacity"
    values=".25;1;.25"
    dur="2s"
    repeatCount="indefinite"/>
</circle>

<!-- ======================================================= -->
<!-- ASCII PORTRAIT -->
<!-- ======================================================= -->

<g
  font-family="monospace"
  font-size="13"
  font-weight="600"
  fill="url(#asciiGradient)"
  opacity=".94">

  <text x="65" y="120">
    <tspan opacity="0">
      &lt;/&gt;───────────────&lt;/&gt;
      <animate attributeName="opacity"
        values="0;1" dur="1s" begin=".3s"
        fill="freeze"/>
    </tspan>
  </text>

  <text x="65" y="139">
    <tspan opacity="0">
      │   ▄████████▄    │
      <animate attributeName="opacity"
        values="0;1" dur="1s" begin=".7s"
        fill="freeze"/>
    </tspan>
  </text>

  <text x="65" y="158">
    <tspan opacity="0">
      │  ████████████   │
      <animate attributeName="opacity"
        values="0;1" dur="1s" begin="1.1s"
        fill="freeze"/>
    </tspan>
  </text>

  <text x="65" y="177">
    <tspan opacity="0">
      │ ███  ◉  ◉  ███  │
      <animate attributeName="opacity"
        values="0;1" dur="1s" begin="1.5s"
        fill="freeze"/>
    </tspan>
  </text>

  <text x="65" y="196">
    <tspan opacity="0">
      │ ███   ▄   ███   │
      <animate attributeName="opacity"
        values="0;1" dur="1s" begin="1.9s"
        fill="freeze"/>
    </tspan>
  </text>

  <text x="65" y="215">
    <tspan opacity="0">
      │  ████████████   │
      <animate attributeName="opacity"
        values="0;1" dur="1s" begin="2.3s"
        fill="freeze"/>
    </tspan>
  </text>

  <text x="65" y="234">
    <tspan opacity="0">
      │   ██████████    │
      <animate attributeName="opacity"
        values="0;1" dur="1s" begin="2.7s"
        fill="freeze"/>
    </tspan>
  </text>

  <text x="65" y="253">
    <tspan opacity="0">
      │    ████████     │
      <animate attributeName="opacity"
        values="0;1" dur="1s" begin="3.1s"
        fill="freeze"/>
    </tspan>
  </text>

  <text x="65" y="272">
    <tspan opacity="0">
      │  ████████████   │
      <animate attributeName="opacity"
        values="0;1" dur="1s" begin="3.5s"
        fill="freeze"/>
    </tspan>
  </text>

  <text x="65" y="291">
    <tspan opacity="0">
      │ ███  █████  ███ │
      <animate attributeName="opacity"
        values="0;1" dur="1s" begin="3.9s"
        fill="freeze"/>
    </tspan>
  </text>

  <text x="65" y="310">
    <tspan opacity="0">
      &lt;/&gt;───────────────&lt;/&gt;
      <animate attributeName="opacity"
        values="0;1" dur="1s" begin="4.3s"
        fill="freeze"/>
    </tspan>
  </text>

</g>

<!-- ASCII floating -->
<animateTransform
  attributeName="transform"
  type="translate"
  values="0 0;0 -4;0 0"
  dur="5s"
  repeatCount="indefinite"/>

<!-- Scanline -->
<rect x="40" y="-80" width="400" height="65"
  fill="url(#scanline)"
  opacity=".65">
  <animateTransform
    attributeName="transform"
    type="translate"
    values="0 0;0 440;0 0"
    dur="6s"
    repeatCount="indefinite"/>
</rect>

<!-- ASCII glow -->
<text x="65" y="345"
  font-family="monospace"
  font-size="12"
  fill="#22D3EE"
  opacity=".45">
  &gt; initializing full_stack_profile...
  <animate attributeName="opacity"
    values=".15;.65;.15"
    dur="3s"
    repeatCount="indefinite"/>
</text>

<text x="65" y="370"
  font-family="monospace"
  font-size="12"
  fill="#7C3AED"
  opacity=".7">
  &gt; systems.ready
</text>

<text x="65" y="395"
  font-family="monospace"
  font-size="12"
  fill="#94A3B8">
  &gt; status:
  <tspan fill="#10B981"> ONLINE</tspan>
</text>

<!-- ======================================================= -->
<!-- RIGHT TERMINAL -->
<!-- ======================================================= -->

<rect x="475" y="28" width="677" height="554"
  rx="25"
  fill="#0F172A"
  fill-opacity=".72"
  stroke="rgba(255,255,255,.08)"
  stroke-width="1"/>

<rect x="475" y="28" width="677" height="554"
  rx="25"
  fill="none"
  stroke="url(#borderGradient)"
  stroke-width="1.2"/>

<!-- Terminal top bar -->
<line x1="475" y1="83" x2="1152" y2="83"
  stroke="#FFFFFF"
  stroke-opacity=".07"/>

<circle cx="505" cy="56" r="5" fill="#EF4444" opacity=".8"/>
<circle cx="524" cy="56" r="5" fill="#F59E0B" opacity=".8"/>
<circle cx="543" cy="56" r="5" fill="#10B981" opacity=".8"/>

<text x="570" y="61"
  fill="#64748B"
  font-family="monospace"
  font-size="11">
  kashan — terminal
</text>

<!-- Greeting -->
<g font-family="monospace">

  <text x="520" y="122"
    fill="#64748B"
    font-size="12">
    ~/profile $ whoami
  </text>

  <text x="520" y="153"
    fill="#F8FAFC"
    font-size="28"
    font-weight="700">
    Hi 👋 I'm Kashan
  </text>

  <!-- Animated typing line -->
  <text x="520" y="188"
    fill="url(#accent)"
    font-size="15"
    font-weight="600">
    <tspan>
      Full-Stack Developer
      <animate attributeName="opacity"
        values="0;1;1;0"
        dur="12s"
        repeatCount="indefinite"/>
    </tspan>
  </text>

  <text x="520" y="188"
    fill="url(#accent)"
    font-size="15"
    font-weight="600"
    opacity="0">
    Frontend Engineer
    <animate attributeName="opacity"
      values="0;0;1;1;0"
      dur="12s"
      repeatCount="indefinite"/>
  </text>

  <text x="520" y="188"
    fill="url(#accent)"
    font-size="15"
    font-weight="600"
    opacity="0">
    Open Source Contributor
    <animate attributeName="opacity"
      values="0;0;0;1;0"
      dur="12s"
      repeatCount="indefinite"/>
  </text>

  <text x="520" y="188"
    fill="#22D3EE"
    font-size="15">
    ▌
    <animate attributeName="opacity"
      values="1;0;1;0;1"
      dur="1s"
      repeatCount="indefinite"/>
  </text>

  <!-- Divider -->
  <line x1="520" y1="212" x2="1107" y2="212"
    stroke="#FFFFFF"
    stroke-opacity=".06"/>

  <!-- Profile information -->

  <text x="520" y="245"
    fill="#64748B"
    font-size="11">
    LOCATION
  </text>

  <text x="665" y="245"
    fill="#F8FAFC"
    font-size="12">
    Pakistan
  </text>

  <text x="520" y="274"
    fill="#64748B"
    font-size="11">
    EDUCATION
  </text>

  <text x="665" y="274"
    fill="#F8FAFC"
    font-size="12">
    Computer Science / Software Development
  </text>

  <text x="520" y="303"
    fill="#64748B"
    font-size="11">
    FOCUS
  </text>

  <text x="665" y="303"
    fill="#22D3EE"
    font-size="12">
    Full-Stack Web Development
  </text>

  <text x="520" y="332"
    fill="#64748B"
    font-size="11">
    PORTFOLIO
  </text>

  <text x="665" y="332"
    fill="#94A3B8"
    font-size="12">
    your-portfolio.com
  </text>

  <text x="520" y="361"
    fill="#64748B"
    font-size="11">
    EMAIL
  </text>

  <text x="665" y="361"
    fill="#94A3B8"
    font-size="12">
    your-email@example.com
  </text>

  <!-- Skills -->
  <text x="520" y="401"
    fill="#F8FAFC"
    font-size="13"
    font-weight="700">
    STACK
  </text>

  <!-- Skill pills -->
  <g font-size="10" font-family="monospace">

    <rect x="520" y="420" width="62" height="27" rx="13"
      fill="#FFFFFF" fill-opacity=".045"
      stroke="#22D3EE" stroke-opacity=".3">
      <animateTransform attributeName="transform"
        type="scale"
        values="1;1.04;1"
        dur="3s" repeatCount="indefinite"/>
    </rect>
    <text x="535" y="438" fill="#CBD5E1">HTML</text>

    <rect x="592" y="420" width="58" height="27" rx="13"
      fill="#FFFFFF" fill-opacity=".045"
      stroke="#7C3AED" stroke-opacity=".3"/>
    <text x="608" y="438" fill="#CBD5E1">CSS</text>

    <rect x="660" y="420" width="86" height="27" rx="13"
      fill="#FFFFFF" fill-opacity=".045"
      stroke="#22D3EE" stroke-opacity=".3"/>
    <text x="674" y="438" fill="#CBD5E1">JavaScript</text>

    <rect x="756" y="420" width="76" height="27" rx="13"
      fill="#FFFFFF" fill-opacity=".045"
      stroke="#7C3AED" stroke-opacity=".3"/>
    <text x="771" y="438" fill="#CBD5E1">Bootstrap</text>

    <rect x="842" y="420" width="67" height="27" rx="13"
      fill="#FFFFFF" fill-opacity=".045"
      stroke="#22D3EE" stroke-opacity=".3"/>
    <text x="857" y="438" fill="#CBD5E1">jQuery</text>

    <rect x="919" y="420" width="60" height="27" rx="13"
      fill="#FFFFFF" fill-opacity=".045"
      stroke="#7C3AED" stroke-opacity=".3"/>
    <text x="933" y="438" fill="#CBD5E1">React</text>

    <rect x="989" y="420" width="78" height="27" rx="13"
      fill="#FFFFFF" fill-opacity=".045"
      stroke="#10B981" stroke-opacity=".3"/>
    <text x="1003" y="438" fill="#CBD5E1">Tailwind</text>

    <rect x="520" y="457" width="68" height="27" rx="13"
      fill="#FFFFFF" fill-opacity=".045"
      stroke="#10B981" stroke-opacity=".3"/>
    <text x="536" y="475" fill="#CBD5E1">Python</text>

    <rect x="598" y="457" width="51" height="27" rx="13"
      fill="#FFFFFF" fill-opacity=".045"
      stroke="#22D3EE" stroke-opacity=".3"/>
    <text x="612" y="475" fill="#CBD5E1">Git</text>

    <rect x="659" y="457" width="62" height="27" rx="13"
      fill="#FFFFFF" fill-opacity=".045"
      stroke="#7C3AED" stroke-opacity=".3"/>
    <text x="674" y="475" fill="#CBD5E1">Figma</text>

  </g>

  <!-- Socials -->
  <text x="520" y="524"
    fill="#64748B"
    font-size="11">
    CONNECT
  </text>

  <text x="605" y="524"
    fill="#F8FAFC"
    font-size="12">
    GitHub
  </text>

  <text x="675" y="524"
    fill="#F8FAFC"
    font-size="12">
    LinkedIn
  </text>

  <text x="760" y="524"
    fill="#F8FAFC"
    font-size="12">
    Twitter
  </text>

  <text x="835" y="524"
    fill="#F8FAFC"
    font-size="12">
    Portfolio
  </text>

  <!-- Terminal cursor -->
  <text x="520" y="553"
    fill="#10B981"
    font-size="11">
    $
  </text>

  <rect x="536" y="542" width="7" height="14"
    fill="#22D3EE">
    <animate attributeName="opacity"
      values="1;0;1"
      dur="1s"
      repeatCount="indefinite"/>
  </rect>

</g>

<!-- Moving scanline over whole hero -->
<rect x="0" y="-100" width="1180" height="90"
  fill="url(#scanline)"
  opacity=".5">
  <animateTransform
    attributeName="transform"
    type="translate"
    values="0 0;0 720;0 0"
    dur="10s"
    repeatCount="indefinite"/>
</rect>
```

  </g>

  <!-- Outer border -->

<rect x="1" y="1" width="1178" height="608"
 rx="30"
 fill="none"
 stroke="url(#borderGradient)"
 stroke-width="1.5"/>

</svg>

</div>

---

## 👨‍💻 About Me

I'm **Kashan**, a developer focused on building modern, scalable and user-friendly web applications.

My primary focus is **full-stack development**, combining polished frontend experiences with reliable backend systems and practical software architecture.

```text
┌─────────────────────────────────────────────────────────────┐
│  $ ./kashan --status                                        │
│                                                             │
│  Frontend       ████████████████████░░░░  85%              │
│  Backend        █████████████████░░░░░░░  75%              │
│  UI Engineering ███████████████████░░░░░  80%              │
│  Databases      ███████████████░░░░░░░░░  65%              │
│  Dev Tools      ████████████████████░░░░  85%              │
│                                                             │
│  STATUS: ONLINE                                             │
└─────────────────────────────────────────────────────────────┘
```

## ⚡ Tech Stack

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-030712?style=for-the-badge\&logo=html5\&logoColor=E34F26)
![CSS3](https://img.shields.io/badge/CSS3-030712?style=for-the-badge\&logo=css3\&logoColor=1572B6)
![JavaScript](https://img.shields.io/badge/JavaScript-030712?style=for-the-badge\&logo=javascript\&logoColor=F7DF1E)
![Bootstrap](https://img.shields.io/badge/Bootstrap-030712?style=for-the-badge\&logo=bootstrap\&logoColor=7952B3)
![jQuery](https://img.shields.io/badge/jQuery-030712?style=for-the-badge\&logo=jquery\&logoColor=0769AD)
![React](https://img.shields.io/badge/React-030712?style=for-the-badge\&logo=react\&logoColor=61DAFB)
![TailwindCSS](https://img.shields.io/badge/Tailwind-030712?style=for-the-badge\&logo=tailwindcss\&logoColor=06B6D4)
![Python](https://img.shields.io/badge/Python-030712?style=for-the-badge\&logo=python\&logoColor=3776AB)
![Git](https://img.shields.io/badge/Git-030712?style=for-the-badge\&logo=git\&logoColor=F05032)
![Figma](https://img.shields.io/badge/Figma-030712?style=for-the-badge\&logo=figma\&logoColor=F24E1E)

</div>

---

## 🚀 What I'm Building

<details>
<summary><b>🌐 Full-Stack Web Applications</b></summary>

<br>

Building complete web applications from responsive interfaces to backend logic, APIs, databases and deployment.

</details>

<details>
<summary><b>🎨 Modern UI Engineering</b></summary>

<br>

Creating clean interfaces with responsive layouts, reusable components, animations and modern UX principles.

</details>

<details>
<summary><b>⚙️ Backend & APIs</b></summary>

<br>

Working toward robust backend architectures, API development, database integration and scalable application logic.

</details>

<details>
<summary><b>🤖 AI & Intelligent Applications</b></summary>

<br>

Exploring practical ways to integrate AI capabilities into modern web applications and developer workflows.

</details>

---

## 📊 GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=YOUR_GITHUB_USERNAME&show_icons=true&hide_border=true&bg_color=030712&title_color=22D3EE&text_color=94A3B8&icon_color=7C3AED&ring_color=22D3EE" width="49%" />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=YOUR_GITHUB_USERNAME&hide_border=true&background=030712&stroke=0F172A&ring=7C3AED&fire=22D3EE&currStreakLabel=F8FAFC&sideLabels=94A3B8&dates=64748B" width="49%" />

</div>

<br>

<div align="center">

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_GITHUB_USERNAME&layout=compact&hide_border=true&bg_color=030712&title_color=22D3EE&text_color=94A3B8" width="42%" />

</div>

---

## 🏆 GitHub Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=YOUR_GITHUB_USERNAME&theme=darkhub&no-frame=true&no-bg=true&margin-w=8&row=1" width="100%" />

</div>

---

## 🐍 Contribution Activity

<div align="center">

<img src="https://raw.githubusercontent.com/YOUR_GITHUB_USERNAME/YOUR_GITHUB_USERNAME/output/github-contribution-grid-snake.svg" alt="GitHub Contribution Snake" />

</div>

---

## 📈 Contribution Graph

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=YOUR_GITHUB_USERNAME&bg_color=030712&color=22D3EE&line=7C3AED&point=10B981&area=true&hide_border=true" width="100%" />

</div>

---

## 💡 Featured Projects

<details>
<summary><b>🚀 Project One — Full-Stack Application</b></summary>

<br>

**Description:**
A full-stack application focused on modern UI, application logic, API integration and responsive design.

**Stack:**
`React` `JavaScript` `Tailwind` `Python` `Git`

**Highlights:**

* Responsive interface
* Component-driven architecture
* API integration
* Modern user experience
* Scalable project structure

</details>

<details>
<summary><b>⚡ Project Two — Web Application</b></summary>

<br>

**Description:**
A modern web application designed around performance, usability and clean engineering.

**Stack:**
`HTML` `CSS` `JavaScript` `Bootstrap` `jQuery`

**Highlights:**

* Responsive design
* Interactive components
* Clean UI
* Cross-device compatibility

</details>

<details>
<summary><b>🤖 Project Three — AI / Developer Project</b></summary>

<br>

**Description:**
An experimental project exploring AI-powered functionality and intelligent application workflows.

**Stack:**
`Python` `JavaScript` `AI`

**Highlights:**

* AI integration
* Automation
* API-driven workflows
* Developer-focused tooling

</details>

---

## 🌐 Connect With Me

<div align="center">

<a href="https://github.com/YOUR_GITHUB_USERNAME">
<img src="https://img.shields.io/badge/GitHub-030712?style=for-the-badge&logo=github&logoColor=F8FAFC" />
</a>

<a href="https://linkedin.com/in/YOUR_LINKEDIN_USERNAME">
<img src="https://img.shields.io/badge/LinkedIn-030712?style=for-the-badge&logo=linkedin&logoColor=0A66C2" />
</a>

<a href="https://twitter.com/YOUR_TWITTER_USERNAME">
<img src="https://img.shields.io/badge/Twitter-030712?style=for-the-badge&logo=twitter&logoColor=38BDF8" />
</a>

<a href="https://YOUR_PORTFOLIO_URL">
<img src="https://img.shields.io/badge/Portfolio-030712?style=for-the-badge&logo=vercel&logoColor=F8FAFC" />
</a>

</div>

---

<div align="center">

### `Building • Learning • Shipping`

<br>

<img src="https://komarev.com/ghpvc/?username=YOUR_GITHUB_USERNAME&style=for-the-badge&color=7C3AED&label=PROFILE+VIEWS" />

<br><br>

**Thanks for visiting my profile.**

</div>

-------------------------------------
<div align="center">

<a href="https://capsule-render.vercel.app/">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D0221,50:4C1D95,100:312E81&height=220&section=header&text=KASHAN%20ALI%20KHAN&fontSize=42&fontColor=FFFFFF&fontAlignY=38&animation=fadeIn&desc=SOFTWARE%20ENGINEER%20%7C%20WEB%20DEVELOPER%20%7C%20IT%20EDUCATOR&descAlignY=58&descSize=17" width="100%"/>
</a>

<a href="https://readme-typing-svg.demolab.com/">
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=900&color=A78BFA&center=true&vCenter=true&width=800&lines=Software+Engineering+Student+%7C+UBIT;Web+Developer+%7C+IT+Educator;Full-Stack+Web+Application+Development;Building+Practical+Digital+Solutions;Always+Learning.+Always+Building." alt="Typing SVG"/>
</a>

<br/>

![Software Engineering](https://img.shields.io/badge/Software%20Engineering-2024%20%E2%80%93%20Present-7C3AED?style=for-the-badge&logo=academia&logoColor=white)
![University of Karachi](https://img.shields.io/badge/UBIT-University%20of%20Karachi-4C1D95?style=for-the-badge&logo=bookstack&logoColor=white)
![Location](https://img.shields.io/badge/Karachi%2C%20Pakistan-312E81?style=for-the-badge&logo=googlemaps&logoColor=white)

<br/>

<a href="https://github.com/Kashankhanzada?tab=repositories"><img src="https://img.shields.io/badge/PORTFOLIO-7C3AED?style=for-the-badge&logo=github&logoColor=white" /></a>
<a href="https://www.linkedin.com/in/kashan-ali-khan-a07880284"><img src="https://img.shields.io/badge/LINKEDIN-4C1D95?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:karachimarketing6@gmail.com"><img src="https://img.shields.io/badge/EMAIL-6D28D9?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="https://github.com/Kashankhanzada"><img src="https://img.shields.io/badge/GITHUB-312E81?style=for-the-badge&logo=github&logoColor=white" /></a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=Kashankhanzada&style=for-the-badge&color=7C3AED&label=PROFILE+VIEWS" />
<img src="https://img.shields.io/github/followers/Kashankhanzada?style=for-the-badge&color=4C1D95&label=FOLLOWERS" />
<img src="https://img.shields.io/github/stars/Kashankhanzada?style=for-the-badge&color=6D28D9&label=STARS" />

</div>

---

# About

I am a **Software Engineering student at the University of Karachi (UBIT)** with **3+ years of hands-on experience** spanning web development, IT instruction, and academic leadership. My work combines software engineering fundamentals with practical web application development and technical education.

I currently serve as **Head of Department (Computer & IT) at AIMS Computer & Language Institute**, while also working as a **Cambridge Teacher for Computer Science & Islamiyat** and continuing freelance web development through **Fiverr and Upwork**.

My engineering interests center around building responsive websites, modern web applications, practical software solutions, and continuously expanding my knowledge across software engineering, artificial intelligence, databases, application development, and system design.

### Engineering Focus

- Software Engineering & Software Development
- Full-Stack Web Development
- Responsive Web Application Development
- Frontend Engineering
- Backend & REST API Integration
- Database Management
- Object-Oriented Programming
- Data Structures & Algorithms
- Software Architecture & Design
- Artificial Intelligence — academic exposure
- IT Education & Technical Training
- Curriculum & Academic Technology Development

### Open To

**Freelance Web Development · Software Engineering Opportunities · Web Application Projects · Technical Collaboration · Open Source · Educational Technology**

---

# Tech Stack

### Languages

<p align="left">
<img src="https://skillicons.dev/icons?i=html,css,js,php,c,cpp,java,python" />
</p>

### Frontend

<p align="left">
<img src="https://skillicons.dev/icons?i=react,bootstrap,tailwind,jquery" />
</p>

### Backend & Databases

<p align="left">
<img src="https://skillicons.dev/icons?i=php,mysql,mongodb,firebase" />
</p>

### Cloud, DevOps & Tooling

<p align="left">
<img src="https://skillicons.dev/icons?i=git,github,vercel,vscode,idea,pycharm,apache" />
</p>

### Design & Creative Tooling

<p align="left">
<img src="https://skillicons.dev/icons?i=figma,photoshop,canva" />
</p>

<table>
<tr><td><b>Languages</b></td><td>HTML5 · CSS3 · JavaScript · PHP · C · C++ · Java · Python</td></tr>
<tr><td><b>Frameworks</b></td><td>Bootstrap · Tailwind CSS · React JS · jQuery</td></tr>
<tr><td><b>Databases</b></td><td>MySQL · MongoDB</td></tr>
<tr><td><b>Platforms</b></td><td>Vercel · Firebase · Render · Apache</td></tr>
<tr><td><b>Development</b></td><td>VS Code · IntelliJ IDEA · PyCharm · Adobe Dreamweaver · Dev-C++ · Turbo C</td></tr>
<tr><td><b>Creative</b></td><td>Adobe Photoshop · Canva · Macromedia Flash · Adobe Animate</td></tr>
</table>

---

# AI / ML Expertise

My current AI background is primarily **academic**, supported by Artificial Intelligence coursework within my software engineering studies rather than a claimed professional AI/ML specialization.

| Domain | Proficiency | Details |
|---|---|---|
| Artificial Intelligence | Academic | Completed academic study in Artificial Intelligence as part of software engineering coursework. |
| Programming | Practical | Python, C, C++, Java and JavaScript experience. |
| Data Structures & Algorithms | Academic | Included within software engineering academic modules. |
| Database Systems | Academic / Practical | Database Management System coursework with MySQL and MongoDB skills. |
| Software Architecture | Academic | Academic module covering Software Architecture and Design. |
| Software Development | Practical | 3+ years of combined web development and IT experience. |

---

# Featured Projects

<details>
<summary><strong>Responsive Web Development — Client Projects</strong></summary>

### Responsive Web Development — Client Projects

Built and maintained **5+ responsive websites** for local and international clients through freelance work on Fiverr and Upwork. Projects involved modern frontend technologies, responsive design, REST API integration, and collaboration with designers and backend teams.

| Metric | Details |
|---|---|
| **Stack** | HTML5 · CSS3 · JavaScript · Bootstrap · Tailwind CSS · React JS |
| **Scale** | 5+ responsive websites |
| **Performance** | Site performance improved by up to 30% through asset optimisation, lazy loading and caching |
| **Security** | Integrated REST APIs and third-party services with client-focused development practices |
| **Impact** | Delivered web solutions for local and international clients |
| **Repository** | [GitHub Profile](https://github.com/Kashankhanzada) |

**Professional Scope**

- Responsive website development
- Modern frontend implementation
- UI development and optimisation
- REST API integration
- Third-party service integration
- Performance optimisation
- Client collaboration
- Cross-functional collaboration with designers and backend teams

</details>

<details>
<summary><strong>UI Redesign — Technology Media Client</strong></summary>

### UI Redesign — Technology Media Client

Led a UI redesign project for a technology-media client, focusing on improving the overall user experience and interface effectiveness.

| Metric | Details |
|---|---|
| **Stack** | Web Development · Frontend Technologies · UI Development |
| **Scale** | Client project |
| **Performance** | Focused on interface and user experience improvements |
| **Security** | Not specified in supplied source |
| **Impact** | Improved user retention by 20% |
| **Repository** | [GitHub Profile](https://github.com/Kashankhanzada) |

**Professional Scope**

- Led UI redesign activities
- Improved interface usability
- Applied frontend development practices
- Worked toward measurable user-retention improvement
- Collaborated within a client-focused development environment

</details>

---

# Experience

## Head of Department (HOD) — Computer & IT

**AIMS Computer & Language Institute, Karachi**  
**January 2026 – Present**

- Lead Computer & IT departmental operations
- Plan and implement updated technical curricula
- Align syllabi with industry trends and student requirements
- Coordinate staff and academic activities
- Manage timetable scheduling
- Coordinate with institute administration
- Mentor junior instructors
- Promote professional development

**Skills:** `Leadership` `Curriculum Design` `People Management` `IT Education` `Academic Planning`

---

## Cambridge Teacher — Computer Science & Islamiyat

**Hazrat Shah Jahangir Academy, Karachi**  
**August 2025 – Present**

- Deliver Computer Science lessons
- Develop lesson plans and assessments
- Create learning materials
- Align teaching with Cambridge International standards
- Monitor student progress
- Provide personalised academic feedback

**Skills:** `Computer Science` `Teaching` `Curriculum Development` `Assessment` `Communication`

---

## Freelance Web Developer

**Fiverr & Upwork**  
**June 2023 – Present**

- Built and maintained 5+ responsive websites
- Developed solutions using HTML5, CSS3, JavaScript, Bootstrap, Tailwind CSS and React JS
- Improved site performance by up to 30%
- Applied asset optimisation, lazy loading and caching techniques
- Integrated REST APIs
- Integrated third-party services
- Collaborated with designers and backend teams
- Led a UI redesign that improved user retention by 20%

**Skills:** `HTML5` `CSS3` `JavaScript` `Bootstrap` `Tailwind CSS` `React JS` `REST APIs` `Performance Optimisation`

---

## IT Instructor

**Global Computer Institute, Karachi**  
**June 2022 – April 2026**

- Delivered training in MS Office Suite
- Taught Adobe Photoshop
- Taught Web Development
- Delivered HTML, CSS, JavaScript, Bootstrap and React JS training
- Provided programming instruction
- Designed and updated course curricula
- Aligned courses with industry standards
- Delivered hands-on project-based instruction
- Provided real-time feedback
- Developed practical IT skills among students

**Skills:** `IT Training` `Web Development` `Programming` `Curriculum Design` `Project-Based Learning`

---

# Achievements

<div align="center">

| Recognition | Details |
|---|---|
| **5+ Websites Delivered** | Built and maintained 5+ responsive websites for local and international clients. |
| **30% Performance Improvement** | Improved website performance by up to 30% through optimisation, lazy loading and caching. |
| **20% User Retention Improvement** | Led a UI redesign project that improved user retention by 20%. |
| **Academic Contribution Recognition** | Received Certificate of Appreciation for Academic Contribution from Awaz Institute of Media & Management Sciences. |
| **Department Leadership** | Serving as Head of Department for Computer & IT since January 2026. |
| **3+ Years Experience** | Combined experience across web development, IT instruction and academic leadership. |

</div>

---

# Certifications

### Global Computer Institute

![Microsoft Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![Microsoft Office](https://img.shields.io/badge/Microsoft%20Office-D83B01?style=for-the-badge&logo=microsoftoffice&logoColor=white)
![CIT](https://img.shields.io/badge/Certificate%20of%20Information%20Technology-4C1D95?style=for-the-badge&logo=googleclassroom&logoColor=white)
![Web Development](https://img.shields.io/badge/Web%20Designing%20%26%20Development-7C3AED?style=for-the-badge&logo=html5&logoColor=white)

- **Microsoft Excel** — 26 February 2022
- **Microsoft Office** — 19 March 2021
- **Certificate of Information Technology (CIT)** — 01 September 2022
- **Diploma in Web Designing & Development** — 26 July 2025

### Awaz Institute of Media & Management Sciences

![Academic Contribution](https://img.shields.io/badge/Certificate%20of%20Appreciation-Academic%20Contribution-6D28D9?style=for-the-badge&logo=academia&logoColor=white)

- **Certificate of Appreciation — Academic Contribution** — 23 April 2025

### Bahria University Computing & Innovation Society

![MERN Stack](https://img.shields.io/badge/Summer%20Bootcamp-Intro%20to%20MERN%20Stack%20Development-312E81?style=for-the-badge&logo=react&logoColor=white)

- **Summer Bootcamp — Intro to MERN Stack Development** — June–August 2024

---

# Coding Profiles

<div align="center">

<a href="https://leetcode.com/"><img src="https://img.shields.io/badge/LEETCODE-Profile%20Not%20Provided-4C1D95?style=for-the-badge&logo=leetcode&logoColor=white" /></a>
<a href="https://www.geeksforgeeks.org/"><img src="https://img.shields.io/badge/GEEKSFORGEEKS-Profile%20Not%20Provided-312E81?style=for-the-badge&logo=geeksforgeeks&logoColor=white" /></a>
<a href="https://www.hackerrank.com/"><img src="https://img.shields.io/badge/HACKERRANK-Profile%20Not%20Provided-4C1D95?style=for-the-badge&logo=hackerrank&logoColor=white" /></a>
<a href="https://www.codechef.com/"><img src="https://img.shields.io/badge/CODECHEF-Profile%20Not%20Provided-6D28D9?style=for-the-badge&logo=codechef&logoColor=white" /></a>

</div>

---

# GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Kashankhanzada&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D0221&title_color=A78BFA&icon_color=8B5CF6&text_color=CBD5E1&include_all_commits=true&count_private=true" height="180"/>

<img src="[https://nirzak-streak-stats.vercel.app/](https://streak-stats.demolab.com?user=Kashankhanzada&hide_border=true&background=0D0221&ring=8B5CF6&fire=A78BFA&currStreakLabel=A78BFA)?user=Kashankhanzada&theme=tokyonight&hide_border=true&background=0D0221&ring=8B5CF6&fire=A78BFA&currStreakLabel=A78BFA" height="180"/>

<br/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Kashankhanzada&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D0221&title_color=A78BFA&text_color=CBD5E1&langs_count=10" height="180"/>

</div>

---

# GitHub Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=Kashankhanzada&theme=darkhub&no-frame=true&no-bg=true&margin-w=8&column=7" />

</div>

---

# Contribution Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Kashankhanzada&bg_color=0D0221&color=A78BFA&line=8B5CF6&point=C4B5FD&area=true&hide_border=true" width="100%"/>

</div>

---

# Contribution Snake

<div align="center">

<img src="https://raw.githubusercontent.com/Kashankhanzada/Kashankhanzada/output/github-contribution-grid-snake-dark.svg" alt="GitHub Contribution Snake" width="100%"/>

</div>

---

# Current Focus

```yaml
Learning:
  - Advanced Software Engineering
  - Artificial Intelligence
  - Data Structures and Algorithms
  - Software Architecture and Design
  - Database Management Systems
  - Operating Systems
  - Networking and Data Communication
  - Mobile Application Development

Building:
  - Responsive Websites
  - Modern Web Applications
  - Full-Stack Development Skills
  - Practical Software Solutions

Exploring:
  - AI
  - MERN Stack Development
  - Software Construction
  - Software Project Management
  - Computer Organization
  - Assembly Language

Open To:
  - Freelance Web Development
  - Software Engineering Opportunities
  - Web Application Development
  - Technical Collaboration
  - Open Source Contributions
  - Educational Technology
```

---

# Connect

<div align="center">

<a href="mailto:karachimarketing6@gmail.com"><img src="https://img.shields.io/badge/GMAIL-karachimarketing6%40gmail.com-6D28D9?style=for-the-badge&logo=gmail&logoColor=white" /></a>

<a href="https://www.linkedin.com/in/kashan-ali-khan-a07880284"><img src="https://img.shields.io/badge/LINKEDIN-Kashan%20Ali%20Khan-4C1D95?style=for-the-badge&logo=linkedin&logoColor=white" /></a>

<a href="https://github.com/Kashankhanzada"><img src="https://img.shields.io/badge/GITHUB-Kashankhanzada-312E81?style=for-the-badge&logo=github&logoColor=white" /></a>

<a href="https://github.com/Kashankhanzada?tab=repositories"><img src="https://img.shields.io/badge/PORTFOLIO-View%20Repositories-7C3AED?style=for-the-badge&logo=github&logoColor=white" /></a>

</div>

---

# Footer

<div align="center">

**"Building practical software, developing people, and continuously engineering a better future."**

<br/>

<a href="https://capsule-render.vercel.app/">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:312E81,50:4C1D95,100:0D0221&height=130&section=footer" width="100%"/>
</a>

</div>
