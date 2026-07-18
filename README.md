<!-- MARKDOWN GITHUB README — SPIDER-MAN THEME -->
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Alanyuye10/Alan-spider-portfolio/refs/heads/main/public/favicon.svg">
    <img src="https://raw.githubusercontent.com/Alanyuye10/Alan-spider-portfolio/refs/heads/main/public/favicon.svg" width="0">
  </picture>
</p>

<div align="center" style="position:relative;overflow:hidden;min-height:520px;background:#050816;border-radius:24px;border:1px solid rgba(148,163,184,.14);padding:60px 30px 50px;margin-bottom:30px">

<!-- HERO SVG — all animations are inline SVG native (no CSS keyframes) -->
<svg style="position:absolute;inset:0;width:100%;height:100%;pointer-events:none" viewBox="0 0 800 600" preserveAspectRatio="xMidYMid slice">
  <defs>
    <filter id="blobBlur1"><feGaussianBlur stdDeviation="70"/></filter>
    <filter id="blobBlur2"><feGaussianBlur stdDeviation="50"/></filter>
  </defs>

  <!-- AMBIENT BLOBS with SVG animation -->
  <circle cx="680" cy="100" r="160" fill="#ef4444" opacity=".12" filter="url(#blobBlur1)">
    <animate attributeName="opacity" values=".12;.25;.12" dur="7s" repeatCount="indefinite"/>
    <animate attributeName="r" values="160;184;160" dur="7s" repeatCount="indefinite"/>
  </circle>
  <circle cx="520" cy="560" r="100" fill="#3b82f6" opacity=".12" filter="url(#blobBlur2)">
    <animate attributeName="opacity" values=".12;.25;.12" dur="9s" repeatCount="indefinite"/>
    <animate attributeName="r" values="100;115;100" dur="9s" repeatCount="indefinite"/>
  </circle>

  <!-- SPINNING WEB STRANDS (clockwise) -->
  <g>
    <animateTransform attributeName="transform" type="rotate" from="0 400 300" to="360 400 300" dur="30s" repeatCount="indefinite"/>
    <line x1="400" y1="300" x2="400" y2="0" stroke="#60a5fa" stroke-width=".5" opacity=".4"/>
    <line x1="400" y1="300" x2="590" y2="30" stroke="#f87171" stroke-width=".5" opacity=".4"/>
    <line x1="400" y1="300" x2="720" y2="180" stroke="#60a5fa" stroke-width=".5" opacity=".4"/>
    <line x1="400" y1="300" x2="800" y2="300" stroke="#f87171" stroke-width=".5" opacity=".4"/>
    <line x1="400" y1="300" x2="720" y2="420" stroke="#60a5fa" stroke-width=".5" opacity=".4"/>
    <line x1="400" y1="300" x2="590" y2="570" stroke="#f87171" stroke-width=".5" opacity=".4"/>
    <line x1="400" y1="300" x2="400" y2="600" stroke="#60a5fa" stroke-width=".5" opacity=".4"/>
    <line x1="400" y1="300" x2="210" y2="570" stroke="#f87171" stroke-width=".5" opacity=".4"/>
    <line x1="400" y1="300" x2="80" y2="420" stroke="#60a5fa" stroke-width=".5" opacity=".4"/>
    <line x1="400" y1="300" x2="0" y2="300" stroke="#f87171" stroke-width=".5" opacity=".4"/>
    <line x1="400" y1="300" x2="80" y2="180" stroke="#60a5fa" stroke-width=".5" opacity=".4"/>
    <line x1="400" y1="300" x2="210" y2="30" stroke="#f87171" stroke-width=".5" opacity=".4"/>
  </g>

  <!-- SPINNING WEB ARCS (counter-clockwise) -->
  <g opacity=".5">
    <animateTransform attributeName="transform" type="rotate" from="0 400 300" to="-360 400 300" dur="45s" repeatCount="indefinite"/>
    <path d="M280,160 Q400,100 520,160" stroke="rgba(96,165,250,.3)" stroke-width=".5" fill="none"/>
    <path d="M180,240 Q400,160 620,240" stroke="rgba(248,113,113,.3)" stroke-width=".5" fill="none"/>
    <path d="M120,300 Q400,220 680,300" stroke="rgba(96,165,250,.3)" stroke-width=".5" fill="none"/>
    <path d="M180,360 Q400,440 620,360" stroke="rgba(248,113,113,.3)" stroke-width=".5" fill="none"/>
    <path d="M280,440 Q400,500 520,440" stroke="rgba(96,165,250,.3)" stroke-width=".5" fill="none"/>
  </g>

  <!-- FLOATING PARTICLES -->
  <circle cx="200" cy="150" r="2" fill="#f87171" opacity=".3">
    <animate attributeName="cy" values="150;110;150" dur="8s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values=".3;.7;.3" dur="8s" repeatCount="indefinite"/>
  </circle>
  <circle cx="600" cy="100" r="1.5" fill="#60a5fa" opacity=".3">
    <animate attributeName="cy" values="100;60;100" dur="10s" repeatCount="indefinite" begin="2s"/>
    <animate attributeName="opacity" values=".3;.6;.3" dur="10s" repeatCount="indefinite" begin="2s"/>
  </circle>
  <circle cx="150" cy="400" r="1.8" fill="#f87171" opacity=".3">
    <animate attributeName="cy" values="400;360;400" dur="9s" repeatCount="indefinite" begin="4s"/>
    <animate attributeName="opacity" values=".3;.6;.3" dur="9s" repeatCount="indefinite" begin="4s"/>
  </circle>
  <circle cx="650" cy="450" r="2.2" fill="#60a5fa" opacity=".3">
    <animate attributeName="cy" values="450;410;450" dur="11s" repeatCount="indefinite" begin="1s"/>
    <animate attributeName="opacity" values=".3;.6;.3" dur="11s" repeatCount="indefinite" begin="1s"/>
  </circle>
  <circle cx="100" cy="250" r="1.2" fill="#f87171" opacity=".3">
    <animate attributeName="cy" values="250;220;250" dur="7s" repeatCount="indefinite" begin="3s"/>
    <animate attributeName="opacity" values=".3;.5;.3" dur="7s" repeatCount="indefinite" begin="3s"/>
  </circle>
  <circle cx="700" cy="200" r="1.6" fill="#60a5fa" opacity=".3">
    <animate attributeName="cy" values="200;160;200" dur="12s" repeatCount="indefinite" begin="5s"/>
    <animate attributeName="opacity" values=".3;.6;.3" dur="12s" repeatCount="indefinite" begin="5s"/>
  </circle>

  <!-- ORB DOTS -->
  <circle cx="96" cy="108" r="3.5" fill="#f87171" filter="url(#blobBlur1)">
    <animate attributeName="opacity" values=".35;.1;.35" dur="2.5s" repeatCount="indefinite"/>
    <animate attributeName="r" values="3.5;6.3;3.5" dur="2.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="760" cy="426" r="3.5" fill="#60a5fa" filter="url(#blobBlur2)">
    <animate attributeName="opacity" values=".35;.1;.35" dur="2.5s" repeatCount="indefinite" begin=".8s"/>
    <animate attributeName="r" values="3.5;6.3;3.5" dur="2.5s" repeatCount="indefinite" begin=".8s"/>
  </circle>
  <circle cx="264" cy="558" r="2" fill="#ef4444">
    <animate attributeName="opacity" values=".35;.1;.35" dur="2.5s" repeatCount="indefinite" begin="1.5s"/>
    <animate attributeName="r" values="2;3.6;2" dur="2.5s" repeatCount="indefinite" begin="1.5s"/>
  </circle>

  <!-- SCROLL ARROW (bottom center) -->
  <g transform="translate(400,570)">
    <text x="0" y="0" fill="#64748b" font-family="DM Mono,monospace" font-size="10" text-anchor="middle" letter-spacing="2">SCROLL</text>
    <path d="M-6,10 L0,18 L6,10" stroke="#64748b" stroke-width="1.5" fill="none">
      <animateTransform attributeName="transform" type="translate" values="0,0;0,6;0,0" dur="2s" repeatCount="indefinite"/>
    </path>
  </g>
