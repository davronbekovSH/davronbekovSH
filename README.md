<div align="center">

<img src="./banner.svg" alt="Shahzodbek Davronbekov" width="100%">

</div>

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 260" width="900" height="260" role="img" aria-label="Shahzodbek Davronbekov">
  <title>Shahzodbek Davronbekov</title>
  <defs>
    <linearGradient id="bg" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0" stop-color="#1B1440"/>
      <stop offset="1" stop-color="#0F2A4A"/>
    </linearGradient>
    <clipPath id="cn"><rect class="rn" x="60" y="90" width="0" height="80"/></clipPath>
  </defs>

  <style>
    .name { font: 700 54px 'Segoe UI','Helvetica Neue',Arial,sans-serif; fill: #FFFFFF; }
    .rn { animation: type 3s steps(22) .6s forwards; }
    .cur { fill: #FFC857; animation: move 3s steps(22) .6s forwards, blink 1s step-end 3.6s infinite; }
    .star { fill: #CFE6FF; animation: twinkle 4s ease-in-out infinite; }
    .link { stroke: #8EC5FF; stroke-width: 1.2; fill: none; stroke-dasharray: 140; animation: draw 7s ease-in-out infinite alternate; opacity: .7; }
    .node { fill: #8EC5FF; animation: twinkle 3s ease-in-out infinite; }

    @keyframes type { from { width: 0; } to { width: 640px; } }
    @keyframes move { from { transform: translateX(0); } to { transform: translateX(640px); } }
    @keyframes blink { 0%,50% { opacity: 1; } 50.01%,100% { opacity: 0; } }
    @keyframes twinkle { 0%,100% { opacity: .25; } 50% { opacity: 1; } }
    @keyframes draw { from { stroke-dashoffset: 140; } to { stroke-dashoffset: 0; } }

    @media (prefers-reduced-motion: reduce) {
      * { animation: none !important; }
      .rn { width: 640px; }
      .cur { display: none; }
    }
  </style>

  <rect width="900" height="260" rx="14" fill="url(#bg)"/>

  <!-- stars -->
  <g>
    <circle class="star" cx="48" cy="34" r="1.6" style="animation-delay:-0.4s"/>
    <circle class="star" cx="150" cy="226" r="1.2" style="animation-delay:-1.5s"/>
    <circle class="star" cx="262" cy="42" r="1.4" style="animation-delay:-2.6s"/>
    <circle class="star" cx="388" cy="222" r="1.8" style="animation-delay:-0.9s"/>
    <circle class="star" cx="470" cy="60" r="1.2" style="animation-delay:-3.2s"/>
    <circle class="star" cx="552" cy="236" r="1.5" style="animation-delay:-2.1s"/>
    <circle class="star" cx="604" cy="28" r="1.3" style="animation-delay:-1.1s"/>
    <circle class="star" cx="870" cy="236" r="1.6" style="animation-delay:-3.6s"/>
    <circle class="star" cx="876" cy="30" r="1.2" style="animation-delay:-0.2s"/>
  </g>

  <!-- constellation -->
  <g>
    <polyline class="link" points="700,40 770,80 840,45"/>
    <polyline class="link" points="770,80 740,200 820,190 860,130 840,45" style="animation-delay:-2s"/>
    <circle class="node" cx="700" cy="40" r="4"/>
    <circle class="node" cx="770" cy="80" r="5" style="animation-delay:-1s"/>
    <circle class="node" cx="840" cy="45" r="4" style="animation-delay:-2s"/>
    <circle class="node" cx="740" cy="200" r="3.5" style="animation-delay:-0.5s"/>
    <circle class="node" cx="820" cy="190" r="4.5" style="animation-delay:-1.7s"/>
    <circle class="node" cx="860" cy="130" r="3.5" style="animation-delay:-2.4s"/>
  </g>

  <!-- name -->
  <g clip-path="url(#cn)">
    <text class="name" x="60" y="145" textLength="640" lengthAdjust="spacing">Shahzodbek Davronbekov</text>
  </g>
  <rect class="cur" x="62" y="100" width="4" height="56"/>
</svg>
