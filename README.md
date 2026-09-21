<div align="center">

<!-- ═══ Two lights: Red × Blue ═══ -->

<svg viewBox="0 0 900 240" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="smylorx">
  <defs>
    <linearGradient id="gMain" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#ff2d55">
        <animate attributeName="stop-color" values="#ff2d55;#1e90ff;#ff2d55" dur="8s" repeatCount="indefinite" />
      </stop>
      <stop offset="100%" stop-color="#1e90ff">
        <animate attributeName="stop-color" values="#1e90ff;#ff2d55;#1e90ff" dur="8s" repeatCount="indefinite" />
      </stop>
    </linearGradient>
    <linearGradient id="gBar" x1="0" y1="0" x2="900" y2="0" gradientUnits="userSpaceOnUse">
      <stop offset="0%" stop-color="#ff2d55" />
      <stop offset="100%" stop-color="#1e90ff" />
    </linearGradient>
    <radialGradient id="lightRed" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#ff2d55" stop-opacity="0.9" />
      <stop offset="100%" stop-color="#ff2d55" stop-opacity="0" />
    </radialGradient>
    <radialGradient id="lightBlue" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#1e90ff" stop-opacity="0.9" />
      <stop offset="100%" stop-color="#1e90ff" stop-opacity="0" />
    </radialGradient>
  </defs>

  <rect width="900" height="240" rx="22" fill="#0d1117" />

  <!-- two lights -->
  <circle cx="180" cy="120" r="150" fill="url(#lightRed)">
    <animate attributeName="opacity" values="0.9;0.4;0.9" dur="4s" repeatCount="indefinite" />
  </circle>
  <circle cx="720" cy="120" r="150" fill="url(#lightBlue)">
    <animate attributeName="opacity" values="0.9;0.4;0.9" dur="4s" repeatCount="indefinite" />
  </circle>

  <!-- flowing gradient veil -->
  <rect width="900" height="240" rx="22" fill="url(#gMain)" opacity="0.14">
    <animate attributeName="opacity" values="0.08;0.2;0.08" dur="6s" repeatCount="indefinite" />
  </rect>

  <!-- shine beam -->
  <polygon points="-160,300 360,-60 400,-60 -120,300" fill="url(#gBar)" opacity="0.16">
    <animateTransform attributeName="transform" type="translate" values="-900,0;900,0" dur="7s" repeatCount="indefinite" />
  </polygon>

  <!-- orbit ring -->
  <circle cx="450" cy="98" r="92" fill="none" stroke="#1e90ff" stroke-width="1" stroke-dasharray="6 10" opacity="0.5">
    <animateTransform attributeName="transform" type="rotate" from="0 450 98" to="360 450 98" dur="18s" repeatCount="indefinite" />
  </circle>
  <circle cx="450" cy="98" r="116" fill="none" stroke="#ff2d55" stroke-width="1" stroke-dasharray="3 16" opacity="0.5">
    <animateTransform attributeName="transform" type="rotate" from="360 450 98" to="0 450 98" dur="22s" repeatCount="indefinite" />
  </circle>

  <!-- title with two-light rim -->
  <text x="453" y="98" text-anchor="middle" font-family="'Segoe UI', Arial, sans-serif" font-size="64" font-weight="800" fill="#ff2d55" opacity="0.85">smylorx</text>
  <text x="447" y="98" text-anchor="middle" font-family="'Segoe UI', Arial, sans-serif" font-size="64" font-weight="800" fill="#1e90ff" opacity="0.85">smylorx</text>
  <text x="450" y="98" text-anchor="middle" font-family="'Segoe UI', Arial, sans-serif" font-size="64" font-weight="800" fill="#ffffff">smylorx</text>

  <!-- subtitle: cycling words -->
  <text x="450" y="152" text-anchor="middle" font-family="'Segoe UI', Arial, sans-serif" font-size="22" fill="#ff2d55" font-weight="600">Developer</text>
  <text x="450" y="152" text-anchor="middle" font-family="'Segoe UI', Arial, sans-serif" font-size="22" fill="#1e90ff" font-weight="600">
    Coder
    <animate attributeName="opacity" values="0;0;1;1;0" dur="4s" repeatCount="indefinite" />
  </text>
  <rect x="516" y="140" width="10" height="20" fill="#ffffff">
    <animate attributeName="opacity" values="1;0;1" dur="0.8s" repeatCount="indefinite" />
  </rect>

  <!-- animated baseline -->
  <rect x="300" y="178" width="300" height="3" rx="2" fill="url(#gBar)">
    <animate attributeName="width" values="80;300;80" dur="4s" repeatCount="indefinite" />
    <animate attributeName="opacity" values="1;0.5;1" dur="4s" repeatCount="indefinite" />
  </rect>
