<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Men of Culture</title>
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,600;1,300;1,400&family=Rajdhani:wght@300;400;500;600;700&family=Space+Mono:ital,wght@0,400;0,700;1,400&display=swap" rel="stylesheet">
<style>
*{margin:0;padding:0;box-sizing:border-box}
:root{
--gold:#C9A84C;--gold2:#E8C97A;--gold3:#8B6914;
--dark:#050508;--dark2:#0A0A10;--dark3:#0F0F18;
--glass:rgba(255,255,255,0.04);--glass2:rgba(201,168,76,0.08);
--text:#F0EDE4;--muted:#8A8470;
}
html{scroll-behavior:smooth;background:var(--dark)}
body{font-family:'Rajdhani',sans-serif;color:var(--text);background:var(--dark);overflow-x:hidden;cursor:none}

/* CURSOR */
#cursor{position:fixed;width:12px;height:12px;background:var(--gold);border-radius:50%;pointer-events:none;z-index:9999;transform:translate(-50%,-50%);transition:transform 0.1s,width 0.3s,height 0.3s,background 0.3s;mix-blend-mode:difference}
#cursor-ring{position:fixed;width:36px;height:36px;border:1px solid var(--gold);border-radius:50%;pointer-events:none;z-index:9998;transform:translate(-50%,-50%);transition:transform 0.15s ease-out,width 0.3s,height 0.3s,opacity 0.3s;opacity:0.5}

/* SCROLLBAR */
::-webkit-scrollbar{width:4px}
::-webkit-scrollbar-track{background:var(--dark2)}
::-webkit-scrollbar-thumb{background:var(--gold3);border-radius:2px}

/* NOISE OVERLAY */
body::before{content:'';position:fixed;inset:0;background-image:url("data:image/svg+xml,%3Csvg viewBox='0 0 200 200' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)' opacity='0.04'/%3E%3C/svg%3E");pointer-events:none;z-index:1;opacity:0.4}

/* HERO */
#hero{min-height:100vh;display:flex;flex-direction:column;align-items:center;justify-content:center;position:relative;overflow:hidden}
#hero-bg{position:absolute;inset:0;background:radial-gradient(ellipse 80% 60% at 50% 40%,rgba(201,168,76,0.06) 0%,transparent 70%)}
.hero-lines{position:absolute;inset:0;pointer-events:none}
.hero-line{position:absolute;background:linear-gradient(90deg,transparent,rgba(201,168,76,0.15),transparent);height:1px;animation:scanline 4s linear infinite}
.hero-line:nth-child(1){top:20%;animation-delay:0s;width:100%}
.hero-line:nth-child(2){top:50%;animation-delay:1.5s;width:100%}
.hero-line:nth-child(3){top:80%;animation-delay:3s;width:100%}
@keyframes scanline{0%{transform:translateX(-100%)}100%{transform:translateX(100%)}}

.hero-tag{font-family:'Space Mono',monospace;font-size:11px;letter-spacing:0.3em;color:var(--gold);text-transform:uppercase;margin-bottom:2rem;opacity:0;animation:fadeUp 1s 0.3s forwards}
.hero-title{font-family:'Cormorant Garamond',serif;font-size:clamp(3.5rem,10vw,8rem);font-weight:300;line-height:0.95;text-align:center;opacity:0;animation:fadeUp 1s 0.6s forwards}
.hero-title em{font-style:italic;color:var(--gold);display:block}
.hero-subtitle{font-family:'Rajdhani',sans-serif;font-size:1.1rem;font-weight:300;letter-spacing:0.15em;color:var(--muted);margin-top:2rem;text-align:center;opacity:0;animation:fadeUp 1s 0.9s forwards}
.hero-year{font-family:'Space Mono',monospace;font-size:0.75rem;color:var(--gold3);letter-spacing:0.2em;margin-top:1rem;opacity:0;animation:fadeUp 1s 1.1s forwards}
.scroll-hint{position:absolute;bottom:3rem;left:50%;transform:translateX(-50%);display:flex;flex-direction:column;align-items:center;gap:0.5rem;opacity:0;animation:fadeUp 1s 1.5s forwards}
.scroll-hint span{font-family:'Space Mono',monospace;font-size:10px;letter-spacing:0.25em;color:var(--muted)}
.scroll-dot{width:1px;height:50px;background:linear-gradient(to bottom,var(--gold),transparent);animation:scrollPulse 2s ease-in-out infinite}
@keyframes scrollPulse{0%,100%{opacity:0.3;transform:scaleY(1)}50%{opacity:1;transform:scaleY(1.2)}}
@keyframes fadeUp{from{opacity:0;transform:translateY(30px)}to{opacity:1;transform:translateY(0)}}

/* SECTION BASE */
section{position:relative;padding:8rem 2rem;z-index:2}
.section-label{font-family:'Space Mono',monospace;font-size:10px;letter-spacing:0.4em;color:var(--gold3);text-transform:uppercase;margin-bottom:0.75rem}
.section-title{font-family:'Cormorant Garamond',serif;font-size:clamp(2.5rem,5vw,4.5rem);font-weight:300;line-height:1.1;margin-bottom:1rem}
.section-title em{font-style:italic;color:var(--gold)}
.section-divider{width:60px;height:1px;background:linear-gradient(to right,var(--gold),transparent);margin:1.5rem 0 3rem}
.container{max-width:1200px;margin:0 auto}

/* FACT TICKER */
#fact-ticker{position:fixed;bottom:0;left:0;right:0;z-index:100;background:rgba(5,5,8,0.95);border-top:1px solid rgba(201,168,76,0.2);padding:0.6rem 1.5rem;display:flex;align-items:center;gap:1.5rem;backdrop-filter:blur(10px)}
.ticker-label{font-family:'Space Mono',monospace;font-size:9px;letter-spacing:0.3em;color:var(--gold);white-space:nowrap;text-transform:uppercase;background:var(--gold3);color:var(--dark);padding:3px 8px;border-radius:2px}
#ticker-text{font-size:0.85rem;color:var(--muted);font-family:'Rajdhani',sans-serif;letter-spacing:0.05em;flex:1;overflow:hidden;white-space:nowrap;font-weight:400}
#ticker-refresh{background:none;border:1px solid rgba(201,168,76,0.3);color:var(--gold3);font-family:'Space Mono',monospace;font-size:9px;padding:3px 8px;cursor:pointer;letter-spacing:0.1em;transition:all 0.3s}
#ticker-refresh:hover{background:var(--gold);color:var(--dark)}