</svg>

<!-- GRID PATTERN (inline CSS — works on GitHub) -->
<div style="position:absolute;inset:0;opacity:.12;background-image:linear-gradient(rgba(148,163,184,.08) 1px,transparent 1px),linear-gradient(90deg,rgba(148,163,184,.08) 1px,transparent 1px);background-size:72px 72px;mask-image:radial-gradient(ellipse 70% 70% at 50% 50%,black,transparent);-webkit-mask-image:radial-gradient(ellipse 70% 70% at 50% 50%,black,transparent);pointer-events:none"></div>

<!-- HERO CONTENT -->
<div style="position:relative;z-index:1">
  <div style="display:inline-block;padding:8px 16px 8px 12px;margin-bottom:30px;border:1px solid rgba(34,197,94,.19);border-radius:99px;background:rgba(34,197,94,.045);color:rgba(255,255,255,.7);font:500 9px 'DM Mono',monospace;letter-spacing:.08em;text-transform:uppercase">
    <span style="display:inline-flex;align-items:center;gap:6px">
      <svg width="6" height="6" viewBox="0 0 6 6" style="display:inline-block">
        <circle cx="3" cy="3" r="3" fill="#22c55e">
          <animate attributeName="opacity" values="1;.4;1" dur="2s" repeatCount="indefinite"/>
        </circle>
      </svg>
      Available for projects
    </span>
  </div>

  <div style="font-family:'Space Grotesk',sans-serif;letter-spacing:-.065em">
    <div style="color:#64748b;font:500 11px 'DM Mono',monospace;letter-spacing:.2em;margin-bottom:12px;text-transform:uppercase">👋 Hello, I'm</div>
    <h1 style="margin:0;font-size:clamp(3rem,8vw,5.5rem);font-weight:600;line-height:.9;color:white">
      Alanyuye10
    </h1>
    <div style="font-size:clamp(2rem,5vw,4rem);font-weight:600;line-height:1.1;margin-top:12px;background:linear-gradient(100deg,#fff 3%,#fca5a5 48%,#93c5fd 90%);background-clip:text;color:transparent">
      Friendly Neighborhood Developer
    </div>
  </div>

  <div style="margin-top:28px;display:flex;align-items:center;justify-content:center;gap:13px;color:#94a3b8;font-size:.92rem">
    <span style="color:#60a5fa;font:9px 'DM Mono',monospace">//</span>
    <strong style="color:white;font-weight:500">MERN Stack Developer</strong>
    <svg width="2" height="16" viewBox="0 0 2 16" style="display:inline-block">
      <rect width="2" height="16" fill="#60a5fa">
        <animate attributeName="opacity" values="1;0;1" dur=".8s" repeatCount="indefinite"/>
      </rect>
    </svg>
  </div>

  <p style="max-width:580px;margin:20px auto 0;color:#94a3b8;font-size:.95rem;line-height:1.75;text-align:center">
    Actively building my career as a <strong style="color:white">MERN Stack Developer</strong>, currently interning at <strong style="color:#f87171">Luminar Technolab</strong> in Kochi. I craft digital experiences that feel as good as they perform.
  </p>

  <div style="margin-top:36px;display:flex;align-items:center;justify-content:center;gap:12px;flex-wrap:wrap">
    <a href="https://github.com/Alanyuye10?tab=repositories" style="display:inline-flex;align-items:center;gap:10px;min-height:51px;padding:0 28px;border-radius:13px;background:linear-gradient(135deg,#dc2626,#2563eb);box-shadow:0 12px 35px rgba(220,38,38,.2),inset 0 1px 0 rgba(255,255,255,.25);color:white;font-size:.85rem;font-weight:600;text-decoration:none">View Repos ↓</a>
    <a href="https://wa.me/9567188533" style="display:inline-flex;align-items:center;gap:10px;min-height:51px;padding:0 28px;border:1px solid rgba(148,163,184,.14);border-radius:13px;background:rgba(255,255,255,.035);color:rgba(255,255,255,.85);font-size:.85rem;font-weight:600;text-decoration:none">Let's Talk →</a>
  </div>