</svg>

</div>

<br/>

<div align="center">
  <img src="https://media1.tenor.com/m/PcTVZK3aROQAAAAC/albanie.gif" alt="gif" width="498" />
</div>

<br/>

<!-- ═══════ Animated dashboard (always renders) ═══════ -->

<div align="center">
  <svg viewBox="0 0 900 250" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="dashboard">
    <defs>
      <linearGradient id="dBar" x1="0" y1="0" x2="900" y2="0" gradientUnits="userSpaceOnUse">
        <stop offset="0%" stop-color="#ff2d55" />
        <stop offset="100%" stop-color="#1e90ff" />
      </linearGradient>
    </defs>

    <rect width="900" height="250" rx="22" fill="#0d1117" />
    <rect width="900" height="250" rx="22" fill="#ff2d55" opacity="0.04">
      <animate attributeName="opacity" values="0.02;0.08;0.02" dur="5s" repeatCount="indefinite" />
    </rect>

    <!-- column dividers -->
    <line x1="299" y1="40" x2="299" y2="235" stroke="#21262d" stroke-width="1" />
    <line x1="601" y1="40" x2="601" y2="235" stroke="#21262d" stroke-width="1" />

    <!-- ── STATS ── -->
    <text x="164" y="64" text-anchor="middle" font-family="'Segoe UI', Arial, sans-serif" font-size="14" fill="#8b949e" letter-spacing="2">STATS</text>
    <rect x="55" y="95" width="198" height="8" rx="4" fill="#161b22" />
    <rect x="55" y="95" width="150" height="8" rx="4" fill="url(#dBar)">
      <animate attributeName="width" values="120;198;120" dur="3s" repeatCount="indefinite" />
    </rect>
    <rect x="55" y="118" width="198" height="8" rx="4" fill="#161b22" />
    <rect x="55" y="118" width="130" height="8" rx="4" fill="#1e90ff">
      <animate attributeName="width" values="170;110;170" dur="3.4s" repeatCount="indefinite" />
    </rect>
    <rect x="55" y="141" width="198" height="8" rx="4" fill="#161b22" />
    <rect x="55" y="141" width="110" height="8" rx="4" fill="url(#dBar)">
      <animate attributeName="width" values="90;150;90" dur="2.6s" repeatCount="indefinite" />
    </rect>
    <circle cx="253" cy="95" r="4" fill="#ff2d55">
      <animate attributeName="opacity" values="1;0;1" dur="1.2s" repeatCount="indefinite" />
    </circle>
    <circle cx="253" cy="118" r="4" fill="#1e90ff">
      <animate attributeName="opacity" values="0;1;0" dur="1.2s" repeatCount="indefinite" />
    </circle>
    <circle cx="253" cy="141" r="4" fill="#ff2d55">
      <animate attributeName="opacity" values="1;0;1" dur="1.6s" repeatCount="indefinite" />
    </circle>
    <text x="164" y="180" text-anchor="middle" font-family="'Segoe UI', Arial, sans-serif" font-size="26" font-weight="700" fill="url(#dBar)">∞</text>

    <!-- ── LANGUAGES ── -->
    <text x="450" y="64" text-anchor="middle" font-family="'Segoe UI', Arial, sans-serif" font-size="14" fill="#8b949e" letter-spacing="2">LANGUAGES</text>
    <rect x="395" y="88" width="12" height="12" rx="3" fill="#ff2d55" />
    <text x="415" y="99" font-family="'Segoe UI', Arial, sans-serif" font-size="13" fill="#c9d1d9">JavaScript</text>
    <rect x="415" y="108" width="160" height="5" rx="2" fill="#21262d"/>
    <rect x="415" y="108" width="132" height="5" rx="2" fill="#ff2d55">
      <animate attributeName="width" values="120;140;120" dur="3s" repeatCount="indefinite" />
    </rect>

    <rect x="395" y="128" width="12" height="12" rx="3" fill="#1e90ff" />
    <text x="415" y="139" font-family="'Segoe UI', Arial, sans-serif" font-size="13" fill="#c9d1d9">TypeScript</text>
    <rect x="415" y="148" width="160" height="5" rx="2" fill="#21262d"/>
    <rect x="415" y="148" width="112" height="5" rx="2" fill="#1e90ff">
      <animate attributeName="width" values="100;120;100" dur="3.5s" repeatCount="indefinite" />
    </rect>

    <rect x="395" y="168" width="12" height="12" rx="3" fill="#ff2d55" />
    <text x="415" y="179" font-family="'Segoe UI', Arial, sans-serif" font-size="13" fill="#c9d1d9">Python</text>
    <rect x="415" y="188" width="160" height="5" rx="2" fill="#21262d"/>
    <rect x="415" y="188" width="96" height="5" rx="2" fill="url(#dBar)">
      <animate attributeName="width" values="90;104;90" dur="2.8s" repeatCount="indefinite" />
    </rect>

    <!-- ── ACTIVITY ── -->
    <text x="736" y="64" text-anchor="middle" font-family="'Segoe UI', Arial, sans-serif" font-size="14" fill="#8b949e" letter-spacing="2">ACTIVITY</text>
    <line x1="610" y1="110" x2="860" y2="110" stroke="#21262d" stroke-width="1" />
    <line x1="610" y1="150" x2="860" y2="150" stroke="#21262d" stroke-width="1" />
    <line x1="610" y1="190" x2="860" y2="190" stroke="#21262d" stroke-width="1" />
    <path d="M610 200 C 640 185, 655 208, 685 165 S 740 128, 770 148 S 830 112, 860 135 L860 220 L610 220 Z"
          fill="url(#dBar)" opacity="0.22" />
    <path d="M610 200 C 640 185, 655 208, 685 165 S 740 128, 770 148 S 830 112, 860 135" fill="none" stroke="#1e90ff" stroke-width="2.5" stroke-linecap="round" />
    <circle r="6" fill="#ffffff">
      <animateMotion dur="6s" repeatCount="indefinite" path="M610 200 C 640 185, 655 208, 685 165 S 740 128, 770 148 S 830 112, 860 135" />
    </circle>
    <circle r="12" fill="#ff2d55" opacity="0.4">
      <animateMotion dur="6s" repeatCount="indefinite" path="M610 200 C 640 185, 655 208, 685 165 S 740 128, 770 148 S 830 112, 860 135" />
      <animate attributeName="opacity" values="0.4;0.1;0.4" dur="1.5s" repeatCount="indefinite" />
    </circle>
  </svg>
</div>

<br/>

<!-- ═══════ Streak (live) ═══════ -->

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=smylorx&theme=transparent&stroke=1e90ff&ring=ff2d55&fire=ff2d55&currStreakNum=ffffff&sideNums=1e90ff&currStreakLabel=ff2d55&sideLabels=8b949e&dates=8b949e&hide_border=true" alt="Streak"/>
</p>

<br/>

<!-- ═══════ TECH STACK ═══════ -->

<p align="center">
  <img src="https://img.shields.io/badge/-JavaScript-ff2d55?style=for-the-badge&logo=javascript&logoColor=white" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/-TypeScript-1e90ff?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/-React-ff2d55?style=for-the-badge&logo=react&logoColor=white" alt="React"/>
  <img src="https://img.shields.io/badge/-Python-1e90ff?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/-Node.js-ff2d55?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node"/>
  <img src="https://img.shields.io/badge/-PostgreSQL-1e90ff?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/-Docker-ff2d55?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/-Git-1e90ff?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
</p>

<br/>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=smylorx&color=blue&style=flat-square" alt="views"/>
</p>