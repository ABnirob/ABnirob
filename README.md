 
<svg viewBox="0 0 1200 360" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="none">

  <defs>

    <!-- 🌌 NIGHT SKY GRADIENT -->
    <linearGradient id="sky" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" stop-color="#01010f"/>
      <stop offset="40%" stop-color="#061a3a"/>
      <stop offset="100%" stop-color="#0f2a3a"/>
    </linearGradient>

    <!-- 🌊 DEEP OCEAN -->
    <linearGradient id="ocean" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#081826"/>
      <stop offset="100%" stop-color="#123a5a"/>
    </linearGradient>

    <!-- 🌙 MOON GLOW -->
    <radialGradient id="moonGlow">
      <stop offset="0%" stop-color="white" stop-opacity="1"/>
      <stop offset="100%" stop-color="white" stop-opacity="0"/>
    </radialGradient>

    <!-- ✨ STAR GLOW -->
    <filter id="glow">
      <feGaussianBlur stdDeviation="1.2"/>
    </filter>

    <!-- 🌫️ DEPTH BLUR -->
    <filter id="soft">
      <feGaussianBlur stdDeviation="6"/>
    </filter>

    <!-- ✨ LIGHT SHINE -->
    <linearGradient id="shine" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="white" stop-opacity="0"/>
      <stop offset="50%" stop-color="white" stop-opacity="0.15"/>
      <stop offset="100%" stop-color="white" stop-opacity="0"/>
    </linearGradient>

  </defs>

  <!-- 🌌 SKY -->
  <rect width="100%" height="100%" fill="url(#sky)"/>

  <!-- ⭐ STARS (animated twinkle) -->
  <g fill="white" filter="url(#glow)">
    <circle cx="120" cy="60" r="1.2">
      <animate attributeName="opacity" values="0.2;1;0.2" dur="3s" repeatCount="indefinite"/>
    </circle>
    <circle cx="300" cy="90" r="1.5">
      <animate attributeName="opacity" values="0.1;1;0.1" dur="4s" repeatCount="indefinite"/>
    </circle>
    <circle cx="520" cy="40" r="1.3">
      <animate attributeName="opacity" values="0.3;1;0.3" dur="5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="780" cy="70" r="1.4">
      <animate attributeName="opacity" values="0.2;1;0.2" dur="3.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="1000" cy="50" r="1.2">
      <animate attributeName="opacity" values="0.2;1;0.2" dur="4.5s" repeatCount="indefinite"/>
    </circle>
  </g>

  <!-- 🌙 CRESCENT MOON -->
  <g>
    <circle cx="950" cy="80" r="34" fill="white"/>
    <circle cx="962" cy="75" r="34" fill="#01010f"/>
    <circle cx="950" cy="80" r="60" fill="url(#moonGlow)" opacity="0.25"/>
  </g>

  <!-- 🌊 OCEAN BASE -->
  <rect y="170" width="100%" height="200" fill="url(#ocean)"/>

  <!-- 🌊 WAVE LAYER 1 -->
  <path d="M0,220 C300,280 900,140 1200,200 L1200,360 L0,360 Z"
        fill="white" opacity="0.06">
    <animate attributeName="d" dur="10s" repeatCount="indefinite"
      values="
      M0,220 C300,280 900,140 1200,200 L1200,360 L0,360 Z;
      M0,240 C350,260 850,180 1200,220 L1200,360 L0,360 Z;
      M0,220 C300,280 900,140 1200,200 L1200,360 L0,360 Z"/>
  </path>

  <!-- 🌊 WAVE LAYER 2 -->
  <path d="M0,250 C400,320 800,180 1200,240 L1200,360 L0,360 Z"
        fill="white" opacity="0.12" filter="url(#soft)">
    <animate attributeName="d" dur="12s" repeatCount="indefinite"
      values="
      M0,250 C400,320 800,180 1200,240 L1200,360 L0,360 Z;
      M0,270 C350,300 850,200 1200,260 L1200,360 L0,360 Z;
      M0,250 C400,320 800,180 1200,240 L1200,360 L0,360 Z"/>
  </path>

  <!-- 🌊 WAVE LAYER 3 -->
  <path d="M0,280 C300,340 900,220 1200,270 L1200,360 L0,360 Z"
        fill="white" opacity="0.18"/>

  <!-- ✨ SHINE -->
  <rect x="-1200" y="170" width="1200" height="200" fill="url(#shine)">
    <animate attributeName="x" from="-1200" to="1200" dur="7s" repeatCount="indefinite"/>
  </rect>

  <!-- 🔥 TYPOGRAPHY (CINEMATIC CENTER TEXT) -->
  <text x="50%" y="120" text-anchor="middle"
        fill="white"
        font-size="34"
        font-family="Fira Code, monospace">

    <!-- fake typing effect -->
    <tspan opacity="0">M<animate attributeName="opacity" to="1" begin="0s" dur="0.1s" fill="freeze"/></tspan>
    <tspan opacity="0">d<animate attributeName="opacity" to="1" begin="0.1s" dur="0.1s" fill="freeze"/></tspan>
    <tspan opacity="0">.</tspan>
    <tspan> Abul Bashar Nirob</tspan>

  </text>

  <text x="50%" y="155" text-anchor="middle"
        fill="#00D4FF"
        font-size="16"
        font-family="Fira Code, monospace">
    Data & Business Analyst | Future Data Engineer | AI Explorer
  </text>

</svg>