</div>

</div>

<!-- DIVIDER -->
<div style="width:80px;height:4px;margin:60px auto;border-radius:4px;background:linear-gradient(90deg,#ef4444,#3b82f6)"></div>

<!-- ABOUT SECTION -->
<div align="center" style="margin-bottom:50px">
  <div style="display:inline-flex;align-items:center;gap:12px;color:#60a5fa;font:500 11px 'DM Mono',monospace;letter-spacing:.16em;text-transform:uppercase;margin-bottom:16px">
    <span style="display:inline-flex;align-items:center;justify-content:center;width:28px;height:28px;border:1px solid rgba(96,165,250,.3);border-radius:50%">🕷️</span>
    About Me
  </div>

  <div style="font-family:'Space Grotesk',sans-serif;font-size:clamp(1.2rem,2.5vw,1.8rem);font-weight:500;letter-spacing:-.035em;color:white;max-width:700px;margin:0 auto 24px;line-height:1.5">
    With great power comes great responsibility
  </div>

  <p style="max-width:650px;margin:0 auto;color:#94a3b8;font-size:.95rem;line-height:1.85">
    I'm a passionate developer who believes in writing clean, scalable code and building applications that make a real impact. From full-stack web apps to polished UI experiences, I bring the same dedication and attention to detail to every project I touch.
  </p>
</div>

<!-- STATS SECTION -->
<div align="center" style="margin-bottom:50px">
  <div style="display:inline-flex;align-items:center;gap:12px;color:#60a5fa;font:500 11px 'DM Mono',monospace;letter-spacing:.16em;text-transform:uppercase;margin-bottom:30px">
    <span style="display:inline-flex;align-items:center;justify-content:center;width:28px;height:28px;border:1px solid rgba(96,165,250,.3);border-radius:50%">📊</span>
    GitHub Stats
  </div>

  <div style="display:flex;flex-wrap:wrap;justify-content:center;gap:15px;margin-bottom:15px">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=Alanyuye10&show_icons=true&theme=radical&bg_color=0d1117&title_color=ef4444&icon_color=ef4444&text_color=c9d1d9&border_color=30363d&hide_border=true">
      <img src="https://github-readme-stats.vercel.app/api?username=Alanyuye10&show_icons=true&theme=radical&bg_color=0d1117&title_color=ef4444&icon_color=ef4444&text_color=c9d1d9&border_color=30363d&hide_border=true" width="420" alt="GitHub Stats">
    </picture>
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-streak-stats.herokuapp.com/?user=Alanyuye10&theme=radical&background=0d1117&stroke=ef4444&ring=ef4444&fire=ef4444&currStreakNum=c9d1d9&sideNums=c9d1d9&currStreakLabel=ef4444&sideLabels=ef4444&dates=64748b&hide_border=true">
      <img src="https://github-readme-streak-stats.herokuapp.com/?user=Alanyuye10&theme=radical&background=0d1117&stroke=ef4444&ring=ef4444&fire=ef4444&currStreakNum=c9d1d9&sideNums=c9d1d9&currStreakLabel=ef4444&sideLabels=ef4444&dates=64748b&hide_border=true" width="420" alt="Streak Stats">
    </picture>
  </div>

  <div style="display:flex;flex-wrap:wrap;justify-content:center;gap:15px;margin-bottom:15px">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=Alanyuye10&layout=compact&theme=radical&bg_color=0d1117&title_color=ef4444&text_color=c9d1d9&border_color=30363d&hide_border=true">
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Alanyuye10&layout=compact&theme=radical&bg_color=0d1117&title_color=ef4444&text_color=c9d1d9&border_color=30363d&hide_border=true" width="420" alt="Top Languages">
    </picture>
  </div>
