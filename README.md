<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>DEFI GIRL | Web3 Growth Partner</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
  <style>
    body {
      background:
        linear-gradient(135deg, rgba(139,92,246,0.12) 0%, rgba(45,212,191,0.09) 100%),
        url('https://img.sanishtech.com/u/f3156a6956ca1a6f177b443486cc2bb2.jpg') center center/cover no-repeat fixed;
      position: relative;
      overflow-x: hidden;
    }
    .floating-cat, .floating-coin {
      position: absolute;
      z-index: 0;
      pointer-events: none;
      animation: float 14s linear infinite;
      opacity: 0.28;
    }
    .floating-cat.cat1 { top: 12%; left: 11%; animation-delay: 0s; animation-duration: 10s;}
    .floating-cat.cat2 { top: 76%; left: 69%; animation-delay: 2s; animation-duration: 13s;}
    .floating-cat.cat3 { top: 53%; left: 81%; animation-delay: 4s; animation-duration: 12s;}
    .floating-cat.cat4 { top: 9%; left: 84%; animation-delay: 4s; animation-duration: 14s;}
    .floating-cat.cat5 { top: 24%; left: 36%; animation-delay: 3s; animation-duration: 17s;}
    .floating-coin { top: 54%; left: 29%; animation: spinFloat 6s linear infinite; opacity: 0.19; }
    @keyframes float {
      0%   {transform: translateY(0px) scale(1);}
      50%  {transform: translateY(-60px) scale(1.07);}
      100% {transform: translateY(0px) scale(1);}
    }
    @keyframes spinFloat {
      0%   {transform: translate(-50%,-50%) scale(1) rotate(0deg);}
      50%  {transform: translate(-50%,-58%) scale(1.11) rotate(180deg);}
      100% {transform: translate(-50%,-50%) scale(1) rotate(360deg);}
    }
    .bio-card {
      max-width: 680px;
      min-height: 740px;
      background: rgba(255,255,255,0.93);
      box-shadow: 0 12px 32px 0 rgba(55,48,163,0.12), 0px 0px 0px 1px rgba(139,92,246,0.08);
    }
    .bio-content {
      font-size: 1.04rem;
      line-height: 1.85;
      letter-spacing: 0.01em;
    }
    @media (max-width: 800px) {
      .bio-card { max-width: 96vw !important; min-height: 90vw !important; }
    }
    @media (max-width: 500px) {
      .bio-card { padding: 1.2rem !important; }
      .bio-content { font-size: 0.95rem; }
      .profile-pic { width: 96px !important; height: 96px !important; }
    }
  </style>
