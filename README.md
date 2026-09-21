<!--
  ██████  ╔═╗ ╔═══╗██╗ ██████╗ ██████╗ ███████╗
  ╠╣ ╔═╗ ║ ║ ║   ║║║ ██╔════╝ ██╔══██╗██╔════╝
  ╠╣ ╚═╝║ ║ ║╚════╝║██║ ██║  ████║  ██║█████╗
  ╠╣ ╚═╝║ ╚═══╝  ╚═╝ ║║╚██╗  ╚██╗ ██╔╝██╔══╝
  ╠╣ ╚══╝   ╚═══╝  ╚═╝ ╚╚══╝   ╚═══╝╚═╝ ██║
  ⚡ Бесконечность · The Strongest · Six Eyes ⚡
-->

<div align="center">

<!-- ═══════════ ANIMATED HERO (Red × Blue × Hollow Purple) ═══════════ -->

<svg viewBox="0 0 900 320" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="smylorx — Satoru Gojo mode">
  <defs>
    <linearGradient id="gRad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#ff2d55">
        <animate attributeName="stop-color" values="#ff2d55;#1e90ff;#a18cd1;#ff2d55" dur="7s" repeatCount="indefinite" />
      </stop>
      <stop offset="50%" stop-color="#a18cd1">
        <animate attributeName="stop-color" values="#a18cd1;#ff2d55;#1e90ff;#a18cd1" dur="7s" repeatCount="indefinite" />
      </stop>
      <stop offset="100%" stop-color="#1e90ff">
        <animate attributeName="stop-color" values="#1e90ff;#a18cd1;#ff2d55;#1e90ff" dur="7s" repeatCount="indefinite" />
      </stop>
    </linearGradient>
    <linearGradient id="gLiquid" x1="0" y1="0" x2="900" y2="0" gradientUnits="userSpaceOnUse">
      <stop offset="0%" stop-color="#ff2d55" />
      <stop offset="100%" stop-color="#1e90ff" />
    </linearGradient>
    <filter id="glow" x="-40%" y="-40%" width="180%" height="180%">
      <feGaussianBlur stdDeviation="14" result="blur" />
      <feMerge>
        <feMergeNode in="blur" />
        <feMergeNode in="SourceGraphic" />
      </feMerge>
    </filter>
    <radialGradient id="eyeBlue" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#dff6ff" />
      <stop offset="60%" stop-color="#8fd3ff" />
      <stop offset="100%" stop-color="#1e90ff" />
    </radialGradient>
    <radialGradient id="eyeRed" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#ffe3e3" />
      <stop offset="60%" stop-color="#ff8596" />
      <stop offset="100%" stop-color="#ff2d55" />
    </radialGradient>
  </defs>

  <!-- background -->
  <rect width="900" height="320" rx="24" fill="#0b0f1a" />

  <!-- breathing gradient veil -->
  <rect width="900" height="320" rx="24" fill="url(#gRad)" opacity="0.28">
    <animate attributeName="opacity" values="0.16;0.45;0.16" dur="4.5s" repeatCount="indefinite" />
  </rect>

  <!-- moving shine beam -->
  <g opacity="0.35">
    <polygon points="-200,420 320,-100 420,-100 -100,420" fill="url(#gLiquid)">
      <animateTransform attributeName="transform" type="translate" values="-900,0;900,0" dur="6s" repeatCount="indefinite" />
    </polygon>
  </g>

  <!-- drifting particles -->
  <g fill="#8fd3ff">
    <circle cx="120" cy="60" r="2.5"><animate attributeName="cy" values="60;300;60" dur="9s" repeatCount="indefinite"/><animate attributeName="opacity" values="0;1;0" dur="9s" repeatCount="indefinite"/></circle>
    <circle cx="240" cy="40" r="2"><animate attributeName="cy" values="40;280;40" dur="11s" repeatCount="indefinite"/><animate attributeName="opacity" values="0;1;0" dur="11s" repeatCount="indefinite"/></circle>
    <circle cx="700" cy="50" r="2.5"><animate attributeName="cy" values="50;290;50" dur="8s" repeatCount="indefinite"/><animate attributeName="opacity" values="0;1;0" dur="8s" repeatCount="indefinite"/></circle>
    <circle cx="820" cy="70" r="2"><animate attributeName="cy" values="70;300;70" dur="10s" repeatCount="indefinite"/><animate attributeName="opacity" values="0;1;0" dur="10s" repeatCount="indefinite"/></circle>
    <circle cx="450" cy="30" r="1.8"><animate attributeName="cy" values="30;270;30" dur="12s" repeatCount="indefinite"/><animate attributeName="opacity" values="0;1;0" dur="12s" repeatCount="indefinite"/></circle>
  </g>
  <g fill="#ff8596">
    <circle cx="160" cy="90" r="2"><animate attributeName="cy" values="90;310;90" dur="7.5s" repeatCount="indefinite"/><animate attributeName="opacity" values="0;1;0" dur="7.5s" repeatCount="indefinite"/></circle>
    <circle cx="600" cy="45" r="2.5"><animate attributeName="cy" values="45;285;45" dur="9.5s" repeatCount="indefinite"/><animate attributeName="opacity" values="0;1;0" dur="9.5s" repeatCount="indefinite"/></circle>
    <circle cx="750" cy="60" r="2"><animate attributeName="cy" values="60;300;60" dur="10.5s" repeatCount="indefinite"/><animate attributeName="opacity" values="0;1;0" dur="10.5s" repeatCount="indefinite"/></circle>
  </g>

  <!-- Gojo's two techniques: RED orb (left) & BLUE orb (right) -->
  <circle cx="200" cy="150" r="58" fill="url(#eyeRed)" filter="url(#glow)" opacity="0.5">
    <animate attributeName="r" values="52;68;52" dur="3.2s" repeatCount="indefinite" />
    <animate attributeName="opacity" values="0.35;0.65;0.35" dur="3.2s" repeatCount="indefinite" />
  </circle>
  <circle cx="700" cy="150" r="58" fill="url(#eyeBlue)" filter="url(#glow)" opacity="0.5">
    <animate attributeName="r" values="68;52;68" dur="3.2s" repeatCount="indefinite" />
    <animate attributeName="opacity" values="0.35;0.65;0.35" dur="3.2s" repeatCount="indefinite" />
  </circle>

  <!-- main title -->
  <text x="450" y="118" text-anchor="middle" font-family="'Segoe UI', Arial, sans-serif" font-size="66" font-weight="800" fill="#ffffff" filter="url(#glow)">smylorx</text>

  <!-- animated gradient caption -->
  <text x="450" y="162" text-anchor="middle" font-family="'Segoe UI', Arial, sans-serif" font-size="26" font-weight="600" fill="url(#gRad)">
    ⚡ СИЛЬНЕЙШИЙ · THE STRONGEST ⚡
    <animate attributeName="opacity" values="0.95;0.55;0.95" dur="3s" repeatCount="indefinite" />
  </text>

  <text x="450" y="205" text-anchor="middle" font-family="'Segoe UI', Arial, sans-serif" font-size="17" fill="#c9d6ff">Бесконечность · Six Eyes · Красная × Синяя = Фиолетовая</text>

  <!-- blinking cursor -->
  <text x="452" y="248" text-anchor="middle" font-family="Consolas, monospace" font-size="16" fill="#8fd3ff">developer=true;</text>
  <rect x="520" y="234" width="10" height="18" fill="#ff2d55">
    <animate attributeName="opacity" values="1;0;1" dur="1s" repeatCount="indefinite" />
  </rect>

  <!-- floating infinity symbols -->
  <g fill="url(#gLiquid)" font-size="26" font-weight="bold">
    <text x="70" y="40">∞</text>
    <text x="330" y="300">∞</text>
    <text x="830" y="300">∞</text>
    <text x="520" y="45">∞</text>
  </g>