</div>

<!-- TROPHY SECTION -->
<div align="center" style="margin-bottom:50px">
  <div style="display:inline-flex;align-items:center;gap:12px;color:#60a5fa;font:500 11px 'DM Mono',monospace;letter-spacing:.16em;text-transform:uppercase;margin-bottom:30px">
    <span style="display:inline-flex;align-items:center;justify-content:center;width:28px;height:28px;border:1px solid rgba(96,165,250,.3);border-radius:50%">🏆</span>
    Trophy Case
  </div>

  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-trophy.vercel.app/?username=Alanyuye10&theme=radical&no-frame=true&margin-w=8&margin-h=8&column=7">
    <img src="https://github-profile-trophy.vercel.app/?username=Alanyuye10&theme=radical&no-frame=true&margin-w=8&margin-h=8&column=7" width="90%" alt="Trophy">
  </picture>
</div>

<!-- TECH STACK -->
<div align="center" style="margin-bottom:50px">
  <div style="display:inline-flex;align-items:center;gap:12px;color:#60a5fa;font:500 11px 'DM Mono',monospace;letter-spacing:.16em;text-transform:uppercase;margin-bottom:30px">
    <span style="display:inline-flex;align-items:center;justify-content:center;width:28px;height:28px;border:1px solid rgba(96,165,250,.3);border-radius:50%">🛠️</span>
    Tech Stack
  </div>

  <div style="display:flex;flex-wrap:wrap;justify-content:center;gap:8px;max-width:750px;margin:0 auto 30px">
    <span style="padding:8px 18px;border:1px solid rgba(148,163,184,.14);border-radius:8px;background:rgba(239,68,68,.06);color:#fca5a5;font:500 13px 'DM Mono',monospace;cursor:default">MongoDB</span>
    <span style="padding:8px 18px;border:1px solid rgba(148,163,184,.14);border-radius:8px;background:rgba(59,130,246,.06);color:#93c5fd;font:500 13px 'DM Mono',monospace;cursor:default">Express.js</span>
    <span style="padding:8px 18px;border:1px solid rgba(148,163,184,.14);border-radius:8px;background:rgba(239,68,68,.06);color:#fca5a5;font:500 13px 'DM Mono',monospace;cursor:default">React</span>
    <span style="padding:8px 18px;border:1px solid rgba(148,163,184,.14);border-radius:8px;background:rgba(59,130,246,.06);color:#93c5fd;font:500 13px 'DM Mono',monospace;cursor:default">Node.js</span>
    <span style="padding:8px 18px;border:1px solid rgba(148,163,184,.14);border-radius:8px;background:rgba(239,68,68,.06);color:#fca5a5;font:500 13px 'DM Mono',monospace;cursor:default">TypeScript</span>
    <span style="padding:8px 18px;border:1px solid rgba(148,163,184,.14);border-radius:8px;background:rgba(59,130,246,.06);color:#93c5fd;font:500 13px 'DM Mono',monospace;cursor:default">JavaScript</span>
    <span style="padding:8px 18px;border:1px solid rgba(148,163,184,.14);border-radius:8px;background:rgba(239,68,68,.06);color:#fca5a5;font:500 13px 'DM Mono',monospace;cursor:default">HTML</span>
    <span style="padding:8px 18px;border:1px solid rgba(148,163,184,.14);border-radius:8px;background:rgba(59,130,246,.06);color:#93c5fd;font:500 13px 'DM Mono',monospace;cursor:default">CSS</span>
    <span style="padding:8px 18px;border:1px solid rgba(148,163,184,.14);border-radius:8px;background:rgba(239,68,68,.06);color:#fca5a5;font:500 13px 'DM Mono',monospace;cursor:default">Tailwind</span>
    <span style="padding:8px 18px;border:1px solid rgba(148,163,184,.14);border-radius:8px;background:rgba(59,130,246,.06);color:#93c5fd;font:500 13px 'DM Mono',monospace;cursor:default">Bootstrap</span>
    <span style="padding:8px 18px;border:1px solid rgba(148,163,184,.14);border-radius:8px;background:rgba(239,68,68,.06);color:#fca5a5;font:500 13px 'DM Mono',monospace;cursor:default">Git</span>
  </div>

  <div style="display:flex;flex-wrap:wrap;justify-content:center;gap:12px">
    <a href="https://skillicons.dev">
      <img src="https://skillicons.dev/icons?i=mongodb,express,react,nodejs,ts,js,html,css,tailwind,bootstrap,git,github,vscode&theme=dark&perline=13" alt="Skills">
    </a>
  </div>
