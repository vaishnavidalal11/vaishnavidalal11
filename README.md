<svg width="460" height="60" viewBox="0 0 460 60" xmlns="http://www.w3.org/2000/svg" font-family="'Fira Code', 'Courier New', monospace">
  <style>
    .line { font-size: 18px; fill: #38BDF8; }
    .cursor { fill: #38BDF8; }
  </style>

  <!-- ================= ICON SLOT (left, 0-60 x 0-60) ================= -->
  <!-- Phase 0 icon: AI / neural node -->
  <g opacity="0">
    <animate attributeName="opacity" dur="12s" repeatCount="indefinite" begin="0s"
      keyTimes="0;0.025;0.225;0.25;1" values="0;1;1;0;0" />
    <circle cx="30" cy="30" r="22" fill="none" stroke="#38BDF8" stroke-width="2"/>
    <circle cx="30" cy="18" r="3.5" fill="#38BDF8"/>
    <circle cx="20" cy="38" r="3.5" fill="#38BDF8"/>
    <circle cx="40" cy="38" r="3.5" fill="#38BDF8"/>
    <line x1="30" y1="18" x2="20" y2="38" stroke="#38BDF8" stroke-width="1.5"/>
    <line x1="30" y1="18" x2="40" y2="38" stroke="#38BDF8" stroke-width="1.5"/>
    <line x1="20" y1="38" x2="40" y2="38" stroke="#38BDF8" stroke-width="1.5"/>
  </g>

  <!-- Phase 1 icon: Agent / robot head -->
  <g opacity="0">
    <animate attributeName="opacity" dur="12s" repeatCount="indefinite" begin="0s"
      keyTimes="0;0.25;0.275;0.475;0.5;1" values="0;0;1;1;0;0" />
    <rect x="12" y="14" width="36" height="28" rx="6" fill="none" stroke="#38BDF8" stroke-width="2"/>
    <circle cx="22" cy="28" r="3" fill="#38BDF8"/>
    <circle cx="38" cy="28" r="3" fill="#38BDF8"/>
    <line x1="30" y1="14" x2="30" y2="6" stroke="#38BDF8" stroke-width="2"/>
    <circle cx="30" cy="4" r="2.5" fill="#38BDF8"/>
    <line x1="18" y1="42" x2="18" y2="48" stroke="#38BDF8" stroke-width="2"/>
    <line x1="42" y1="42" x2="42" y2="48" stroke="#38BDF8" stroke-width="2"/>
  </g>

  <!-- Phase 2 icon: Stack / layers (FastAPI-Next-Docker) -->
  <g opacity="0">
    <animate attributeName="opacity" dur="12s" repeatCount="indefinite" begin="0s"
      keyTimes="0;0.5;0.525;0.725;0.75;1" values="0;0;1;1;0;0" />
    <rect x="10" y="14" width="40" height="9" rx="2" fill="#38BDF8" opacity="0.9"/>
    <rect x="10" y="26" width="40" height="9" rx="2" fill="#38BDF8" opacity="0.6"/>
    <rect x="10" y="38" width="40" height="9" rx="2" fill="#38BDF8" opacity="0.35"/>
  </g>

  <!-- Phase 3 icon: Code brackets -->
  <g opacity="0">
    <animate attributeName="opacity" dur="12s" repeatCount="indefinite" begin="0s"
      keyTimes="0;0.75;0.775;0.975;1" values="0;0;1;1;0" />
    <text x="30" y="38" text-anchor="middle" font-size="26" font-weight="bold" fill="#38BDF8">&lt;/&gt;</text>
  </g>

  <!-- ================= TEXT SLOT (right, starts x=70) ================= -->
  <g>
    <text class="line" x="70" y="36" opacity="0">
      Building AI-powered applications
      <animate attributeName="opacity" dur="12s" repeatCount="indefinite" begin="0s"
        keyTimes="0;0.025;0.225;0.25;1" values="0;1;1;0;0" />
    </text>

    <text class="line" x="70" y="36" opacity="0">
      LLMs | RAG | AI Agents
      <animate attributeName="opacity" dur="12s" repeatCount="indefinite" begin="0s"
        keyTimes="0;0.25;0.275;0.475;0.5;1" values="0;0;1;1;0;0" />
    </text>

    <text class="line" x="70" y="36" opacity="0">
      FastAPI | Next.js | Docker
      <animate attributeName="opacity" dur="12s" repeatCount="indefinite" begin="0s"
        keyTimes="0;0.5;0.525;0.725;0.75;1" values="0;0;1;1;0;0" />
    </text>

    <text class="line" x="70" y="36" opacity="0">
      Software Engineer | AI Engineer
      <animate attributeName="opacity" dur="12s" repeatCount="indefinite" begin="0s"
        keyTimes="0;0.75;0.775;0.975;1" values="0;0;1;1;0" />
    </text>
  </g>

  <!-- Blinking cursor, roughly trailing the text -->
  <rect class="cursor" x="418" y="20" width="9" height="20">
    <animate attributeName="opacity" values="1;0;1" dur="1s" repeatCount="indefinite"/>
  </rect>
</svg>