</svg>

</div>

<p align="center">
  <a href="https://github.com/smylorx"><img src="https://img.shields.io/badge/status-ONLINE-1e90ff?style=for-the-badge&logo=github&logoColor=white" alt="Status"/></a>
  <img src="https://img.shields.io/badge/mode-GOAJO_mode_activated-ff2d55?style=for-the-badge&logo=anilist&logoColor=white" alt="Mode"/>
  <img src="https://img.shields.io/badge/eyez-six_eyes-a18cd1?style=for-the-badge&logo=eye&logoColor=white" alt="Six Eyes"/>
  <img src="https://img.shields.io/badge/time-24%2F7-1e90ff?style=for-the-badge&logo=clockify&logoColor=white" alt="24/7"/>
  <img src="https://img.shields.io/badge/coffee-хочу_свою_косметику-ff2d55?style=for-the-badge&logo=buymeacoffee&logoColor=white" alt="Coffee"/>
</p>

<!-- ═══════════ THE GIF ═══════════ -->

<div align="center">
  <img src="https://media1.tenor.com/m/PcTVZK3aROQAAAAC/albanie.gif" alt="Albanie GIF" width="498" />
  <br>
  <sub><i>⚡ мой уровень нагрузки, когда открываю гитхаб ⚡</i> — <a href="https://tenor.com/ru/view/albanie-gif-4450916960139101412">gif на Tenor</a></sub>
