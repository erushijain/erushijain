
<svg width="1000" height="260" viewBox="0 0 1000 260" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bg" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#0d1117"/>
      <stop offset="100%" stop-color="#161b22"/>
    </linearGradient>
    <radialGradient id="webGlow" cx="0%" cy="0%" r="100%">
      <stop offset="0%" stop-color="#ffffff" stop-opacity="0.25"/>
      <stop offset="100%" stop-color="#ffffff" stop-opacity="0"/>
    </radialGradient>
  </defs>

  <rect width="1000" height="260" rx="18" fill="url(#bg)"/>

  <!-- ===== Corner spider web (left side) ===== -->
  <g stroke="#c9d1d9" stroke-width="1.2" fill="none" opacity="0.55">
    <!-- radial spokes from top-left corner -->
    <line x1="0" y1="0" x2="230" y2="0"/>
    <line x1="0" y1="0" x2="200" y2="70"/>
    <line x1="0" y1="0" x2="150" y2="130"/>
    <line x1="0" y1="0" x2="90" y2="180"/>
    <line x1="0" y1="0" x2="30" y2="215"/>
    <line x1="0" y1="0" x2="0" y2="230"/>
    <!-- concentric web arcs -->
    <path d="M 40,0 Q 55,55 0,60"/>
    <path d="M 90,0 Q 110,110 0,120"/>
    <path d="M 150,0 Q 170,170 0,180"/>
    <path d="M 210,0 Q 220,215 0,225"/>
  </g>
  <circle cx="0" cy="0" r="230" fill="url(#webGlow)"/>

  <!-- small dew-drop accents on the web -->
  <circle cx="55" cy="55" r="2" fill="#58a6ff"/>
  <circle cx="110" cy="108" r="2" fill="#58a6ff"/>
  <circle cx="168" cy="168" r="2" fill="#58a6ff"/>

  <!-- ===== Hero silhouette hanging from a thread, top-right ===== -->
  <line x1="860" y1="0" x2="860" y2="95" stroke="#c9d1d9" stroke-width="1.3" opacity="0.7"/>
  <g transform="translate(838,95)">
    <!-- head/mask -->
    <ellipse cx="22" cy="18" rx="15" ry="17" fill="#e0342a"/>
    <!-- mask eye shapes -->
    <path d="M 12,14 Q 18,8 24,14 Q 19,19 12,14 Z" fill="#ffffff"/>
    <path d="M 22,14 Q 28,8 34,14 Q 29,19 22,14 Z" fill="#ffffff"/>
    <!-- web-line texture on mask -->
    <path d="M22,1 L22,35 M8,10 L36,26 M8,26 L36,10" stroke="#0d1117" stroke-width="0.8" opacity="0.4"/>
    <!-- body -->
    <path d="M10,32 Q22,50 34,32 L34,70 Q22,78 10,70 Z" fill="#1e3a8a"/>
    <!-- arms, one reaching up to the thread -->
    <path d="M22,38 L22,20" stroke="#e0342a" stroke-width="6" stroke-linecap="round"/>
    <path d="M12,45 Q0,55 4,72" stroke="#e0342a" stroke-width="6" fill="none" stroke-linecap="round"/>
    <!-- legs, slightly bent as if mid-swing -->
    <path d="M14,70 Q10,90 18,100" stroke="#1e3a8a" stroke-width="7" fill="none" stroke-linecap="round"/>
    <path d="M30,70 Q38,88 32,100" stroke="#1e3a8a" stroke-width="7" fill="none" stroke-linecap="round"/>
  </g>

  <!-- ===== Cats sitting along the top edge ===== -->
  <g id="cat-style" fill="#ffb454">
    <!-- Cat 1 -->
    <g transform="translate(340,6)">
      <path d="M0,26 Q0,4 14,4 Q28,4 28,26 Z"/>
      <path d="M2,6 L-4,-8 L10,4 Z"/>
      <path d="M26,6 L32,-8 L18,4 Z"/>
      <circle cx="9" cy="16" r="1.6" fill="#0d1117"/>
      <circle cx="19" cy="16" r="1.6" fill="#0d1117"/>
      <path d="M11,20 Q14,22 17,20" stroke="#0d1117" stroke-width="1" fill="none"/>
    </g>
    <!-- Cat 2 -->
    <g transform="translate(470,10)" fill="#8b949e">
      <path d="M0,22 Q0,2 12,2 Q24,2 24,22 Z"/>
      <path d="M1,4 L-4,-7 L9,3 Z"/>
      <path d="M23,4 L28,-7 L15,3 Z"/>
      <circle cx="8" cy="13" r="1.4" fill="#0d1117"/>
      <circle cx="16" cy="13" r="1.4" fill="#0d1117"/>
    </g>
    <!-- Cat 3 -->
    <g transform="translate(600,4)" fill="#f0f6fc">
      <path d="M0,28 Q0,4 15,4 Q30,4 30,28 Z"/>
      <path d="M2,6 L-5,-9 L11,4 Z"/>
      <path d="M28,6 L35,-9 L19,4 Z"/>
      <circle cx="10" cy="17" r="1.7" fill="#0d1117"/>
      <circle cx="20" cy="17" r="1.7" fill="#0d1117"/>
      <path d="M12,21 Q15,23 18,21" stroke="#0d1117" stroke-width="1" fill="none"/>
    </g>
    <!-- Cat 4, small, peeking -->
    <g transform="translate(700,14)" fill="#d29922">
      <path d="M0,18 Q0,2 10,2 Q20,2 20,18 Z"/>
      <path d="M1,3 L-3,-6 L8,2 Z"/>
      <path d="M19,3 L23,-6 L12,2 Z"/>
      <circle cx="6" cy="11" r="1.2" fill="#0d1117"/>
      <circle cx="14" cy="11" r="1.2" fill="#0d1117"/>
    </g>
  </g>

  <!-- ===== Center text ===== -->
  <text x="500" y="140" font-family="Fira Code, monospace" font-size="34" fill="#f0f6fc" text-anchor="middle" font-weight="600">
    Eruuuuuu
  </text>
  <text x="500" y="172" font-family="Fira Code, monospace" font-size="15" fill="#8b949e" text-anchor="middle">
    web-slinging through code, one commit at a time 🕸️🐾
  </text>

  <!-- thin web thread decorations near text -->
  <line x1="380" y1="150" x2="440" y2="150" stroke="#30363d" stroke-width="1"/>
  <line x1="560" y1="150" x2="620" y2="150" stroke="#30363d" stroke-width="1"/>
</svg>