</div>

<!-- FEATURED PROJECTS -->
<div align="center" style="margin-bottom:50px">
  <div style="display:inline-flex;align-items:center;gap:12px;color:#60a5fa;font:500 11px 'DM Mono',monospace;letter-spacing:.16em;text-transform:uppercase;margin-bottom:30px">
    <span style="display:inline-flex;align-items:center;justify-content:center;width:28px;height:28px;border:1px solid rgba(96,165,250,.3);border-radius:50%">📂</span>
    Featured Projects
  </div>

  <div style="display:grid;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));gap:20px;max-width:960px;margin:0 auto">

    <!-- Project 1 -->
    <div style="position:relative;overflow:hidden;border-radius:18px;border:1px solid rgba(148,163,184,.14);background:rgba(15,23,42,.34);padding:28px;text-align:left;cursor:default">
      <div style="position:absolute;inset:0;border-radius:18px;padding:1px;background:linear-gradient(135deg,#ef4444,#3b82f6);-webkit-mask:linear-gradient(#000 0 0) content-box,linear-gradient(#000 0 0);-webkit-mask-composite:xor;mask-composite:exclude;pointer-events:none"></div>
      <div style="font-size:.7rem;color:#64748b;font-family:'DM Mono',monospace;text-transform:uppercase;letter-spacing:.09em;margin-bottom:6px">My Website</div>
      <h3 style="margin:8px 0 10px;font-family:'Space Grotesk',sans-serif;font-size:1.3rem;color:white;font-weight:500">Portfolio</h3>
      <p style="margin:0 0 16px;color:#94a3b8;font-size:.78rem;line-height:1.6">Personal portfolio built with React, TypeScript, Vite, Tailwind CSS, Framer Motion, and GSAP.</p>
      <div style="display:flex;gap:8px;flex-wrap:wrap">
        <span style="padding:4px 8px;border:1px solid rgba(148,163,184,.14);border-radius:6px;color:#a8b4c7;font:8px 'DM Mono',monospace">React</span>
        <span style="padding:4px 8px;border:1px solid rgba(148,163,184,.14);border-radius:6px;color:#a8b4c7;font:8px 'DM Mono',monospace">TypeScript</span>
        <span style="padding:4px 8px;border:1px solid rgba(148,163,184,.14);border-radius:6px;color:#a8b4c7;font:8px 'DM Mono',monospace">Tailwind</span>
      </div>
      <div style="margin-top:16px;display:flex;gap:8px">
        <a href="https://github.com/Alanyuye10/portfolio" style="padding:8px 12px;border-radius:8px;border:1px solid rgba(148,163,184,.14);color:#94a3b8;font-size:.72rem;text-decoration:none">🔗 Code</a>
      </div>
    </div>

    <!-- Project 2 -->
    <div style="position:relative;overflow:hidden;border-radius:18px;border:1px solid rgba(148,163,184,.14);background:rgba(15,23,42,.34);padding:28px;text-align:left;cursor:default">
      <div style="position:absolute;inset:0;border-radius:18px;padding:1px;background:linear-gradient(135deg,#ef4444,#3b82f6);-webkit-mask:linear-gradient(#000 0 0) content-box,linear-gradient(#000 0 0);-webkit-mask-composite:xor;mask-composite:exclude;pointer-events:none"></div>
      <div style="font-size:.7rem;color:#64748b;font-family:'DM Mono',monospace;text-transform:uppercase;letter-spacing:.09em;margin-bottom:6px">Wedding</div>
      <h3 style="margin:8px 0 10px;font-family:'Space Grotesk',sans-serif;font-size:1.3rem;color:white;font-weight:500">Wedding Site</h3>
      <p style="margin:0 0 16px;color:#94a3b8;font-size:.78rem;line-height:1.6">Elegant wedding event website with RSVP system and gallery.</p>
      <div style="display:flex;gap:8px;flex-wrap:wrap">
        <span style="padding:4px 8px;border:1px solid rgba(148,163,184,.14);border-radius:6px;color:#a8b4c7;font:8px 'DM Mono',monospace">HTML</span>
        <span style="padding:4px 8px;border:1px solid rgba(148,163,184,.14);border-radius:6px;color:#a8b4c7;font:8px 'DM Mono',monospace">CSS</span>
        <span style="padding:4px 8px;border:1px solid rgba(148,163,184,.14);border-radius:6px;color:#a8b4c7;font:8px 'DM Mono',monospace">JS</span>
      </div>
      <div style="margin-top:16px;display:flex;gap:8px">
        <a href="https://github.com/Alanyuye10/weddingsite" style="padding:8px 12px;border-radius:8px;border:1px solid rgba(148,163,184,.14);color:#94a3b8;font-size:.72rem;text-decoration:none">🔗 Code</a>
      </div>
    </div>

    <!-- Project 3 -->
    <div style="position:relative;overflow:hidden;border-radius:18px;border:1px solid rgba(148,163,184,.14);background:rgba(15,23,42,.34);padding:28px;text-align:left;cursor:default">
      <div style="position:absolute;inset:0;border-radius:18px;padding:1px;background:linear-gradient(135deg,#ef4444,#3b82f6);-webkit-mask:linear-gradient(#000 0 0) content-box,linear-gradient(#000 0 0);-webkit-mask-composite:xor;mask-composite:exclude;pointer-events:none"></div>
      <div style="font-size:.7rem;color:#64748b;font-family:'DM Mono',monospace;text-transform:uppercase;letter-spacing:.09em;margin-bottom:6px">E-Commerce</div>
      <h3 style="margin:8px 0 10px;font-family:'Space Grotesk',sans-serif;font-size:1.3rem;color:white;font-weight:500">Shoe Factory</h3>
      <p style="margin:0 0 16px;color:#94a3b8;font-size:.78rem;line-height:1.6">Shoe store e-commerce platform with product catalog and cart.</p>
      <div style="display:flex;gap:8px;flex-wrap:wrap">
        <span style="padding:4px 8px;border:1px solid rgba(148,163,184,.14);border-radius:6px;color:#a8b4c7;font:8px 'DM Mono',monospace">HTML</span>
        <span style="padding:4px 8px;border:1px solid rgba(148,163,184,.14);border-radius:6px;color:#a8b4c7;font:8px 'DM Mono',monospace">CSS</span>
        <span style="padding:4px 8px;border:1px solid rgba(148,163,184,.14);border-radius:6px;color:#a8b4c7;font:8px 'DM Mono',monospace">JS</span>
      </div>
      <div style="margin-top:16px;display:flex;gap:8px">
        <a href="https://github.com/Alanyuye10/shoefactory" style="padding:8px 12px;border-radius:8px;border:1px solid rgba(148,163,184,.14);color:#94a3b8;font-size:.72rem;text-decoration:none">🔗 Code</a>
      </div>
    </div>

    <!-- Project 4 -->
    <div style="position:relative;overflow:hidden;border-radius:18px;border:1px solid rgba(148,163,184,.14);background:rgba(15,23,42,.34);padding:28px;text-align:left;cursor:default">
      <div style="position:absolute;inset:0;border-radius:18px;padding:1px;background:linear-gradient(135deg,#ef4444,#3b82f6);-webkit-mask:linear-gradient(#000 0 0) content-box,linear-gradient(#000 0 0);-webkit-mask-composite:xor;mask-composite:exclude;pointer-events:none"></div>
      <div style="font-size:.7rem;color:#64748b;font-family:'DM Mono',monospace;text-transform:uppercase;letter-spacing:.09em;margin-bottom:6px">Travel</div>
      <h3 style="margin:8px 0 10px;font-family:'Space Grotesk',sans-serif;font-size:1.3rem;color:white;font-weight:500">Travel Guide</h3>
      <p style="margin:0 0 16px;color:#94a3b8;font-size:.78rem;line-height:1.6">Travel destination guide with itineraries and photo galleries.</p>
      <div style="display:flex;gap:8px;flex-wrap:wrap">
        <span style="padding:4px 8px;border:1px solid rgba(148,163,184,.14);border-radius:6px;color:#a8b4c7;font:8px 'DM Mono',monospace">HTML</span>
        <span style="padding:4px 8px;border:1px solid rgba(148,163,184,.14);border-radius:6px;color:#a8b4c7;font:8px 'DM Mono',monospace">CSS</span>
        <span style="padding:4px 8px;border:1px solid rgba(148,163,184,.14);border-radius:6px;color:#a8b4c7;font:8px 'DM Mono',monospace">JS</span>
      </div>
      <div style="margin-top:16px;display:flex;gap:8px">
        <a href="https://github.com/Alanyuye10/travel-guide" style="padding:8px 12px;border-radius:8px;border:1px solid rgba(148,163,184,.14);color:#94a3b8;font-size:.72rem;text-decoration:none">🔗 Code</a>
      </div>
    </div>

    <!-- Project 5 -->
    <div style="position:relative;overflow:hidden;border-radius:18px;border:1px solid rgba(148,163,184,.14);background:rgba(15,23,42,.34);padding:28px;text-align:left;cursor:default">
      <div style="position:absolute;inset:0;border-radius:18px;padding:1px;background:linear-gradient(135deg,#ef4444,#3b82f6);-webkit-mask:linear-gradient(#000 0 0) content-box,linear-gradient(#000 0 0);-webkit-mask-composite:xor;mask-composite:exclude;pointer-events:none"></div>
      <div style="font-size:.7rem;color:#64748b;font-family:'DM Mono',monospace;text-transform:uppercase;letter-spacing:.09em;margin-bottom:6px">Gaming</div>
      <h3 style="margin:8px 0 10px;font-family:'Space Grotesk',sans-serif;font-size:1.3rem;color:white;font-weight:500">Black Myth</h3>
      <p style="margin:0 0 16px;color:#94a3b8;font-size:.78rem;line-height:1.6">Black Myth Wukong inspired fan site with character lore and media.</p>
      <div style="display:flex;gap:8px;flex-wrap:wrap">
        <span style="padding:4px 8px;border:1px solid rgba(148,163,184,.14);border-radius:6px;color:#a8b4c7;font:8px 'DM Mono',monospace">HTML</span>
        <span style="padding:4px 8px;border:1px solid rgba(148,163,184,.14);border-radius:6px;color:#a8b4c7;font:8px 'DM Mono',monospace">CSS</span>
        <span style="padding:4px 8px;border:1px solid rgba(148,163,184,.14);border-radius:6px;color:#a8b4c7;font:8px 'DM Mono',monospace">JS</span>
      </div>
      <div style="margin-top:16px;display:flex;gap:8px">
        <a href="https://github.com/Alanyuye10/blackmyth" style="padding:8px 12px;border-radius:8px;border:1px solid rgba(148,163,184,.14);color:#94a3b8;font-size:.72rem;text-decoration:none">🔗 Code</a>
      </div>
    </div>

    <!-- Project 6 -->
    <div style="position:relative;overflow:hidden;border-radius:18px;border:1px solid rgba(148,163,184,.14);background:rgba(15,23,42,.34);padding:28px;text-align:left;cursor:default">
      <div style="position:absolute;inset:0;border-radius:18px;padding:1px;background:linear-gradient(135deg,#ef4444,#3b82f6);-webkit-mask:linear-gradient(#000 0 0) content-box,linear-gradient(#000 0 0);-webkit-mask-composite:xor;mask-composite:exclude;pointer-events:none"></div>
      <div style="font-size:.7rem;color:#64748b;font-family:'DM Mono',monospace;text-transform:uppercase;letter-spacing:.09em;margin-bottom:6px">Style</div>
      <h3 style="margin:8px 0 10px;font-family:'Space Grotesk',sans-serif;font-size:1.3rem;color:white;font-weight:500">Fashion</h3>
      <p style="margin:0 0 16px;color:#94a3b8;font-size:.78rem;line-height:1.6">Fashion brand landing page with modern UI and trend showcase.</p>
      <div style="display:flex;gap:8px;flex-wrap:wrap">
        <span style="padding:4px 8px;border:1px solid rgba(148,163,184,.14);border-radius:6px;color:#a8b4c7;font:8px 'DM Mono',monospace">HTML</span>
        <span style="padding:4px 8px;border:1px solid rgba(148,163,184,.14);border-radius:6px;color:#a8b4c7;font:8px 'DM Mono',monospace">CSS</span>
        <span style="padding:4px 8px;border:1px solid rgba(148,163,184,.14);border-radius:6px;color:#a8b4c7;font:8px 'DM Mono',monospace">JS</span>
      </div>
      <div style="margin-top:16px;display:flex;gap:8px">
        <a href="https://github.com/Alanyuye10/fashion" style="padding:8px 12px;border-radius:8px;border:1px solid rgba(148,163,184,.14);color:#94a3b8;font-size:.72rem;text-decoration:none">🔗 Code</a>
      </div>
    </div>
  </div>