</div>

<br/>

<!-- ═══════════ ABOUT ═══════════ -->

<div align="center">
  <h2>🌀 ОБО МНЕ / ABOUT ME 🌀</h2>
</div>

<pre align="center">
  👁️ Шесть глаз видят всё.
  ⚔️ Сильнейший — это не статус, а образ жизни.
  🌐 Строка за строкой превращаю мир в код.
  ⚡ Если ты устал — учись отдыхать, а не сдаваться (сам советую, но не следую).</pre>

<p align="center">
  <b>👨‍💻 Что я делаю:</b> пишу код, ломаю код, чиню код, снова пишу код.
  <br>
  <b>🎯 Цель:</b> достичь уровня, где на меня можно положиться так же, как Годжо на Бесконечность.
  <br>
  <b>🌙 Домен:</b> могу быть и «Синь» (спокойствие), и «Красный» (огонь) — зависит от дедлайнов.
</p>

<br/>

<!-- ═══════════ TECH STACK ═══════════ -->

<div align="center">
  <h2>🛠️ ТЕХНОЛОГИИ / TECH STACK 🛠️</h2>
  <p><i>Красный = любимое, Синий = в работе, Фиолетовый = осваиваю</i></p>
</div>

<p align="center">
  <b>⚡ Frontend</b><br>
  <img src="https://img.shields.io/badge/-JavaScript-ff2d55?style=for-the-badge&logo=javascript&logoColor=white" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/-TypeScript-1e90ff?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/-React-a18cd1?style=for-the-badge&logo=react&logoColor=white" alt="React"/>
  <img src="https://img.shields.io/badge/-Vue-1e90ff?style=for-the-badge&logo=vuedotjs&logoColor=white" alt="Vue"/>
  <img src="https://img.shields.io/badge/-HTML5-ff2d55?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"/>
  <img src="https://img.shields.io/badge/-CSS3-1e90ff?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3"/>
  <img src="https://img.shields.io/badge/-Tailwind-a18cd1?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind"/>
</p>

<p align="center">
  <b>⚙️ Backend</b><br>
  <img src="https://img.shields.io/badge/-Node.js-1e90ff?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node"/>
  <img src="https://img.shields.io/badge/-Python-ff2d55?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/-Go-a18cd1?style=for-the-badge&logo=go&logoColor=white" alt="Go"/>
  <img src="https://img.shields.io/badge/-Rust-ff2d55?style=for-the-badge&logo=rust&logoColor=white" alt="Rust"/>
  <img src="https://img.shields.io/badge/-PostgreSQL-1e90ff?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/-Redis-ff2d55?style=for-the-badge&logo=redis&logoColor=white" alt="Redis"/>
  <img src="https://img.shields.io/badge/-Docker-1e90ff?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
</p>

<p align="center">
  <b>🔧 Инструменты / Tools</b><br>
  <img src="https://img.shields.io/badge/-Git-ff2d55?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
  <img src="https://img.shields.io/badge/-Linux-1e90ff?style=for-the-badge&logo=linux&logoColor=white" alt="Linux"/>
  <img src="https://img.shields.io/badge/-VSCode-a18cd1?style=for-the-badge&logo=visualstudiocode&logoColor=white" alt="VSCode"/>
  <img src="https://img.shields.io/badge/-Figma-ff2d55?style=for-the-badge&logo=figma&logoColor=white" alt="Figma"/>
  <img src="https://img.shields.io/badge/-Photoshop-1e90ff?style=for-the-badge&logo=adobephotoshop&logoColor=white" alt="Photoshop"/>
</p>

<br/>

<!-- ═══════════ ANIMATED STATS ═══════════ -->