/* TIMELINE */
#timeline-section{background:linear-gradient(180deg,var(--dark) 0%,var(--dark3) 50%,var(--dark) 100%)}
.timeline-grid{display:grid;grid-template-columns:1fr 2px 1fr;gap:0;position:relative}
.timeline-spine{background:linear-gradient(to bottom,transparent,var(--gold),var(--gold3),transparent);position:relative}
.timeline-spine::before{content:'';position:absolute;top:0;left:50%;transform:translateX(-50%);width:1px;height:100%;background:linear-gradient(to bottom,transparent,var(--gold),transparent)}
.t-item{padding:2rem;opacity:0;transform:translateY(20px);transition:all 0.6s ease}
.t-item.visible{opacity:1;transform:translateY(0)}
.t-item-left{text-align:right;padding-right:3rem}
.t-item-right{padding-left:3rem}
.t-dot{position:absolute;width:14px;height:14px;background:var(--dark);border:2px solid var(--gold);border-radius:50%;left:50%;transform:translateX(-50%);margin-top:2.2rem;z-index:2;transition:all 0.3s}
.t-dot::before{content:'';position:absolute;inset:-6px;border:1px solid rgba(201,168,76,0.2);border-radius:50%;animation:pulse 3s ease-in-out infinite}
@keyframes pulse{0%,100%{opacity:0;transform:scale(1)}50%{opacity:1;transform:scale(1.4)}}
.t-year{font-family:'Space Mono',monospace;font-size:10px;letter-spacing:0.3em;color:var(--gold);margin-bottom:0.5rem}
.t-title{font-family:'Cormorant Garamond',serif;font-size:1.8rem;font-weight:400;margin-bottom:0.5rem;line-height:1.2}
.t-desc{font-size:0.9rem;color:var(--muted);line-height:1.7;font-weight:300}
.t-tag{display:inline-block;font-family:'Space Mono',monospace;font-size:9px;letter-spacing:0.2em;color:var(--gold3);border:1px solid rgba(201,168,76,0.2);padding:3px 10px;margin-top:0.75rem;border-radius:2px}

/* EVENTS */
#events-section{background:var(--dark2)}
.events-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(340px,1fr));gap:1.5rem;margin-top:3rem}
.event-card{background:var(--glass);border:1px solid rgba(201,168,76,0.1);padding:2rem;position:relative;overflow:hidden;transition:all 0.4s ease;backdrop-filter:blur(10px)}
.event-card::before{content:'';position:absolute;top:0;left:0;right:0;height:2px;background:linear-gradient(90deg,transparent,var(--gold),transparent);opacity:0;transition:opacity 0.4s}
.event-card:hover{border-color:rgba(201,168,76,0.3);transform:translateY(-4px);background:rgba(201,168,76,0.06)}
.event-card:hover::before{opacity:1}
.event-card.cinematic{background:rgba(0,0,0,0.6);border-color:rgba(201,168,76,0.2)}
.event-card.dramatic{background:rgba(20,0,0,0.6);border-color:rgba(200,50,50,0.2)}
.event-card.dramatic:hover{border-color:rgba(200,50,50,0.5)}
.event-date{font-family:'Space Mono',monospace;font-size:10px;letter-spacing:0.25em;color:var(--gold3);margin-bottom:0.75rem}
.event-title{font-family:'Cormorant Garamond',serif;font-size:1.6rem;font-weight:400;margin-bottom:0.75rem;line-height:1.2}
.event-body{font-size:0.88rem;color:var(--muted);line-height:1.75;font-weight:300}
.event-cat{position:absolute;top:1.25rem;right:1.25rem;font-family:'Space Mono',monospace;font-size:8px;letter-spacing:0.2em;padding:3px 8px;background:rgba(201,168,76,0.1);color:var(--gold3);border-radius:1px;text-transform:uppercase}

/* PERSONAL */
#personal-section{background:var(--dark3);padding:8rem 2rem}
.personal-card{max-width:700px;margin:0 auto;text-align:center;position:relative;padding:4rem 3rem;border:1px solid rgba(201,168,76,0.08)}
.personal-card::before,.personal-card::after{content:'';position:absolute;width:40px;height:40px;border-color:rgba(201,168,76,0.25)}
.personal-card::before{top:0;left:0;border-top:1px solid;border-left:1px solid}
.personal-card::after{bottom:0;right:0;border-bottom:1px solid;border-right:1px solid}
.personal-date{font-family:'Space Mono',monospace;font-size:10px;letter-spacing:0.4em;color:var(--gold3);margin-bottom:1.5rem}
.personal-title{font-family:'Cormorant Garamond',serif;font-size:3.5rem;font-style:italic;font-weight:300;color:var(--gold2);line-height:1}
.personal-subtitle{font-family:'Cormorant Garamond',serif;font-size:1.1rem;font-weight:300;color:var(--muted);margin-top:1rem;font-style:italic}
.personal-body{font-size:0.9rem;color:var(--muted);line-height:1.9;margin-top:2rem;font-weight:300;text-align:left}
.personal-badge{display:inline-block;font-family:'Space Mono',monospace;font-size:9px;letter-spacing:0.3em;color:var(--gold);border:1px solid rgba(201,168,76,0.3);padding:5px 14px;margin-top:2rem;border-radius:1px}