</div>

<!-- CONTRIBUTION GRAPH -->
<div align="center" style="margin-bottom:50px">
  <div style="display:inline-flex;align-items:center;gap:12px;color:#60a5fa;font:500 11px 'DM Mono',monospace;letter-spacing:.16em;text-transform:uppercase;margin-bottom:30px">
    <span style="display:inline-flex;align-items:center;justify-content:center;width:28px;height:28px;border:1px solid rgba(96,165,250,.3);border-radius:50%">📈</span>
    Activity Graph
  </div>

  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=Alanyuye10&theme=redical&hide_border=true&area=true&bg_color=0d1117&line=ef4444&point=f87171&color=60a5fa&area_color=ef4444">
    <img src="https://github-readme-activity-graph.vercel.app/graph?username=Alanyuye10&theme=redical&hide_border=true&area=true&bg_color=0d1117&line=ef4444&point=f87171&color=60a5fa&area_color=ef4444" width="95%" alt="Activity Graph">
  </picture>
</div>

<!-- CONNECT SECTION -->
<div align="center" style="margin-bottom:50px;padding:50px 30px;background:#080c1b;border-radius:24px;border:1px solid rgba(148,163,184,.14)">
  <div style="display:inline-flex;align-items:center;gap:12px;color:#60a5fa;font:500 11px 'DM Mono',monospace;letter-spacing:.16em;text-transform:uppercase;margin-bottom:24px">
    <span style="display:inline-flex;align-items:center;justify-content:center;width:28px;height:28px;border:1px solid rgba(96,165,250,.3);border-radius:50%">🔗</span>
    Connect With Me
  </div>

  <p style="color:#94a3b8;font-size:.9rem;margin:0 auto 30px;max-width:500px">
    Got a project in mind? Let's swing into action and build something amazing together.
  </p>

  <div style="display:flex;flex-wrap:wrap;justify-content:center;gap:12px">
    <a href="https://www.linkedin.com/in/alan-yuye/" style="display:inline-flex;align-items:center;gap:8px;padding:12px 22px;border-radius:13px;background:linear-gradient(135deg,#dc2626,#2563eb);box-shadow:0 12px 35px rgba(220,38,38,.2),inset 0 1px 0 rgba(255,255,255,.25);color:white;font-size:.82rem;font-weight:600;text-decoration:none">💼 LinkedIn</a>
    <a href="https://www.instagram.com/alan_yuye/" style="display:inline-flex;align-items:center;gap:8px;padding:12px 22px;border-radius:13px;border:1px solid rgba(148,163,184,.14);background:rgba(255,255,255,.035);color:rgba(255,255,255,.85);font-size:.82rem;font-weight:600;text-decoration:none">📸 Instagram</a>
    <a href="https://wa.me/9567188533" style="display:inline-flex;align-items:center;gap:8px;padding:12px 22px;border-radius:13px;border:1px solid rgba(148,163,184,.14);background:rgba(255,255,255,.035);color:rgba(255,255,255,.85);font-size:.82rem;font-weight:600;text-decoration:none">💬 WhatsApp</a>
    <a href="mailto:alanyuye@example.com" style="display:inline-flex;align-items:center;gap:8px;padding:12px 22px;border-radius:13px;border:1px solid rgba(148,163,184,.14);background:rgba(255,255,255,.035);color:rgba(255,255,255,.85);font-size:.82rem;font-weight:600;text-decoration:none">✉️ Email</a>
  </div>