<div align="center">
  <h2>📊 МОЯ АНАЛИТИКА / MY ANALYTICS 📊</h2>
  <p><i>⚡ статистика дышит и подтягивается сама ⚡</i></p>
</div>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=smylorx&show_icons=true&locale=ru&theme=transparent&title_color=ff2d55&icon_color=1e90ff&text_color=ffffff&bg_color=0b0f1a&hide_border=true&count_private=true" alt="GitHub Stats" height="180"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=smylorx&layout=compact&locale=ru&theme=transparent&title_color=ff2d55&text_color=ffffff&bg_color=0b0f1a&hide_border=true" alt="Top Languages" height="180"/>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=smylorx&theme=transparent&stroke=1e90ff&ring=ff2d55&fire=ff2d55&currStreakNum=ffffff&sideNums=1e90ff&currStreakLabel=ff2d55&sideLabels=9fc9ff&dates=a18cd1&hide_border=true&locale=ru" alt="Streak Stats"/>
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=smylorx&bg_color=0b0f1a&color=1e90ff&line=ff2d55&point=ffffff&area=true&area_color=a18cd1&hide_border=true&radius=12" alt="Activity Graph" width="100%"/>
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=smylorx&theme=onedark&no-bg=true&no-frame=true&margin-w=15&margin-h=15&row=2&column=4" alt="Trophies"/>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=smylorx&color=blueviolet&style=flat-square&label=👁️+столько+глаз+тебя+увидело" alt="Profile views"/>
</p>

<br/>

<!-- ═══════════ QUOTE ═══════════ -->

<div align="center">
  <h2>♾️ ФИРМЕННАЯ ЦИТАТА / FAVORITE QUOTE ♾️</h2>
</div>

<div align="center">
  <b><i>«На небесах и земле… Я единственный — Досточтимый.»</i></b>
  <br>
  <sub>— Сатору Годжо, и это тоже я</sub>
</div>

<br/>

<div align="center">
  <b>💠 Техники, под которые я пишу код:</b>
  <br><br>
  <img src="https://img.shields.io/badge/Техника-Бланк-ff2d55?style=for-the-badge&logo=atom&logoColor=white" alt="Limitless"/>
  <img src="https://img.shields.io/badge/Инверсия-Красная-1e90ff?style=for-the-badge&logo=atom&logoColor=white" alt="Red"/>
  <img src="https://img.shields.io/badge/Синьори-Синяя-a18cd1?style=for-the-badge&logo=atom&logoColor=white" alt="Blue"/>
  <img src="https://img.shields.io/badge/Пустота-Бесконечности-ff2d55?style=for-the-badge&logo=atom&logoColor=white" alt="Domain"/>
</div>

<br/>

<!-- ═══════════ CONTACT ═══════════ -->

<div align="center">
  <h2>📡 ГДЕ МЕНЯ НАЙТИ / FIND ME 📡</h2>
</div>

<p align="center">
  <a href="https://github.com/smylorx"><img src="https://img.shields.io/badge/GitHub-smylorx-1e90ff?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
  <a href="https://t.me/username"><img src="https://img.shields.io/badge/Telegram-написать-ff2d55?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram"/></a>
  <a href="mailto:smylorx@example.com"><img src="https://img.shields.io/badge/Email-письмо-a18cd1?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

<br/>

<!-- ═══════════ FOOTER ═══════════ -->

<div align="center">
  <svg width="260" height="40" viewBox="0 0 260 40" xmlns="http://www.w3.org/2000/svg">
    <rect width="260" height="40" rx="12" fill="none"/>
    <text x="130" y="25" text-anchor="middle" font-family="'Segoe UI', Arial, sans-serif" font-size="15" fill="url(#gRad2)">∞ Бесконечность ∞</text>
    <defs>
      <linearGradient id="gRad2" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stop-color="#ff2d55"><animate attributeName="stop-color" values="#ff2d55;#1e90ff;#ff2d55" dur="3s" repeatCount="indefinite"/></stop>
        <stop offset="100%" stop-color="#1e90ff"><animate attributeName="stop-color" values="#1e90ff;#ff2d55;#1e90ff" dur="3s" repeatCount="indefinite"/></stop>
      </linearGradient>
    </defs>
  </svg>
  <br>
  <sub>Сделано с ♥, переливающимся красным и синим · Gojo Mode forever 🌀</sub>
</div>