<svg width="1280" height="420" viewBox="0 0 1280 420" fill="none" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bg" x1="0" y1="0" x2="1280" y2="420" gradientUnits="userSpaceOnUse">
      <stop stop-color="#0E0F11"/>
      <stop offset="1" stop-color="#171A1F"/>
    </linearGradient>

    <linearGradient id="softText" x1="0" y1="0" x2="1" y2="1">
      <stop stop-color="#F5F1E9"/>
      <stop offset="1" stop-color="#DDD6C9"/>
    </linearGradient>

    <filter id="glow" x="-20%" y="-20%" width="140%" height="140%">
      <feGaussianBlur stdDeviation="2.5" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <!-- background -->
  <rect width="1280" height="420" rx="26" fill="url(#bg)"/>

  <!-- subtle doodles -->
  <g opacity="0.08" stroke="#FFFFFF" stroke-linecap="round">
    <path d="M40 48C84 20 120 20 164 40" stroke-width="5"/>
    <path d="M90 342C138 320 180 320 228 340" stroke-width="5"/>
    <path d="M1062 56C1110 30 1154 30 1202 52" stroke-width="5"/>
    <path d="M1018 344C1074 316 1132 316 1190 344" stroke-width="5"/>
  </g>

  <!-- left little icons -->
  <g stroke="#ECE6DA" stroke-width="2.2" stroke-linecap="round" opacity="0.72">
    <path d="M92 112L102 102L112 112L102 122L92 112Z"/>
    <path d="M150 150C166 138 184 138 200 150"/>
    <path d="M174 138V162"/>
    <path d="M210 102L218 94L226 102L218 110L210 102Z"/>
  </g>

  <!-- right little icons -->
  <g stroke="#ECE6DA" stroke-width="2.2" stroke-linecap="round" opacity="0.72">
    <path d="M1094 116L1104 106L1114 116L1104 126L1094 116Z"/>
    <path d="M1040 154C1056 142 1074 142 1090 154"/>
    <path d="M1064 142V166"/>
    <path d="M1140 104L1148 96L1156 104L1148 112L1140 104Z"/>
  </g>

  <!-- spider thread -->
  <line x1="640" y1="0" x2="640" y2="96" stroke="#F0EADF" stroke-width="2.3" stroke-dasharray="5 7" opacity="0.95"/>

  <!-- big hanging spider -->
  <g filter="url(#glow)">
    <g transform="translate(640 118)">
      <animateTransform attributeName="transform" type="translate"
        values="640 118;640 126;640 118;640 122;640 118"
        dur="4s" repeatCount="indefinite"/>

      <!-- legs -->
      <g stroke="#F1ECE1" stroke-width="3.2" stroke-linecap="round">
        <path d="M-16 4C-42 -14 -62 -14 -82 4"/>
        <path d="M16 4C42 -14 62 -14 82 4"/>

        <path d="M-18 24C-46 18 -66 32 -82 48"/>
        <path d="M18 24C46 18 66 32 82 48"/>

        <path d="M-14 44C-34 56 -48 72 -60 92"/>
        <path d="M14 44C34 56 48 72 60 92"/>

        <path d="M-6 58C-14 76 -22 90 -28 108"/>
        <path d="M6 58C14 76 22 90 28 108"/>
      </g>

      <!-- head -->
      <circle cx="0" cy="8" r="16" fill="#F1ECE1"/>

      <!-- body -->
      <ellipse cx="0" cy="50" rx="30" ry="38" fill="#F1ECE1"/>

      <!-- eyes -->
      <circle cx="-6" cy="5" r="2.4" fill="#171A1F"/>
      <circle cx="6" cy="5" r="2.4" fill="#171A1F"/>
    </g>
  </g>

  <!-- centered intro -->
  <text x="640" y="236"
        text-anchor="middle"
        fill="url(#softText)"
        font-family="'Segoe UI', Arial, sans-serif"
        font-size="28"
        font-weight="600">
    Hi, I'm
  </text>

  <text x="640" y="284"
        text-anchor="middle"
        fill="url(#softText)"
        font-family="'Segoe Script', 'Trebuchet MS', cursive"
        font-size="58"
        font-weight="700">
    Sayyad Adeel
  </text>

  <text x="640" y="320"
        text-anchor="middle"
        fill="#E9E3D7"
        font-family="'Segoe UI', Arial, sans-serif"
        font-size="19"
        opacity="0.95">
    Jack of all trades • master of none • still learning the art of everything
  </text>

  <text x="640" y="350"
        text-anchor="middle"
        fill="#CFC7BB"
        font-family="'Segoe UI', Arial, sans-serif"
        font-size="16"
        opacity="0.92">
    Curious mind • AI-assisted experiments • student from Pakistan
  </text>

  <!-- left side card -->
  <g>
    <rect x="70" y="210" width="250" height="126" rx="18" fill="#111419" stroke="#2A2E35"/>
    <text x="94" y="242" fill="#F1ECE1" font-family="'Segoe UI', Arial, sans-serif" font-size="18" font-weight="700">
      about me
    </text>
    <text x="94" y="272" fill="#D8D0C4" font-family="'Segoe UI', Arial, sans-serif" font-size="15">
      • curious about many things
    </text>
    <text x="94" y="296" fill="#D8D0C4" font-family="'Segoe UI', Arial, sans-serif" font-size="15">
      • learning by building
    </text>
    <text x="94" y="320" fill="#D8D0C4" font-family="'Segoe UI', Arial, sans-serif" font-size="15">
      • usually exploring new ideas
    </text>
  </g>

  <!-- right side card -->
  <g>
    <rect x="960" y="210" width="250" height="126" rx="18" fill="#111419" stroke="#2A2E35"/>
    <text x="984" y="242" fill="#F1ECE1" font-family="'Segoe UI', Arial, sans-serif" font-size="18" font-weight="700">
      exploring
    </text>
    <text x="984" y="272" fill="#D8D0C4" font-family="'Segoe UI', Arial, sans-serif" font-size="15">
      • AI agents
    </text>
    <text x="984" y="296" fill="#D8D0C4" font-family="'Segoe UI', Arial, sans-serif" font-size="15">
      • prototypes
    </text>
    <text x="984" y="320" fill="#D8D0C4" font-family="'Segoe UI', Arial, sans-serif" font-size="15">
      • product ideas
    </text>
  </g>
</svg>