</div>

<!-- FOOTER -->
<div align="center" style="position:relative;padding:40px 20px 30px;overflow:hidden">

  <!-- Footer spider web SVG -->
  <svg style="position:absolute;bottom:0;left:50%;transform:translateX(-50%);width:200px;height:100px;pointer-events:none" viewBox="0 0 200 100">
    <path d="M100,100 L100,20 M100,20 L140,0 M100,20 L60,0 M100,20 L150,40 M100,20 L50,40 M100,40 L170,60 M100,40 L30,60" stroke="#ef4444" stroke-width=".5" fill="none" opacity=".6"/>
    <path d="M100,50 Q130,40 160,55 M100,50 Q70,40 40,55 M100,65 Q125,55 155,70 M100,65 Q75,55 45,70" stroke="#3b82f6" stroke-width=".4" fill="none" opacity=".4"/>
    <circle cx="100" cy="20" r="3" fill="#f87171" opacity=".5">
      <animate attributeName="opacity" values=".35;.1;.35" dur="2.5s" repeatCount="indefinite"/>
      <animate attributeName="r" values="3;5.4;3" dur="2.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="140" cy="0" r="1.5" fill="#60a5fa" opacity=".4">
      <animate attributeName="opacity" values=".35;.1;.35" dur="2.5s" repeatCount="indefinite" begin=".8s"/>
      <animate attributeName="r" values="1.5;2.7;1.5" dur="2.5s" repeatCount="indefinite" begin=".8s"/>
    </circle>
    <circle cx="60" cy="0" r="1.5" fill="#60a5fa" opacity=".4">
      <animate attributeName="opacity" values=".35;.1;.35" dur="2.5s" repeatCount="indefinite" begin="1.5s"/>
      <animate attributeName="r" values="1.5;2.7;1.5" dur="2.5s" repeatCount="indefinite" begin="1.5s"/>
    </circle>
  </svg>

  <!-- Animated spider emoji (SVG swing) -->
  <svg width="40" height="40" viewBox="-20 -20 40 40" style="margin-bottom:20px">
    <text x="0" y="0" text-anchor="middle" dominant-baseline="central" font-size="32">🕷️</text>
    <animateTransform attributeName="transform" type="rotate" values="-8;8;-8" dur="3s" repeatCount="indefinite"/>
  </svg>

  <p style="color:#94a3b8;font-family:'Space Grotesk',sans-serif;font-size:1.1rem;font-weight:500;letter-spacing:-.02em;margin:0 0 16px;position:relative">
    "With great code comes great responsibility"
  </p>

  <p style="color:#64748b;font-size:.75rem;margin:0;position:relative">
    <span style="color:#f87171">©</span> 2026 <span style="color:#60a5fa">Alanyuye10</span> · Built with 🕸️ from the Spider-Verse
  </p>

  <p style="color:#64748b;font-size:.65rem;margin-top:12px;font-family:'DM Mono',monospace">
    <img src="https://komarev.com/ghpvc/?username=Alanyuye10&color=ef4444&style=flat&label=🕷️+Spidey+Sense+Triggers" alt="Profile Views">
  </p>
</div>