</head>
<body class="min-h-screen flex flex-col items-center justify-center px-4 relative">

  <!-- Animated floating elements -->
  <img src="https://raw.githubusercontent.com/edent/SuperTinyIcons/master/images/svg/cat.svg" alt="" class="floating-cat cat1" width="64" height="64">
  <img src="https://raw.githubusercontent.com/edent/SuperTinyIcons/master/images/svg/cat.svg" alt="" class="floating-cat cat2" width="56" height="56">
  <img src="https://raw.githubusercontent.com/edent/SuperTinyIcons/master/images/svg/cat.svg" alt="" class="floating-cat cat3" width="44" height="44">
  <img src="https://raw.githubusercontent.com/edent/SuperTinyIcons/master/images/svg/cat.svg" alt="" class="floating-cat cat4" width="40" height="40">
  <img src="https://raw.githubusercontent.com/edent/SuperTinyIcons/master/images/svg/cat.svg" alt="" class="floating-cat cat5" width="52" height="52">
  <img src="https://pngimg.com/uploads/bitcoin/bitcoin_PNG47.png" alt="floating coin" class="floating-coin" width="80" height="80">

  <main class="bio-card rounded-3xl p-14 flex flex-col items-center w-full relative z-10">
    <img src="https://image2url.com/images/1764914656340-1514fcde-b3d5-474d-9560-3dd0b6e5369c.jpeg"
      alt="DEFI GIRL Profile"
      class="profile-pic w-36 h-36 rounded-full object-cover border-4 border-indigo-400 shadow mb-6" />

    <h1 class="text-4xl font-extrabold text-zinc-900 tracking-tight mb-2 text-center">DEFI GIRL</h1>
    <h2 class="text-lg text-indigo-600 uppercase font-semibold tracking-wider text-center mb-4">Web3 Growth Partner</h2>
    
    <section class="bio-content text-zinc-700 mb-10 w-full text-left">
      <p class="mb-3">I help Web3 projects grow with clear strategy, strong community building, and smart visibility. My work is focused on real, sustainable project strength—not just hype with no results.</p>
      <p class="mb-6">My tailored growth plans support:</p>
      <ul class="list-disc pl-6 mb-6">
        <li>Community expansion</li>
        <li>Holder confidence</li>
        <li>Token awareness and adoption</li>
        <li>Investor reach (organic audiences)</li>
        <li>Brand presence across major platforms</li>
      </ul>
      <p class="mb-3">I work with active, real communities across Telegram, Reddit, X, and other platforms to help projects stay visible, energetic, and engaged. My goal is simple: help teams build momentum, attract genuine supporters, and keep communities thriving.</p>
      <p class="mb-3">I guide projects through listings on popular crypto discovery platforms to boost visibility and trust, using data-driven strategy inspired by successful memecoins and launch patterns.</p>
      <p class="mb-4">I believe the strongest Web3 projects blend community, creativity, communication, and smart execution.</p>
      <p>If you want a partner who understands the culture and pace of crypto and Web3, I’m here to support your growth and help bring your vision to life — with clarity, energy, and trusted expertise.</p>
    </section>

    <div class="flex items-center justify-center space-x-6 mb-4">
      <a href="https://x.com/defi_girl2" target="_blank" rel="noopener noreferrer" aria-label="X (Twitter)"
         class="hover:scale-110 transition duration-200">
        <!-- X SVG -->
        <svg viewBox="0 0 24 24" class="w-7 h-7 text-blue-400" fill="currentColor">
          <path d="M19.633 7.997c.013.176.013.353.013.531 0 5.384-4.095 11.594-11.594 11.594-.002 0-.002 0-.004 0a11.505 11.505 0 0 1-6.188-1.775c.376.044.76.066 1.152.066a8.201 8.201 0 0 0 5.061-1.75A4.102 4.102 0 0 1 2.78 13.71c.213.04.428.06.65.06.314 0 .615-.04.903-.12a4.093 4.093 0 0 1-3.286-4.02v-.051c.55.305 1.177.491 1.846.513A4.09 4.09 0 0 1 1.09 5.577c0-.748.2-1.454.553-2.059a11.635 11.635 0 0 0 8.601 4.363c-.07-.298-.106-.605-.106-.922A4.093 4.093 0 0 1 13.662 2c1.18 0 2.246.498 2.996 1.296a8.193 8.193 0 0 0 2.604-.998 4.09 4.09 0 0 1-1.798 2.262 8.23 8.23 0 0 0 2.356-.647 8.24 8.24 0 0 1-2.048 2.084z"/>
        </svg>
      </a>
      <a href="https://t.me/EX_Reg1" target="_blank" rel="noopener noreferrer" aria-label="Telegram User"
         class="hover:scale-110 transition duration-200">
        <svg viewBox="0 0 24 24" class="w-7 h-7 text-blue-500" fill="currentColor">
          <path d="M9.99 15.81l-.39 3.3c.56 0 .8-.24 1.08-.53l2.6-2.47 5.41 3.95c1 .56 1.72.27 1.97-.93L23.95 5.6c.33-1.33-.48-1.85-1.34-1.58l-21.47 8.27c-1.31.48-1.29 1.18-.22 1.48l5.49 1.72 12.76-8.07c.6-.39 1.15-.18.7.25z"/>
        </svg>
      </a>
      <a href="https://t.me/defi_channelgirl" target="_blank" rel="noopener noreferrer" aria-label="Telegram Channel"
         class="hover:scale-110 transition duration-200">
        <svg viewBox="0 0 24 24" class="w-7 h-7 text-teal-500" fill="currentColor">
          <path d="M9.99 15.81l-.39 3.3c.56 0 .8-.24 1.08-.53l2.6-2.47 5.41 3.95c1 .56 1.72.27 1.97-.93L23.95 5.6c.33-1.33-.48-1.85-1.34-1.58l-21.47 8.27c-1.31.48-1.29 1.18-.22 1.48l5.49 1.72 12.76-8.07c.6-.39 1.15-.18.7.25z"/>
        </svg>
      </a>
      <a href="YOUR_DISCORD_LINK_HERE" target="_blank" rel="noopener noreferrer" aria-label="Discord"
         class="hover:scale-110 transition duration-200">
        <svg viewBox="0 0 24 24" class="w-7 h-7 text-indigo-600" fill="currentColor">
          <path d="M20.317 4.368a19.791 19.791 0 0 0-4.885-1.515.074.074 0 0 0-.079.037c-.211.383-.447.883-.614 1.276a17.941 17.941 0 0 0-5.367 0c-.167-.393-.406-.893-.617-1.276a.077.077 0 0 0-.079-.037A19.736 19.736 0 0 0 3.684 4.369a.069.069 0 0 0-.031.027c-3.093 4.604-3.934 9.107-3.499 13.565a.081.081 0 0 0 .031.057c2.082 1.519 4.096 2.425 6.072 3.061a.077.077 0 0 0 .084-.027c.469-.646.893-1.326 1.264-2.029a.073.073 0 0 0-.041-.1c-.659-.251-1.285-.547-1.887-.88a.076.076 0 0 1-.008-.127c.126-.094.252-.19.373-.287a.069.069 0 0 1 .07-.013c3.927 1.792 8.18 1.792 12.061 0a.07.07 0 0 1 .073.009c.122.097.247.193.373.287a.077.077 0 0 1-.007.127c-.603.334-1.229.629-1.888.88a.073.073 0 0 0-.04.101c.374.702.798 1.382 1.266 2.028a.076.076 0 0 0 .084.028c1.977-.636 3.991-1.542 6.072-3.061a.075.075 0 0 0 .031-.057c.5-5.005-.838-9.466-3.501-13.566a.08.08 0 0 0-.031-.025ZM8.02 15.331c-1.018 0-1.85-.928-1.85-2.07 0-1.143.819-2.073 1.85-2.073 1.04 0 1.87.93 1.85 2.073 0 1.142-.81 2.07-1.85 2.07Zm7.978 0c-1.018 0-1.85-.928-1.85-2.07 0-1.143.818-2.073 1.85-2.073 1.039 0 1.87.93 1.85 2.073 0 1.142-.81 2.07-1.85 2.07Z"/>
        </svg>
      </a>
    </div>
    <div class="w-full flex justify-center">
      <span class="text-xs text-zinc-400">made with ❤️ by DEFI GIRL</span>
    </div>
  </main>
</body>
</html>