/* HISTORY */
#history-section{background:var(--dark)}
.history-list{margin-top:3rem;border-left:1px solid rgba(201,168,76,0.15);padding-left:2.5rem}
.h-item{position:relative;padding:1.5rem 0 1.5rem 0;border-bottom:1px solid rgba(255,255,255,0.03);opacity:0;transform:translateX(-20px);transition:all 0.5s ease}
.h-item.visible{opacity:1;transform:translateX(0)}
.h-item::before{content:'';position:absolute;left:-2.6rem;top:1.8rem;width:10px;height:10px;background:var(--dark);border:1px solid var(--gold3);border-radius:50%}
.h-item:hover::before{background:var(--gold);border-color:var(--gold)}
.h-date{font-family:'Space Mono',monospace;font-size:10px;letter-spacing:0.3em;color:var(--gold3);margin-bottom:0.5rem}
.h-title{font-family:'Cormorant Garamond',serif;font-size:1.7rem;font-weight:400;margin-bottom:0.4rem}
.h-body{font-size:0.88rem;color:var(--muted);line-height:1.7;font-weight:300;max-width:650px}
.h-tag{display:inline-block;font-family:'Space Mono',monospace;font-size:9px;letter-spacing:0.15em;margin-top:0.75rem;padding:3px 10px;border-radius:2px}
.tag-global{background:rgba(100,60,200,0.15);color:#9B7FDF;border:1px solid rgba(150,100,220,0.2)}
.tag-india{background:rgba(255,165,0,0.1);color:#E8A020;border:1px solid rgba(255,165,0,0.2)}
.tag-tech{background:rgba(0,200,150,0.1);color:#3DB898;border:1px solid rgba(0,200,150,0.2)}
.tag-war{background:rgba(200,50,50,0.1);color:#C84040;border:1px solid rgba(200,50,50,0.2)}
.tag-space{background:rgba(50,130,255,0.1);color:#5090FF;border:1px solid rgba(50,130,255,0.2)}

/* AI PANEL */
#ai-panel{background:var(--dark3);border-top:1px solid rgba(201,168,76,0.1);padding:8rem 2rem}
.ai-box{max-width:800px;margin:0 auto;background:rgba(201,168,76,0.03);border:1px solid rgba(201,168,76,0.12);padding:3rem;position:relative}
.ai-box::before{content:'AI ENGINE';position:absolute;top:-10px;left:2rem;background:var(--dark3);padding:0 10px;font-family:'Space Mono',monospace;font-size:9px;letter-spacing:0.3em;color:var(--gold3)}
.ai-input-row{display:flex;gap:0;margin-top:2rem}
#ai-input{flex:1;background:rgba(0,0,0,0.4);border:1px solid rgba(201,168,76,0.2);border-right:none;color:var(--text);padding:0.9rem 1.2rem;font-family:'Rajdhani',sans-serif;font-size:1rem;outline:none;letter-spacing:0.05em;transition:border-color 0.3s}
#ai-input:focus{border-color:rgba(201,168,76,0.5)}
#ai-input::placeholder{color:rgba(138,132,112,0.5)}
#ai-btn{background:var(--gold3);color:var(--dark);border:none;padding:0.9rem 1.5rem;font-family:'Rajdhani',sans-serif;font-size:0.9rem;font-weight:700;letter-spacing:0.2em;cursor:pointer;transition:all 0.3s;white-space:nowrap;text-transform:uppercase}
#ai-btn:hover{background:var(--gold);transform:none}
#ai-output{margin-top:2rem;min-height:100px;padding:1.5rem;background:rgba(0,0,0,0.3);border:1px solid rgba(201,168,76,0.08);border-radius:0;font-size:0.9rem;color:var(--text);line-height:1.8;font-weight:300;display:none;position:relative}
#ai-output.visible{display:block}
.ai-cursor{display:inline-block;width:2px;height:1em;background:var(--gold);animation:blink 0.8s steps(1) infinite;vertical-align:middle;margin-left:2px}
@keyframes blink{0%,100%{opacity:1}50%{opacity:0}}
.ai-tag-pills{display:flex;flex-wrap:wrap;gap:0.5rem;margin-top:1rem}
.ai-pill{font-family:'Space Mono',monospace;font-size:9px;letter-spacing:0.15em;padding:4px 12px;border:1px solid rgba(201,168,76,0.2);color:var(--gold3);cursor:pointer;transition:all 0.2s;border-radius:1px}
.ai-pill:hover{background:var(--gold3);color:var(--dark)}

/* ADMIN */
#admin-panel{display:none;position:fixed;inset:0;z-index:1000;background:rgba(0,0,0,0.9);backdrop-filter:blur(20px);justify-content:center;align-items:center}
#admin-panel.open{display:flex}
.admin-box{background:var(--dark2);border:1px solid rgba(201,168,76,0.2);padding:2.5rem;width:90%;max-width:600px;max-height:85vh;overflow-y:auto}
.admin-title{font-family:'Cormorant Garamond',serif;font-size:2rem;color:var(--gold);margin-bottom:0.25rem}
.admin-sub{font-family:'Space Mono',monospace;font-size:9px;letter-spacing:0.3em;color:var(--muted);margin-bottom:2rem}
.admin-field{margin-bottom:1rem}
.admin-field label{display:block;font-family:'Space Mono',monospace;font-size:9px;letter-spacing:0.2em;color:var(--gold3);margin-bottom:0.4rem;text-transform:uppercase}
.admin-field input,.admin-field select,.admin-field textarea{width:100%;background:rgba(0,0,0,0.5);border:1px solid rgba(201,168,76,0.15);color:var(--text);padding:0.75rem 1rem;font-family:'Rajdhani',sans-serif;font-size:0.95rem;outline:none;transition:border-color 0.3s;resize:vertical}
.admin-field input:focus,.admin-field select,.admin-field textarea:focus{border-color:rgba(201,168,76,0.4)}
.admin-field select option{background:var(--dark2);color:var(--text)}
.admin-btn-row{display:flex;gap:0.75rem;margin-top:1.5rem}
.btn-primary{background:var(--gold3);color:var(--dark);border:none;padding:0.75rem 1.5rem;font-family:'Rajdhani',sans-serif;font-size:0.9rem;font-weight:700;letter-spacing:0.2em;cursor:pointer;text-transform:uppercase;transition:all 0.3s;flex:1}
.btn-primary:hover{background:var(--gold)}
.btn-ghost{background:none;color:var(--muted);border:1px solid rgba(201,168,76,0.15);padding:0.75rem 1.5rem;font-family:'Rajdhani',sans-serif;font-size:0.9rem;letter-spacing:0.2em;cursor:pointer;text-transform:uppercase;transition:all 0.3s}
.btn-ghost:hover{border-color:rgba(201,168,76,0.4);color:var(--text)}
.admin-lock{text-align:center;padding:3rem 0}
.admin-lock-icon{font-size:3rem;margin-bottom:1rem;opacity:0.3}
.lock-input{width:100%;background:rgba(0,0,0,0.5);border:1px solid rgba(201,168,76,0.2);color:var(--text);padding:1rem;font-family:'Space Mono',monospace;font-size:1.2rem;letter-spacing:0.5em;text-align:center;outline:none;margin-top:1rem}
.lock-btn{width:100%;margin-top:0.75rem;background:rgba(201,168,76,0.1);color:var(--gold);border:1px solid rgba(201,168,76,0.3);padding:0.75rem;font-family:'Rajdhani',sans-serif;font-size:0.9rem;letter-spacing:0.2em;cursor:pointer;text-transform:uppercase;transition:all 0.3s}
.lock-btn:hover{background:var(--gold3);color:var(--dark)}
.admin-toggle{position:fixed;bottom:4rem;right:1.5rem;z-index:200;background:rgba(5,5,8,0.95);border:1px solid rgba(201,168,76,0.2);width:44px;height:44px;display:flex;align-items:center;justify-content:center;cursor:pointer;font-size:1.2rem;transition:all 0.3s;backdrop-filter:blur(10px)}
.admin-toggle:hover{border-color:var(--gold);background:var(--glass2)}
.dynamic-events-area{margin-top:2rem}
.dyn-event-card{background:rgba(201,168,76,0.03);border:1px solid rgba(201,168,76,0.12);padding:1.5rem;margin-bottom:1rem;position:relative;overflow:hidden}
.dyn-event-card::before{content:'';position:absolute;left:0;top:0;bottom:0;width:3px;background:linear-gradient(to bottom,var(--gold),var(--gold3))}
.dyn-event-cat{font-family:'Space Mono',monospace;font-size:8px;letter-spacing:0.3em;color:var(--gold3);text-transform:uppercase;margin-bottom:0.4rem}
.dyn-event-title{font-family:'Cormorant Garamond',serif;font-size:1.3rem;margin-bottom:0.3rem}
.dyn-event-body{font-size:0.85rem;color:var(--muted);line-height:1.7;font-weight:300}

/* NAV */
nav{position:fixed;top:0;left:0;right:0;z-index:500;padding:1.5rem 3rem;display:flex;justify-content:space-between;align-items:center;background:linear-gradient(to bottom,rgba(5,5,8,0.9),transparent);backdrop-filter:blur(2px)}
.nav-logo{font-family:'Cormorant Garamond',serif;font-size:1.4rem;font-weight:300;letter-spacing:0.1em;color:var(--gold2)}
.nav-logo span{font-style:italic}
.nav-links{display:flex;gap:2rem;list-style:none}
.nav-links a{font-family:'Space Mono',monospace;font-size:10px;letter-spacing:0.25em;color:var(--muted);text-decoration:none;text-transform:uppercase;transition:color 0.3s}
.nav-links a:hover{color:var(--gold)}
.nav-dot{display:inline-block;width:4px;height:4px;background:var(--gold3);border-radius:50%;vertical-align:middle;margin:0 0.75rem}

/* FOOTER */
footer{background:var(--dark);border-top:1px solid rgba(201,168,76,0.08);padding:3rem 2rem 6rem;text-align:center}
.footer-title{font-family:'Cormorant Garamond',serif;font-size:1.5rem;font-style:italic;color:var(--gold3);margin-bottom:0.5rem}
.footer-sub{font-family:'Space Mono',monospace;font-size:9px;letter-spacing:0.3em;color:var(--muted);text-transform:uppercase}

/* COUNTER */
.stat-row{display:flex;gap:3rem;margin:3rem 0;flex-wrap:wrap}
.stat{text-align:center}
.stat-num{font-family:'Cormorant Garamond',serif;font-size:3rem;font-weight:300;color:var(--gold)}
.stat-label{font-family:'Space Mono',monospace;font-size:9px;letter-spacing:0.25em;color:var(--muted);text-transform:uppercase}

/* LOADING */
#loader{position:fixed;inset:0;z-index:9000;background:var(--dark);display:flex;flex-direction:column;align-items:center;justify-content:center;transition:opacity 0.8s,visibility 0.8s}
#loader.done{opacity:0;visibility:hidden}
.loader-title{font-family:'Cormorant Garamond',serif;font-size:2.5rem;font-style:italic;color:var(--gold);margin-bottom:1.5rem;letter-spacing:0.05em}
.loader-bar-wrap{width:200px;height:1px;background:rgba(201,168,76,0.1)}
.loader-bar{height:100%;width:0;background:linear-gradient(to right,var(--gold3),var(--gold));transition:width 0.1s linear}
.loader-pct{font-family:'Space Mono',monospace;font-size:10px;color:var(--gold3);margin-top:0.75rem;letter-spacing:0.3em}
</style>
</head>
<body>

<div id="loader">
  <div class="loader-title">Men of Culture</div>
  <div class="loader-bar-wrap"><div class="loader-bar" id="loader-bar"></div></div>
  <div class="loader-pct" id="loader-pct">0%</div>
</div>

<div id="cursor"></div>
<div id="cursor-ring"></div>

<nav>
  <div class="nav-logo">Men <span>of</span> Culture</div>
  <ul class="nav-links">
    <li><a href="#timeline-section">Revolutions</a></li>
    <li><a href="#events-section">Events</a></li>
    <li><a href="#history-section">History</a></li>
    <li><a href="#ai-panel">AI Engine</a></li>
  </ul>
</nav>

<!-- HERO -->
<div id="hero">
  <div id="hero-bg"></div>
  <div class="hero-lines">
    <div class="hero-line"></div>
    <div class="hero-line"></div>
    <div class="hero-line"></div>
  </div>
  <div style="position:relative;z-index:2;text-align:center;padding:0 2rem">
    <div class="hero-tag">A Cinematic Cultural Archive · 2015 – 2026</div>
    <h1 class="hero-title">Men<br><em>of Culture</em></h1>
    <p class="hero-subtitle">Revolutions &nbsp;·&nbsp; Events &nbsp;·&nbsp; Milestones &nbsp;·&nbsp; History</p>
    <p class="hero-year">WHERE MEMORY BECOMES MONUMENT</p>
  </div>
  <div class="scroll-hint">
    <span>SCROLL</span>
    <div class="scroll-dot"></div>
  </div>
</div>

<!-- STATS -->
<section style="background:var(--dark2);padding:4rem 2rem;border-top:1px solid rgba(201,168,76,0.08);border-bottom:1px solid rgba(201,168,76,0.08)">
  <div class="container">
    <div class="stat-row" style="justify-content:center">
      <div class="stat"><div class="stat-num" data-count="11">0</div><div class="stat-label">Years Covered</div></div>
      <div class="stat"><div class="stat-num" data-count="18">0</div><div class="stat-label">Major Events</div></div>
      <div class="stat"><div class="stat-num" data-count="4">0</div><div class="stat-label">Revolutions</div></div>
      <div class="stat"><div class="stat-num" data-count="1400000000">0</div><div class="stat-label">Lives Impacted</div></div>
    </div>
  </div>
</section>

<!-- TIMELINE -->
<section id="timeline-section">
  <div class="container">
    <div class="section-label">Chapter I</div>
    <h2 class="section-title">Revolutions We <em>Witnessed</em></h2>
    <div class="section-divider"></div>
    <div class="timeline-grid" id="timeline-grid">

      <!-- LEFT: Mobile Evolution -->
      <div class="t-item t-item-left" style="grid-row:1">
        <div class="t-year">2015 – 2022</div>
        <div class="t-title">Mobile Evolution</div>
        <div class="t-desc">From feature phones to AI-powered supercomputers in your pocket. India saw 500M+ smartphone users by 2021. The screen became the new reality.</div>
        <span class="t-tag">REVOLUTION · TECH</span>
      </div>
      <div style="grid-row:1;position:relative" class="timeline-spine">
        <div class="t-dot"></div>
      </div>
      <div style="grid-row:1" class="t-item t-item-right">
        <div class="t-year">PARALLEL EVENT</div>
        <div class="t-title">Television's Last Stand</div>
        <div class="t-desc">As screens multiplied, the living room TV fought back — smart TVs, 4K, OLED. But the audience was already looking elsewhere.</div>
        <span class="t-tag">CULTURE · MEDIA</span>
      </div>

      <div class="t-item t-item-left" style="grid-row:2">
        <div class="t-year">2016 – 2019</div>
        <div class="t-title">OTT Revolution</div>
        <div class="t-desc">Netflix, Amazon Prime, Hotstar — the binge era began. India became the world's fastest-growing OTT market. Content was no longer prime time; it was any time.</div>
        <span class="t-tag">ENTERTAINMENT · OTT</span>
      </div>
      <div style="grid-row:2;position:relative" class="timeline-spine">
        <div class="t-dot"></div>
      </div>
      <div style="grid-row:2" class="t-item t-item-right">
        <div class="t-year">2016 → PRESENT</div>
        <div class="t-title">Network: 3G → 6G</div>
        <div class="t-desc">Reliance Jio ignited the 4G era in 2016. 5G arrived by 2022. 6G looms on the horizon — latency approaching zero, connectivity becoming invisible.</div>
        <span class="t-tag">TELECOM · FUTURE</span>
      </div>

    </div>
  </div>
</section>

<!-- MAJOR EVENTS -->
<section id="events-section">
  <div class="container">
    <div class="section-label">Chapter II</div>
    <h2 class="section-title">Major Events That <em>Shaped Us</em></h2>
    <div class="section-divider"></div>
    <div class="events-grid">

      <div class="event-card cinematic">
        <div class="event-cat">Pandemic</div>
        <div class="event-date">25 MARCH 2020</div>
        <div class="event-title">COVID-19 Lockdown India</div>
        <div class="event-body">PM Modi announced a 21-day nationwide lockdown at 8 PM with 4 hours notice. 1.38 billion people stood still. The streets fell silent. Families were trapped inside history. India would never be the same.</div>
      </div>

      <div class="event-card cinematic">
        <div class="event-cat">Telecom</div>
        <div class="event-date">SEPTEMBER 2016</div>
        <div class="event-title">Rise of Reliance Jio</div>
        <div class="event-body">Free data. Free calls. A single company collapsed the price of connectivity. 100 million users in 170 days — the fastest adoption in telecom history. The internet wasn't a luxury anymore. It was air.</div>
      </div>

      <div class="event-card cinematic">
        <div class="event-cat">Fintech</div>
        <div class="event-date">2016 – PRESENT</div>
        <div class="event-title">UPI Digital Revolution</div>
        <div class="event-body">India built a payments system the world would study. ₹1 transactions to ₹1 lakh transfers — instant, free, universal. From chai stalls to luxury stores, a QR code replaced cash. India processes billions of transactions monthly.</div>
      </div>

      <div class="event-card dramatic">
        <div class="event-cat" style="color:#C84040;border-color:rgba(200,50,50,0.3)">Shock Policy</div>
        <div class="event-date">8 NOVEMBER 2016</div>
        <div class="event-title">Demonetization</div>
        <div class="event-body">At 8 PM, ₹500 and ₹1000 notes — 86% of India's cash — were declared illegal tender overnight. Queues stretched for miles. Lives upended. The most audacious monetary experiment in democratic history.</div>
      </div>

      <div class="event-card cinematic">
        <div class="event-cat">Youth Culture</div>
        <div class="event-date">2018 – 2020</div>
        <div class="event-title">TikTok & PUBG Craze</div>
        <div class="event-body">200 million TikTok users. 175 million PUBG Mobile players. India was the world's largest audience for both. Then June 2020 — India banned 59 Chinese apps. A generation's digital identity, erased in a government order.</div>
      </div>

      <div class="event-card cinematic">
        <div class="event-cat" style="color:#9B7FDF;border-color:rgba(150,100,220,0.25)">Spiritual</div>
        <div class="event-date">2025 · ONCE IN 144 YEARS</div>
        <div class="event-title">Mahakumbh Mela</div>
        <div class="event-body">The largest human gathering in recorded history. Prayagraj hosted the Purna Kumbh — a celestial convergence that occurs only every 144 years. 400 million pilgrims. A river of faith that made the satellite images look surreal.</div>
      </div>

    </div>

    <!-- Dynamic events added by admin will appear here -->
    <div class="dynamic-events-area" id="dynamic-events-area"></div>
  </div>
</section>

<!-- PERSONAL -->
<section id="personal-section">
  <div class="container">
    <div class="section-label" style="text-align:center">Chapter III · Personal</div>
    <div class="personal-card">
      <div class="personal-date">26 JANUARY 2023 · REPUBLIC DAY</div>
      <div class="personal-title">Muka No Kand</div>
      <div class="personal-subtitle">The Day That Became Legend</div>
      <div class="personal-body">
        Some moments don't announce themselves. They simply arrive, and afterwards, everything is measured against them — before and after. On the 74th Republic Day of India, while the nation watched the parade on Kartavya Path, a different kind of march was happening elsewhere. The kind that only a handful of people would remember, and those people would remember nothing else from that year. Muka no kand. It doesn't translate. It doesn't need to. Those who were there understand the specific gravity of this particular Tuesday — the chai that went cold, the phone calls that didn't come, the things that were said standing somewhere ordinary that made it permanently extraordinary.
      </div>
      <div class="personal-badge">PERSONAL ARCHIVE · CLASSIFIED</div>
    </div>
  </div>
</section>

<!-- HISTORY -->
<section id="history-section">
  <div class="container">
    <div class="section-label">Chapter IV</div>
    <h2 class="section-title">Modern History's <em>Turning Points</em></h2>
    <div class="section-divider"></div>
    <div class="history-list">

      <div class="h-item">
        <div class="h-date">END OF 2022</div>
        <div class="h-title">The AI Boom Begins</div>
        <div class="h-body">ChatGPT launched November 30, 2022. 100 million users in 2 months. The fastest product adoption in history. Artificial intelligence stopped being a research topic and became a civilizational force. The world split into before-AI and after-AI.</div>
        <span class="h-tag tag-tech">TECHNOLOGY · GLOBAL</span>
      </div>

      <div class="h-item">
        <div class="h-date">23 AUGUST 2023 · 18:04 IST</div>
        <div class="h-title">Chandrayaan-3 · India on the Moon</div>
        <div class="h-body">Vikram lander touched the lunar south pole. India became the first nation to do so, and only the 4th country to land on the Moon. ISRO had done it at a fraction of NASA's budget. August 23 is now India's National Space Day. The nation erupted.</div>
        <span class="h-tag tag-space">SPACE · INDIA</span>
      </div>

      <div class="h-item">
        <div class="h-date">9–10 SEPTEMBER 2023</div>
        <div class="h-title">India Hosts G20 Summit</div>
        <div class="h-body">New Delhi hosted 43 heads of state. India secured the African Union's inclusion in the G20 — a historic diplomatic win. The world watched India from Bharat Mandapam. The presidency ended with 83 outcomes adopted by consensus — a record.</div>
        <span class="h-tag tag-india">INDIA · DIPLOMACY</span>
      </div>

      <div class="h-item">
        <div class="h-date">22 JANUARY 2024</div>
        <div class="h-title">Ayodhya Ram Mandir Inauguration</div>
        <div class="h-body">PM Modi performed the 'Prana Pratishtha' ceremony of Ram Lalla. A 500-year wait, a Supreme Court verdict, and a 1200-crore temple — all converging in one moment. 550 million people watched live. Ayodhya was renamed; history was rewritten in stone and gold.</div>
        <span class="h-tag tag-india">CULTURE · INDIA</span>
      </div>

      <div class="h-item">
        <div class="h-date">7 MAY 2025</div>
        <div class="h-title">India–Pakistan: Operation Sindoor & Blackout</div>
        <div class="h-body">Following the Pahalgam terror attack, India launched cross-border precision strikes under Operation Sindoor. Cities across northern India conducted civil defence drills — sirens, blackouts, shelter protocols. The subcontinent held its breath. Diplomacy and deterrence danced on a knife's edge.</div>
        <span class="h-tag tag-war">CONFLICT · INDIA</span>
      </div>

      <div class="h-item">
        <div class="h-date">MARCH 2026</div>
        <div class="h-title">Israel–Iran War Begins</div>
        <div class="h-body">Following months of escalation, direct military confrontation between Israel and Iran began in March 2026 — fundamentally reshaping Middle East geopolitics. Oil markets convulsed. Regional alliances fractured. The world watched a new axis of conflict emerge in real time.</div>
        <span class="h-tag tag-war">GLOBAL · CONFLICT</span>
      </div>

    </div>
  </div>
</section>

<!-- AI ENGINE -->
<section id="ai-panel">
  <div class="container">
    <div class="section-label">AI Engine</div>
    <h2 class="section-title">Ask the <em>Archive</em></h2>
    <div class="section-divider"></div>
    <p style="color:var(--muted);font-size:0.9rem;max-width:600px;font-weight:300;line-height:1.8;margin-bottom:2rem">Powered by Claude. Ask about any event, revolution, or cultural moment. Generate new event cards. Explore connections across time.</p>
    <div class="ai-box">
      <div style="margin-bottom:1.5rem">
        <div class="section-label" style="margin-bottom:0.5rem">Quick Prompts</div>
        <div class="ai-tag-pills">
          <button class="ai-pill" onclick="setPrompt('How did Jio change India in 3 sentences?')">Jio Impact</button>
          <button class="ai-pill" onclick="setPrompt('Describe the emotion of Chandrayaan-3 landing')">Chandrayaan-3</button>
          <button class="ai-pill" onclick="setPrompt('What was life like during India COVID lockdown?')">COVID Lockdown</button>
          <button class="ai-pill" onclick="setPrompt('Explain UPI revolution as if to a foreigner')">UPI Explained</button>
          <button class="ai-pill" onclick="setPrompt('Write a cinematic one-paragraph description of the AI Boom of 2022')">AI Boom</button>
          <button class="ai-pill" onclick="setPrompt('Give me a surprising fact about Mahakumbh Mela 2025')">Mahakumbh Fact</button>
        </div>
      </div>
      <div class="ai-input-row">
        <input id="ai-input" type="text" placeholder="Ask the archive anything..." maxlength="300">
        <button id="ai-btn" onclick="askAI()">ASK →</button>
      </div>
      <div id="ai-output"></div>
    </div>
  </div>
</section>

<!-- FOOTER -->
<footer>
  <div class="footer-title">Men of Culture</div>
  <div class="footer-sub">A Living Archive · 2015 – 2026 · Built with Memory</div>
  <div style="margin-top:2rem;font-family:'Space Mono',monospace;font-size:9px;letter-spacing:0.2em;color:rgba(138,132,112,0.3)">EVERY MOMENT MATTERED</div>
</footer>

<!-- FACT TICKER -->
<div id="fact-ticker">
  <span class="ticker-label">DID YOU KNOW</span>
  <span id="ticker-text">Loading cultural facts...</span>
  <button id="ticker-refresh" onclick="nextFact()">→ NEXT</button>
</div>

<!-- ADMIN TOGGLE -->
<button class="admin-toggle" onclick="openAdmin()" title="Admin Panel">⚙</button>

<!-- ADMIN PANEL -->
<div id="admin-panel">
  <div class="admin-box">
    <div id="admin-lock-screen">
      <div class="admin-title">Admin Access</div>
      <div class="admin-sub">AUTHORIZED PERSONNEL ONLY</div>
      <div class="admin-lock">
        <div class="admin-lock-icon">🔐</div>
        <div style="font-family:'Space Mono',monospace;font-size:10px;letter-spacing:0.2em;color:var(--muted)">ENTER PASSKEY</div>
        <input class="lock-input" type="password" id="admin-pass" placeholder="· · · · · ·" maxlength="20">
        <button class="lock-btn" onclick="checkPass()">AUTHENTICATE</button>
        <div id="lock-error" style="font-family:'Space Mono',monospace;font-size:9px;color:#C84040;margin-top:0.75rem;letter-spacing:0.15em;display:none">ACCESS DENIED</div>
      </div>
    </div>
    <div id="admin-main" style="display:none">
      <div class="admin-title">Add New Event</div>
      <div class="admin-sub">AI-POWERED AUTO-FORMAT</div>
      <div class="admin-field">
        <label>Event Topic / Raw Description</label>
        <textarea id="adm-raw" rows="3" placeholder="Describe the event in your own words..."></textarea>
      </div>
      <div class="admin-field">
        <label>Category</label>
        <select id="adm-cat">
          <option value="Revolution">Revolution</option>
          <option value="Event">Major Event</option>
          <option value="Global">Global</option>
          <option value="Personal">Personal</option>
        </select>
      </div>
      <div class="admin-field">
        <label>Date / Year</label>
        <input id="adm-date" type="text" placeholder="e.g. 15 August 2024">
      </div>
      <div class="admin-btn-row">
        <button class="btn-primary" onclick="adminGenerate()">✦ AI FORMAT &amp; ADD</button>
        <button class="btn-ghost" onclick="closeAdmin()">CLOSE</button>
      </div>
      <div id="adm-status" style="font-family:'Space Mono',monospace;font-size:9px;letter-spacing:0.15em;color:var(--gold3);margin-top:1rem;display:none"></div>
    </div>
  </div>
</div>

<script>
// CURSOR
const cur=document.getElementById('cursor'),curR=document.getElementById('cursor-ring');
let mx=0,my=0,rx=0,ry=0;
document.addEventListener('mousemove',e=>{mx=e.clientX;my=e.clientY;cur.style.left=mx+'px';cur.style.top=my+'px'});
setInterval(()=>{rx+=(mx-rx)*0.12;ry+=(my-ry)*0.12;curR.style.left=rx+'px';curR.style.top=ry+'px'},16);
document.querySelectorAll('a,button,input,textarea,select,.event-card,.t-item').forEach(el=>{
  el.addEventListener('mouseenter',()=>{cur.style.width='20px';cur.style.height='20px';curR.style.width='60px';curR.style.height='60px';curR.style.opacity='0.2'});
  el.addEventListener('mouseleave',()=>{cur.style.width='12px';cur.style.height='12px';curR.style.width='36px';curR.style.height='36px';curR.style.opacity='0.5'});
});

// LOADER
let pct=0;const bar=document.getElementById('loader-bar'),pctEl=document.getElementById('loader-pct');
const iv=setInterval(()=>{pct+=Math.random()*8+2;if(pct>=100){pct=100;clearInterval(iv);setTimeout(()=>{document.getElementById('loader').classList.add('done')},400)}
bar.style.width=pct+'%';pctEl.textContent=Math.floor(pct)+'%'},80);

// FACTS
const facts=[
  "India processes over 14 billion UPI transactions per month as of 2024.",
  "Reliance Jio signed up 100 million users faster than any telecom in history.",
  "Chandrayaan-3 cost ₹615 crore — less than many Hollywood movies.",
  "During COVID lockdown, Doordarshan re-aired Ramayan and got 77 million viewers — a world record.",
  "India banned 59 Chinese apps in June 2020, affecting 200 million TikTok users overnight.",
  "The Mahakumbh 2025 had more attendees than the entire population of the United States.",
  "Demonetization removed 86% of India's currency in circulation overnight.",
  "India's G20 presidency resulted in the most summit outcomes in the group's history.",
  "PUBG Mobile had 175 million Indian players before its 2020 ban.",
  "ChatGPT reached 100 million users in 2 months — faster than Instagram took 2.5 years.",
  "The Ram Mandir in Ayodhya used 17,000+ stone blocks carved by artisans over 5 years.",
  "India's 5G rollout reached 100 cities in just 6 months — one of the fastest globally.",
];
let factIdx=0;
function nextFact(){factIdx=(factIdx+1)%facts.length;const el=document.getElementById('ticker-text');el.style.opacity='0';setTimeout(()=>{el.textContent=facts[factIdx];el.style.opacity='1'},300)}
document.getElementById('ticker-text').style.transition='opacity 0.3s';
document.getElementById('ticker-text').textContent=facts[0];
setInterval(nextFact,6000);

// INTERSECTION OBSERVER
const obs=new IntersectionObserver(entries=>{entries.forEach(e=>{if(e.isIntersecting)e.target.classList.add('visible')})},{threshold:0.15});
document.querySelectorAll('.t-item,.h-item').forEach(el=>obs.observe(el));

// COUNTER ANIMATION
const cObs=new IntersectionObserver(entries=>{entries.forEach(e=>{if(e.isIntersecting&&!e.target.dataset.done){
  e.target.dataset.done=1;const target=+e.target.dataset.count;const dur=1500;const start=Date.now();
  const tick=()=>{const p=Math.min((Date.now()-start)/dur,1);const val=Math.floor(p*target);
    if(target>=1000000){e.target.textContent=(val/1000000).toFixed(0)+'B+'}else{e.target.textContent=val}
    if(p<1)requestAnimationFrame(tick)};tick()}})},{threshold:0.5});
document.querySelectorAll('[data-count]').forEach(el=>cObs.observe(el));

// PARALLAX
window.addEventListener('scroll',()=>{const s=window.scrollY;document.getElementById('hero-bg').style.transform=`translateY(${s*0.3}px)`});

// AI
async function askAI(){
  const input=document.getElementById('ai-input');const btn=document.getElementById('ai-btn');
  const q=input.value.trim();if(!q)return;
  const out=document.getElementById('ai-output');
  out.innerHTML='<span class="ai-cursor"></span>';out.classList.add('visible');
  btn.textContent='...';btn.disabled=true;
  const sysprompt=`You are the AI archivist for "Men of Culture" — a luxury cinematic cultural archive website focusing on India and global events from 2015–2026. You write in an evocative, literary style — cinematic, poetic but informative. Keep responses to 2-4 sentences max. Be vivid, not generic. Respond as if narrating a documentary.`;
  try{
    const r=await fetch('https://api.anthropic.com/v1/messages',{method:'POST',headers:{'Content-Type':'application/json'},body:JSON.stringify({model:'claude-sonnet-4-20250514',max_tokens:1000,system:sysprompt,messages:[{role:'user',content:q}]})});
    const d=await r.json();const text=d.content?.[0]?.text||'Archive is silent on this matter.';
    out.innerHTML='';let i=0;
    const typeIt=()=>{if(i<text.length){out.innerHTML=text.slice(0,++i)+'<span class="ai-cursor"></span>';setTimeout(typeIt,18)}else{out.innerHTML=text}};typeIt();
  }catch(e){out.innerHTML='The archive encountered turbulence. Please try again.'}
  btn.textContent='ASK →';btn.disabled=false;
}
function setPrompt(t){document.getElementById('ai-input').value=t;document.getElementById('ai-input').focus()}
document.getElementById('ai-input').addEventListener('keydown',e=>{if(e.key==='Enter')askAI()});

// ADMIN
const PASS='culture2026';
function openAdmin(){document.getElementById('admin-panel').classList.add('open');document.getElementById('admin-pass').value='';document.getElementById('lock-error').style.display='none'}
function closeAdmin(){document.getElementById('admin-panel').classList.remove('open');document.getElementById('admin-main').style.display='none';document.getElementById('admin-lock-screen').style.display='block'}
function checkPass(){const p=document.getElementById('admin-pass').value;if(p===PASS){document.getElementById('admin-lock-screen').style.display='none';document.getElementById('admin-main').style.display='block'}else{document.getElementById('lock-error').style.display='block'}}
document.getElementById('admin-pass').addEventListener('keydown',e=>{if(e.key==='Enter')checkPass()});

async function adminGenerate(){
  const raw=document.getElementById('adm-raw').value.trim();
  const cat=document.getElementById('adm-cat').value;
  const date=document.getElementById('adm-date').value.trim();
  if(!raw){alert('Please enter an event description');return}
  const st=document.getElementById('adm-status');st.style.display='block';st.textContent='⟳ AI IS FORMATTING...';
  const sys=`You are an AI formatter for a luxury cultural archive website called "Men of Culture". Format the user's raw event description into a JSON object with these fields: title (punchy, 3-6 words), description (2-3 sentences, cinematic tone, 60 words max). Return ONLY valid JSON with those two fields, no markdown.`;
  try{
    const r=await fetch('https://api.anthropic.com/v1/messages',{method:'POST',headers:{'Content-Type':'application/json'},body:JSON.stringify({model:'claude-sonnet-4-20250514',max_tokens:1000,system:sys,messages:[{role:'user',content:`Raw event: ${raw}\nDate: ${date||'Unknown'}\nCategory: ${cat}`}]})});
    const d=await r.json();let text=(d.content?.[0]?.text||'{}').replace(/```json|```/g,'').trim();
    const parsed=JSON.parse(text);
    addDynamicEvent({title:parsed.title||raw.slice(0,30),body:parsed.description||raw,cat,date:date||'RECENT'});
    st.textContent='✓ EVENT ADDED TO ARCHIVE';
    setTimeout(()=>{document.getElementById('adm-raw').value='';document.getElementById('adm-date').value='';st.textContent=''},3000);
  }catch(e){st.textContent='⚠ AI ERROR — please try again'}
}

function addDynamicEvent({title,body,cat,date}){
  const area=document.getElementById('dynamic-events-area');
  const card=document.createElement('div');card.className='dyn-event-card';
  card.innerHTML=`<div class="dyn-event-cat">${cat}</div><div class="dyn-event-title">${title}</div><div style="font-family:'Space Mono',monospace;font-size:9px;letter-spacing:0.2em;color:var(--gold3);margin-bottom:0.5rem">${date}</div><div class="dyn-event-body">${body}</div>`;
  card.style.opacity='0';card.style.transform='translateY(20px)';card.style.transition='all 0.5s ease';
  area.appendChild(card);
  setTimeout(()=>{card.style.opacity='1';card.style.transform='translateY(0)'},50);
}

// Close admin on outside click
document.getElementById('admin-panel').addEventListener('click',e=>{if(e.target===document.getElementById('admin-panel'))closeAdmin()});
</script>
</body>
</html>
