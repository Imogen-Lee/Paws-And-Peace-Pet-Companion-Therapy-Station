<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover">
<title>Paws & Peace · Pet Companion Therapy Station</title>
<meta name="description" content="Paws & Peace -- A vintage-inspired pet companion therapy station. Healing modern loneliness through professional, warm and personalized pet companionship.">
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,500;0,700;0,800;1,500&family=Special+Elite&family=Cormorant+Garamond:ital,wght@0,500;0,600;0,700;1,500&family=Noto+Serif+SC:wght@400;500;600;700&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://unpkg.com/leaflet@1.9.4/dist/leaflet.css" />
<script src="https://unpkg.com/leaflet@1.9.4/dist/leaflet.js"></script>
<style>
/* 字体引入与定义 */
@import url('https://fonts.googleapis.com/css2?family=Libre+Baskerville:ital,wght@0,400;0,700;1,400;1,700&display=swap');
@font-face {
  font-family: 'Felix Titling';
  src: local('Felix Titling'), local('FelixTitling'), local('Felix Titling MT');
  font-weight: normal;
  font-style: normal;
}
@font-face {
  font-family: 'I.Ming';
  src: local('I.Ming'), local('IMFangSong'), local('华文仿宋'), local('STFangsong');
  font-weight: normal;
  font-style: normal;
}
@font-face {
  font-family: 'I.Ming';
  src: local('I.Ming Bold'), local('IMing');
  font-weight: bold;
  font-style: normal;
}

:root{
--amber:#C27F3A;
--amber-soft:#E0B375;
--rust:#9C4A2A;
--rust-deep:#7A3520;
--cream:#FDF8EE;
--cream-2:#F5ECD7;
--cream-3:#EFE2C2;
--olive:#6B7B4F;
--olive-soft:#8C9D6F;
--ink:#3B2A1E;
--ink-soft:#5C4632;
--line:rgba(59,42,30,.18);
--line-strong:rgba(59,42,30,.32);
--shadow:0 6px 0 rgba(59,42,30,.10), 0 18px 30px -18px rgba(59,42,30,.4);
--shadow-soft:0 2px 0 rgba(59,42,30,.08), 0 14px 30px -22px rgba(59,42,30,.5);
--paper-noise:url("data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='400' height='400'><filter id='n'><feTurbulence type='fractalNoise' baseFrequency='0.85' numOctaves='2' stitchTiles='stitch'/><feColorMatrix values='0 0 0 0 0.45 0 0 0 0 0.30 0 0 0 0 0.18 0 0 0 0.18 0'/></filter><rect width='100%' height='100%' filter='url(%23n)'/></svg>");
--paper-grain:url("data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='200' height='200'><filter id='g'><feTurbulence baseFrequency='1.6' numOctaves='1'/><feColorMatrix values='0 0 0 0 0.3 0 0 0 0 0.2 0 0 0 0 0.1 0 0 0 0.07 0'/></filter><rect width='100%' height='100%' filter='url(%23g)'/></svg>");
}
*{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth}
body{
font-family:"Noto Serif SC","Cormorant Garamond","Playfair Display",Georgia,serif;
color:var(--ink);
background:var(--cream);
background-image:
radial-gradient(1200px 600px at 80% -10%, rgba(194,127,58,.18), transparent 60%),
radial-gradient(900px 500px at -10% 110%, rgba(107,123,79,.16), transparent 60%),
radial-gradient(600px 400px at 50% 50%, rgba(156,74,42,.05), transparent 70%),
var(--paper-noise);
background-size:auto,auto,auto,400px 400px;
line-height:1.75;
cursor:url("data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='28' height='28' viewBox='0 0 64 64'><g fill='%239C4A2A'><circle cx='20' cy='22' r='6'/><circle cx='44' cy='22' r='6'/><circle cx='12' cy='38' r='5'/><circle cx='52' cy='38' r='5'/><ellipse cx='32' cy='46' rx='14' ry='11'/></g></svg>") 14 14, auto;
position:relative;
}
/* 做旧纸张效果 */
body::before {
  content: "";
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  pointer-events: none;
  z-index: 0;
  background-image: var(--paper-grain);
  opacity: 0.25;
  mix-blend-mode: multiply;
}
body::after {
  content: "";
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  pointer-events: none;
  z-index: 0;
  background: radial-gradient(ellipse at top, rgba(0,0,0,0.02) 0%, rgba(0,0,0,0.08) 100%);
  box-shadow: inset 0 0 50px rgba(0,0,0,0.05);
}
a,button{cursor:url("data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='32' height='32' viewBox='0 0 64 64'><g fill='%23C27F3A'><circle cx='20' cy='22' r='6'/><circle cx='44' cy='22' r='6'/><circle cx='12' cy='38' r='5'/><circle cx='52' cy='38' r='5'/><ellipse cx='32' cy='46' rx='14' ry='11'/></g></svg>") 16 16, pointer;}

/* 特定字体覆盖 */
.section-title em,
.hero h1 .ital,
.pull-quote,
.hero .slogan {
  font-family: "I.Ming", "Libre Baskerville", "Times New Roman", serif !important;
  font-style: italic;
  font-weight: 700;
  color: var(--rust);
}
.culture-card h3 em,
.svc-card h3 em,
.stat-card .stat-num em,
.rev-num {
  font-family: "I.Ming", "Libre Baskerville", "Times New Roman", serif !important;
  font-style: italic;
  font-weight: 700;
}
.hero h1 .paws-text {
  font-family: "Felix Titling", "Times New Roman", serif;
  font-weight: normal;
  font-style: normal;
  letter-spacing: 1px;
}

/* SINCE 2026 印章：仅上下双层线条，左右无边框，极致做旧感 */
.hero h1 .stamp {
  display: inline-block;
  font-family: "Special Elite", "Courier New", monospace;
  font-size: 0.32em;
  letter-spacing: 2.5px;
  color: #8B5230;
  background: #FCF5E0;
  background-image: radial-gradient(circle at 30% 45%, rgba(120, 70, 40, 0.12) 1.2px, transparent 1.5px),
                    linear-gradient(115deg, rgba(200, 170, 120, 0.1) 0%, rgba(150, 110, 70, 0.05) 100%);
  background-size: 14px 14px, 100%;
  border-top: 2.5px solid #8B5230;
  border-bottom: 2.5px solid #8B5230;
  border-left: none;
  border-right: none;
  padding: 7px 24px;
  margin-left: 12px;
  vertical-align: middle;
  box-shadow: 0 -4px 0 0 rgba(80, 50, 25, 0.35),
              0 4px 0 0 rgba(80, 50, 25, 0.35),
              inset 0 1px 0 rgba(255, 245, 215, 0.7),
              inset 0 -1px 0 rgba(80, 50, 25, 0.2),
              2px 2px 6px rgba(0, 0, 0, 0.12),
              -1px -1px 3px rgba(255, 235, 190, 0.8);
  transform: rotate(-2deg) scale(0.98);
  position: relative;
  backdrop-filter: blur(0.8px);
  transition: transform 0.2s ease;
  text-shadow: 0.5px 0.5px 0 rgba(0,0,0,0.05), -0.3px -0.3px 0 rgba(255,240,200,0.6);
}
.hero h1 .stamp:hover {
  transform: rotate(-1deg) scale(0.99);
}
.hero h1 .stamp::before,
.hero h1 .stamp::after {
  content: "✧";
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  font-size: 13px;
  color: #9C5E38;
  opacity: 0.7;
  font-family: "Playfair Display", serif;
  font-weight: normal;
  filter: blur(0.3px);
  text-shadow: 0 1px 0 rgba(0,0,0,0.1);
}
.hero h1 .stamp::before {
  left: -20px;
}
.hero h1 .stamp::after {
  right: -20px;
}
.hero .slogan {
  font-size: 24px;
  font-weight: 400;
  margin: 18px 0 22px;
  line-height: 1.4;
  max-width: 540px;
}

/* ================ Sidebar ================ */
.sidebar{
position:fixed;top:0;left:0;width:268px;height:100%;
background:linear-gradient(180deg,#F2E3C2 0%,#E8D2A6 100%);
border-right:1px solid var(--line-strong);
padding:36px 24px 28px;
display:flex;flex-direction:column;gap:28px;z-index:1000;
box-shadow:6px 0 24px -16px rgba(59,42,30,.4);
transition: transform 0.3s ease;
}
.sidebar::before{content:"";position:absolute;inset:0;background:var(--paper-noise);opacity:.4;pointer-events:none;mix-blend-mode:multiply;}
.sidebar::after{
content:"";position:absolute;top:0;bottom:0;right:6px;width:1px;
background:repeating-linear-gradient(180deg,var(--rust) 0 6px,transparent 6px 12px);opacity:.45;
}
.brand{display:flex;flex-direction:column;gap:8px;position:relative;padding-bottom:20px;border-bottom:1px dashed var(--line-strong)}
.brand-mark{
width:68px;height:68px;border-radius:50%;
background:radial-gradient(circle at 35% 30%,#E8B97A,var(--rust));
display:grid;place-items:center;color:var(--cream);font-family:"Special Elite";font-size:22px;
box-shadow:inset 0 -4px 0 rgba(0,0,0,.18), 4px 4px 0 rgba(59,42,30,.18), 0 0 0 4px rgba(253,248,238,.7);
}
.brand-name{font-family:"Playfair Display",serif;font-weight:700;font-size:17px;color:var(--rust);letter-spacing:.5px;line-height:1.25;margin-top:6px}
.brand-sub{font-family:"Special Elite";font-size:10.5px;color:var(--ink-soft);letter-spacing:2px;margin-top:2px}
.nav{display:flex;flex-direction:column;gap:3px;position:relative}
.nav a{
text-decoration:none;color:var(--ink-soft);font-size:15px;padding:9px 14px;border-radius:6px;
display:flex;align-items:center;gap:10px;border:1px solid transparent;transition:all .25s ease;
font-weight:500;font-family:"Noto Serif SC","Cormorant Garamond",serif;letter-spacing:.4px;
}
.nav a::before{content:"❦";color:var(--amber);opacity:.5;font-size:11px}
.nav a:hover,.nav a.active{
background:var(--cream);color:var(--rust);border-color:var(--line);
transform:translateX(4px);box-shadow:3px 3px 0 var(--amber);
}
.nav a.active::before{opacity:1;color:var(--rust)}
.side-foot{
margin-top:auto;font-family:"Special Elite";font-size:10.5px;color:var(--ink-soft);
opacity:.85;line-height:1.7;position:relative;padding-top:20px;border-top:1px dashed var(--line-strong);
text-align:center;letter-spacing:1px;
}
.side-foot em{font-family:"Cormorant Garamond",serif;font-style:italic;color:var(--rust);font-size:13px;display:block;margin-bottom:6px;letter-spacing:0}

/* mobile menu */
.mobile-menu-btn{display:none;position:fixed;top:18px;left:18px;z-index:1100;
background:var(--rust);color:var(--cream);border:none;padding:9px 18px;border-radius:40px;
font-family:"Special Elite",monospace;font-size:14px;letter-spacing:1.5px;
box-shadow:3px 3px 0 var(--ink);}
.mobile-menu-btn:hover{background:var(--rust-deep);transform:translate(-1px,-1px);box-shadow:5px 5px 0 var(--ink)}
.mobile-overlay{display:none;position:fixed;inset:0;background:rgba(0,0,0,.4);z-index:999;backdrop-filter:blur(2px)}

/* ================ Main ================ */
main{margin-left:268px;padding:0;position:relative;z-index:1}
section{padding:104px 8% 96px;position:relative;scroll-margin-top:20px;}

/* ornamental dividers */
.ornament{display:flex;align-items:center;justify-content:center;gap:14px;margin:0 auto 28px;color:var(--rust);opacity:.7}
.ornament .line{flex:0 0 60px;height:1px;background:linear-gradient(90deg,transparent,var(--rust),transparent)}
.ornament .glyph{font-family:"Playfair Display",serif;font-size:18px;letter-spacing:6px}
.section-tag{
display:inline-block;font-family:"Special Elite";letter-spacing:3px;font-size:12px;
color:var(--rust);padding:5px 14px;border:1px solid var(--rust);border-radius:999px;margin-bottom:18px;
background:rgba(253,248,238,.7);position:relative;
}
.section-tag::before,.section-tag::after{content:"✦";margin:0 6px;opacity:.7;font-size:9px}
.section-title{
font-family:"Playfair Display",serif;font-weight:700;font-size:46px;color:var(--ink);margin-bottom:14px;line-height:1.1;letter-spacing:-.5px;
}
.section-title em{color:var(--rust);font-style:italic;font-weight:700;}
.section-lead{max-width:700px;color:var(--ink-soft);font-size:20px;margin-bottom:48px;font-family:"Noto Serif SC","Cormorant Garamond",serif;line-height:1.7}
.reveal{opacity:0;transform:translateY(24px);transition:opacity .9s ease,transform .9s ease}
.reveal.visible{opacity:1;transform:none}

/* ================ Hero ================ */
#home{
min-height:100vh;display:flex;align-items:center;
background:
radial-gradient(700px 400px at 80% 30%, rgba(156,74,42,.15), transparent 70%),
radial-gradient(500px 300px at 10% 80%, rgba(107,123,79,.12), transparent 70%),
linear-gradient(180deg, transparent, rgba(245,236,215,.6));
}
.hero-grid{display:grid;grid-template-columns:1.15fr .95fr;gap:60px;align-items:center;width:100%}
.hero .eyebrow{
display:inline-flex;align-items:center;gap:10px;
font-family:"Special Elite";letter-spacing:3px;font-size:12px;color:var(--rust);
border:1px solid var(--rust);padding:5px 14px;border-radius:999px;margin-bottom:22px;
background:rgba(253,248,238,.7);
}
.hero .eyebrow .dot{width:6px;height:6px;border-radius:50%;background:var(--rust);box-shadow:0 0 0 4px rgba(156,74,42,.18)}
.hero h1{
font-family:"Playfair Display",serif;font-weight:800;font-size:68px;line-height:1.02;color:var(--ink);
letter-spacing:-1.5px;margin-bottom:8px;
}
.hero h1 .ital{
font-family: "I.Ming", "Libre Baskerville", "Times New Roman", serif !important;
font-style: italic;
font-weight: 700;
color: var(--rust);
}
.hero .intro{
color:var(--ink-soft);
font-size:19px;
max-width:540px;
margin-bottom:34px;
font-family:"Noto Serif SC","Cormorant Garamond",serif;
line-height:1.75;
font-weight:500;
}
.btn-row{display:flex;gap:16px;flex-wrap:wrap}
.btn{
display:inline-flex;align-items:center;gap:10px;padding:14px 26px;
font-family:"Special Elite";letter-spacing:2px;font-size:13px;text-decoration:none;
border:2px solid var(--ink);background:var(--cream);color:var(--ink);
box-shadow:5px 5px 0 var(--ink);transition:all .2s ease;text-transform:uppercase;
}
.btn:hover{transform:translate(-3px,-3px);box-shadow:8px 8px 0 var(--ink)}
.btn.primary{background:var(--rust);color:var(--cream);border-color:var(--rust);box-shadow:5px 5px 0 var(--ink)}
.btn.primary:hover{box-shadow:8px 8px 0 var(--ink)}
.hero-collage{position:relative;height:520px}
.hero-card{
position:absolute;background:var(--cream);border:1px solid var(--line);
padding:18px;border-radius:6px;box-shadow:var(--shadow);
}
.hero-card::before{content:"";position:absolute;inset:0;background:var(--paper-noise);opacity:.4;mix-blend-mode:multiply;border-radius:6px;pointer-events:none}
.polaroid{background:#fff;padding:14px 14px 50px;box-shadow:var(--shadow);position:relative;}
.polaroid .ph{
width:100%;aspect-ratio:1/1;background:
radial-gradient(circle at 30% 30%, #E8B97A, transparent 50%),
radial-gradient(circle at 70% 60%, #9C4A2A, transparent 50%),
linear-gradient(135deg,#6B7B4F,#3B2A1E);
display:grid;place-items:center;color:var(--cream);font-family:"Special Elite";font-size:13px;letter-spacing:2px;
position:relative;overflow:hidden;
}
.polaroid .ph::after{content:"";position:absolute;inset:0;background:var(--paper-grain);opacity:.5;mix-blend-mode:overlay}
.polaroid .cap{position:absolute;bottom:14px;left:0;right:0;text-align:center;font-family:"Special Elite";color:var(--ink-soft);font-size:12px;letter-spacing:1px}
.tape{position:absolute;width:90px;height:22px;background:rgba(194,127,58,.55);top:-10px;left:50%;transform:translateX(-50%) rotate(-3deg);box-shadow:0 2px 4px rgba(0,0,0,.1)}
.hero-card.c1{top:0;right:40px;width:300px;transform:rotate(3deg);z-index:2}
.hero-card.c2{bottom:20px;left:0;width:240px;transform:rotate(-5deg);z-index:1;padding:14px}
.hero-card.c2 .polaroid{padding:10px 10px 40px}
.hero-card.c2 .polaroid .ph{
background:
radial-gradient(circle at 60% 40%, #C8B89A, transparent 60%),
linear-gradient(135deg,#9C4A2A,#5C4632);
}
.hero-stamp-circle{
position:absolute;bottom:80px;right:0;width:110px;height:110px;border-radius:50%;
border:2px dashed var(--rust);color:var(--rust);
display:grid;place-items:center;text-align:center;font-family:"Special Elite";font-size:10px;letter-spacing:2px;
background:rgba(253,248,238,.85);transform:rotate(-10deg);line-height:1.5;
box-shadow:0 8px 20px -10px rgba(59,42,30,.4);z-index:3;
}
.hero-stamp-circle b{display:block;font-size:14px;letter-spacing:1px;color:var(--rust-deep);margin:4px 0}

/* ================ Story ================ */
.story-grid{display:grid;grid-template-columns:1.1fr .9fr;gap:60px;align-items:start}
/* 统一所有段落首字母下沉样式 */
.story-text p{margin-bottom:18px;color:var(--ink-soft);font-size:19px;font-family:"Noto Serif SC","Cormorant Garamond",serif;line-height:1.75;font-weight:500}
.story-text p::first-letter{
  font-family:"Playfair Display",serif;
  font-size:58px;
  float:left;
  line-height:.9;
  padding:8px 12px 0 0;
  color:var(--rust);
  font-weight:700;
}
.pull-quote{
margin:28px 0;padding:18px 24px;border-left:3px double var(--rust);
font-family: "I.Ming", "Libre Baskerville", "Times New Roman", serif !important;
font-style: italic;
font-weight: 700;
color: var(--rust);
font-size:21px;
line-height:1.5;
background:rgba(245,236,215,.5);
}
.focus-box{
background:var(--cream);border:1px solid var(--line);padding:30px 28px;position:relative;border-radius:4px;
box-shadow:var(--shadow);
}
.focus-box::before{content:"";position:absolute;inset:0;background:var(--paper-noise);opacity:.35;mix-blend-mode:multiply;border-radius:4px;pointer-events:none}
.focus-box::after{
content:"";position:absolute;top:8px;left:8px;right:8px;bottom:8px;
border:1px dashed var(--line-strong);border-radius:2px;pointer-events:none;
}
.focus-box h4{font-family:"Special Elite";letter-spacing:2px;color:var(--rust);font-size:13.5px;margin-bottom:20px;text-transform:uppercase;border-bottom:1px dashed var(--line);padding-bottom:10px}
.focus-list{display:flex;flex-direction:column;gap:16px}
.focus-list .item{display:flex;gap:14px;align-items:flex-start}
.focus-list .num{font-family:"Playfair Display",serif;font-style:italic;color:var(--amber);font-size:24px;min-width:30px;font-weight:700}
.focus-list .item b{display:block;color:var(--ink);font-size:17px;margin-bottom:3px;font-family:"Playfair Display",serif}
.focus-list .item span{color:var(--ink-soft);font-size:17px;font-family:"Noto Serif SC","Cormorant Garamond",serif}

/* ================ Market & Opportunity ================ */
#market{background:linear-gradient(180deg,rgba(245,236,215,.4),transparent)}
.market-grid{display:grid;grid-template-columns:repeat(4,1fr);gap:22px;margin-bottom:48px}
.stat-card{
background:var(--cream);border:1px solid var(--line);padding:26px 22px;border-radius:6px;
box-shadow:var(--shadow-soft);position:relative;overflow:hidden;text-align:center;
transition:transform .35s ease;
}
.stat-card::before{content:"";position:absolute;inset:0;background:var(--paper-noise);opacity:.3;mix-blend-mode:multiply;pointer-events:none}
.stat-card:hover{transform:translateY(-4px)}
.stat-card .stat-num{
font-family:"Playfair Display",serif;font-weight:800;font-size:38px;color:var(--rust);
line-height:1;letter-spacing:-1px;margin-bottom:8px;
}
.stat-card .stat-num em{font-style:italic;font-weight:500;color:var(--amber);font-size:.7em}
.stat-card .stat-label{
font-family:"Special Elite";font-size:11px;letter-spacing:1.8px;color:var(--ink-soft);text-transform:uppercase;margin-bottom:8px;
}
.stat-card .stat-desc{
font-family:"Cormorant Garamond","Noto Serif SC",serif;font-size:16px;color:var(--ink-soft);line-height:1.5;
}
.gap-note{
background:var(--cream);border:1px dashed var(--rust);padding:24px 28px;border-radius:6px;
font-family:"Cormorant Garamond",serif;font-size:19px;color:var(--ink);font-style:italic;line-height:1.6;
position:relative;
}
.gap-note::before{
content:"GAP";position:absolute;top:-12px;left:24px;background:var(--cream);padding:0 10px;
font-family:"Special Elite";font-style:normal;font-size:11px;letter-spacing:3px;color:var(--rust);
}

/* ================ Culture ================ */
.culture-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:26px}
.culture-card{
background:var(--cream);border:1px solid var(--line);padding:34px 28px;border-radius:6px;
box-shadow:var(--shadow);position:relative;transition:transform .35s ease,box-shadow .35s ease;
overflow:hidden;
}
.culture-card::before{content:"";position:absolute;inset:0;background:var(--paper-noise);opacity:.3;mix-blend-mode:multiply;pointer-events:none}
.culture-card::after{
content:"";position:absolute;top:0;right:0;width:80px;height:80px;
background:radial-gradient(circle at top right,rgba(194,127,58,.18),transparent 70%);pointer-events:none;
}
.culture-card:hover{transform:translate(-4px,-6px);box-shadow:0 10px 0 rgba(59,42,30,.15), 0 30px 50px -20px rgba(59,42,30,.45)}
.culture-card .pillar-num{
font-family:"Special Elite";font-size:11px;letter-spacing:3px;color:var(--amber);margin-bottom:8px;
}
.culture-card h3{font-family:"Playfair Display",serif;font-size:24px;color:var(--ink);margin:6px 0 14px;letter-spacing:-.3px}
.culture-card h3 em{
font-family: "I.Ming", "Libre Baskerville", "Times New Roman", serif !important;
font-style: italic;
font-weight: 700;
color: var(--rust);
}
.culture-card p{color:var(--ink-soft);font-size:17px;font-family:"Noto Serif SC","Cormorant Garamond",serif;line-height:1.7}
.svc-icon{
width:60px;height:60px;border-radius:50%;background:var(--rust);color:var(--cream);
display:grid;place-items:center;font-size:26px;margin-bottom:18px;
box-shadow:inset 0 -3px 0 rgba(0,0,0,.2), 0 4px 0 rgba(59,42,30,.12);
}
.mission-list{margin-top:8px}
.mission-item{display:flex;gap:16px;margin-bottom:22px;align-items:flex-start}
.mission-item:last-child{margin-bottom:0}
.mission-num{
font-family:"Special Elite";background:var(--rust);color:var(--cream);
width:30px;height:30px;border-radius:50%;display:inline-flex;align-items:center;justify-content:center;
font-size:13px;margin-top:2px;flex-shrink:0;box-shadow:2px 2px 0 rgba(59,42,30,.18);
}
.mission-item b{color:var(--ink);font-family:"Playfair Display",serif;font-size:17px;display:block;margin-bottom:4px}
.mission-item .m-body{color:var(--ink-soft);font-size:17px;font-family:"Noto Serif SC","Cormorant Garamond",serif;line-height:1.7}

/* ================ Strategic Development Plan (增强设计感) ================ */
.plan-grid{display:grid;grid-template-columns:1fr 1fr 1fr;gap:24px;margin-top:20px}
.plan-card{
background: linear-gradient(145deg, #FFFCF4, #FDF5E6);
border: 1.5px solid #CFB27C;
border-radius: 16px;
padding: 1.6rem 1.4rem;
transition: all 0.3s ease;
position: relative;
box-shadow: 4px 4px 12px rgba(0, 0, 0, 0.05), inset 0 1px 0 rgba(255, 250, 220, 0.8);
overflow: hidden;
}
.plan-card::before {
  content: "✧";
  position: absolute;
  bottom: 12px;
  right: 16px;
  font-size: 32px;
  color: rgba(156, 74, 42, 0.12);
  font-family: "Playfair Display", serif;
  pointer-events: none;
  transform: rotate(5deg);
}
.plan-card::after {
  content: "";
  position: absolute;
  inset: 0;
  background-image: radial-gradient(circle at 20% 30%, rgba(160, 110, 60, 0.05) 2px, transparent 2.5px);
  background-size: 16px 16px;
  pointer-events: none;
}
.plan-card:nth-child(1) { background-color: #FEF7E8; border-left: 4px solid #C27F3A; }
.plan-card:nth-child(2) { background-color: #FCF5E2; border-left: 4px solid #9C4A2A; }
.plan-card:nth-child(3) { background-color: #FDF4DF; border-left: 4px solid #6B7B4F; }
.plan-card:hover {
  transform: translateY(-6px);
  box-shadow: 8px 12px 24px -12px rgba(59,42,30,0.35), inset 0 1px 0 rgba(255,245,200,0.9);
}
.plan-card h4 {
  font-family: "Playfair Display", serif;
  font-size: 18px;
  color: var(--rust);
  margin-bottom: 12px;
  letter-spacing: 0.5px;
  display: inline-block;
  border-bottom: 1px dashed #DABE8E;
  padding-bottom: 4px;
}
.plan-card p {
  font-size: 15px;
  color: var(--ink-soft);
  line-height: 1.65;
  font-family: "Noto Serif SC", "Cormorant Garamond", serif;
}
/* 调整 Vision 和 Strategic Plan 之间留白 */
.story-grid.vision-plan {
  margin-top: 32px;
  gap: 32px;
}
.story-grid.vision-plan .focus-box {
  padding: 28px 26px;
}
/* 消除大片空白：减少上下margin */
#culture .story-grid:last-of-type {
  margin-top: 24px;
}

/* ================ Services ================ */
.services-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:28px;margin-bottom:48px}
.svc-card{
background:var(--cream);border:1px solid var(--line);padding:32px 26px;border-radius:6px;
box-shadow:var(--shadow);position:relative;transition:transform .35s ease,box-shadow .35s ease;
}
.svc-card::before{content:"";position:absolute;inset:0;background:var(--paper-noise);opacity:.3;mix-blend-mode:multiply;border-radius:6px;pointer-events:none}
.svc-card:hover{transform:translate(-4px,-6px);box-shadow:0 10px 0 rgba(59,42,30,.15), 0 30px 50px -20px rgba(59,42,30,.45)}
.svc-card h3{font-family:"Playfair Display",serif;font-size:23px;color:var(--ink);margin-bottom:10px}
.svc-card h3 em{
font-family: "I.Ming", "Libre Baskerville", "Times New Roman", serif !important;
font-style: italic;
font-weight: 700;
color: var(--rust);
}
.svc-card p{color:var(--ink-soft);font-size:17px;margin-bottom:14px;font-family:"Noto Serif SC","Cormorant Garamond",serif;line-height:1.7}
.svc-card .meta{font-family:"Special Elite";font-size:10.5px;letter-spacing:2.5px;color:var(--olive);text-transform:uppercase;padding-top:10px;border-top:1px dashed var(--line)}
.revenue-grid{display:grid;grid-template-columns:1.1fr .9fr;gap:32px;align-items:start;margin-top:36px}
.revenue-list{display:flex;flex-direction:column;gap:14px}
.rev-row{
display:flex;align-items:center;gap:18px;padding:18px 22px;
background:var(--cream);border:1px solid var(--line);border-radius:6px;
box-shadow:var(--shadow-soft);transition:transform .25s ease;
}
.rev-row:hover{transform:translateX(6px)}
.rev-num{
font-family: "I.Ming", "Libre Baskerville", "Times New Roman", serif !important;
font-style: italic;
font-weight: 700;
color: var(--amber);
font-size:32px;
min-width:40px;
}
.rev-row b{display:block;color:var(--ink);font-family:"Playfair Display",serif;font-size:17px;margin-bottom:2px}
.rev-row span{color:var(--ink-soft);font-size:17px;font-family:"Noto Serif SC","Cormorant Garamond",serif}
.marketing-box{
background:linear-gradient(135deg,rgba(156,74,42,.06),rgba(107,123,79,.08));
border:1px solid var(--line);border-radius:6px;padding:28px;position:relative;
}
.marketing-box::before{content:"";position:absolute;inset:0;background:var(--paper-noise);opacity:.2;mix-blend-mode:multiply;border-radius:6px;pointer-events:none}
.marketing-box h4{font-family:"Special Elite";font-size:12px;letter-spacing:3px;color:var(--rust);text-transform:uppercase;margin-bottom:18px;padding-bottom:10px;border-bottom:1px dashed var(--line)}
.marketing-box .mk-item{margin-bottom:18px}
.marketing-box .mk-item:last-child{margin-bottom:0}
.marketing-box .mk-item b{font-family:"Playfair Display",serif;color:var(--ink);font-size:17px;display:block;margin-bottom:4px}
.marketing-box .mk-item p{color:var(--ink-soft);font-size:16px;font-family:"Noto Serif SC","Cormorant Garamond",serif;line-height:1.65}
.doing-grid{display:grid;grid-template-columns:1fr 1fr;gap:24px;margin-top:48px}
.doing{
border:1px dashed var(--rust);background:rgba(253,248,238,.7);padding:28px;border-radius:6px;position:relative;
transition:transform .3s ease;
}
.doing:hover{transform:translateY(-4px)}
.doing .stamp-tag{position:absolute;top:-12px;left:24px;background:var(--rust);color:var(--cream);font-family:"Special Elite";font-size:10.5px;padding:4px 10px;letter-spacing:2px;box-shadow:2px 2px 0 rgba(59,42,30,.18)}
.doing h4{font-family:"Playfair Display",serif;font-size:20px;margin-bottom:8px;color:var(--ink)}
.doing p{color:var(--ink-soft);font-size:17px;font-family:"Noto Serif SC","Cormorant Garamond",serif}

/* ================ Map ================ */
.map-wrap{
background:var(--cream);border:6px double #DAB77A;border-radius:24px;padding:12px;
box-shadow:6px 6px 0 rgba(59,42,30,.12), 0 18px 40px -20px rgba(59,42,30,.35);
position:relative;overflow:hidden;max-width:100%;box-sizing:border-box;isolation:isolate;
}
.map-wrap::before{
content:"";position:absolute;inset:0;background:var(--paper-noise);opacity:.25;
mix-blend-mode:multiply;pointer-events:none;border-radius:20px;z-index:2;
}
.map-wrap::after{
content:"";position:absolute;top:18px;left:18px;right:18px;bottom:18px;
border:1px dashed rgba(194,127,58,.5);border-radius:14px;pointer-events:none;z-index:3;
}
#vintageMap{
width:100%;height:520px;max-width:100%;border-radius:14px;
box-shadow:inset 0 0 0 1px var(--line);background:#efe6d2;cursor:inherit;
overflow:hidden;position:relative;z-index:1;contain:strict;
}
@media (max-width:720px){#vintageMap{height:360px}}
#vintageMap .leaflet-tile-pane{filter:sepia(.35) saturate(.85) hue-rotate(-8deg) brightness(.98) contrast(.95);}
.leaflet-container{font-family:"Noto Serif SC",serif;background:#f5ecd6;}
.leaflet-popup-content-wrapper{background:#FDF8EE;border:1px solid #9C4A2A;border-radius:4px;
box-shadow:4px 4px 0 rgba(59,42,30,.18);padding:4px 6px;}
.leaflet-popup-tip{background:#FDF8EE;border:1px solid #9C4A2A;}
.leaflet-popup-content{margin:10px 14px;color:#3B2A1E;font-size:13px;line-height:1.6;}
.leaflet-popup-content .pop-name{font-family:"Special Elite",monospace;color:#9C4A2A;font-size:13px;letter-spacing:2px;margin-bottom:4px;}
.leaflet-popup-content .pop-desc{font-weight:600;color:#3B2A1E;}
.leaflet-popup-content .pop-addr{font-size:12px;color:#5C4632;margin-top:2px;}
.leaflet-control-zoom a{background:#FDF8EE!important;color:#9C4A2A!important;border:1px solid #9C4A2A!important;font-family:"Special Elite",monospace;}
.leaflet-control-attribution{background:rgba(253,248,238,.7)!important;font-family:"Special Elite",monospace;font-size:10px;}
.city-tags{display:flex;flex-wrap:wrap;gap:10px;margin-top:24px;}
.city-tags .tag{
font-family:"Special Elite";font-size:12px;letter-spacing:1.5px;color:var(--rust);
padding:6px 14px;border:1px solid var(--rust);border-radius:999px;background:var(--cream);transition:all .2s ease;
}
.city-tags .tag:hover{background:var(--rust);color:var(--cream);transform:translateY(-2px);}

/* ================ Timeline ================ */
.timeline{position:relative;padding-left:30px;max-width:860px}
.timeline::before{content:"";position:absolute;left:8px;top:6px;bottom:6px;width:2px;background:repeating-linear-gradient(180deg,var(--rust) 0 6px,transparent 6px 12px)}
.tl-item{position:relative;margin-bottom:30px;padding:24px 28px;background:var(--cream);border:1px solid var(--line);border-radius:6px;box-shadow:var(--shadow);transition:transform .3s ease}
.tl-item:hover{transform:translateX(6px)}
.tl-item::before{content:"";position:absolute;left:-28px;top:26px;width:14px;height:14px;border-radius:50%;background:var(--amber);border:3px solid var(--cream);box-shadow:0 0 0 2px var(--rust)}
.tl-year{font-family:"Special Elite";color:var(--rust);font-size:12.5px;letter-spacing:2.5px;margin-bottom:6px}
.tl-item h4{font-family:"Playfair Display",serif;font-size:20px;margin-bottom:6px;color:var(--ink)}
.tl-item p{color:var(--ink-soft);font-size:17px;font-family:"Noto Serif SC","Cormorant Garamond",serif;line-height:1.7}

/* ================ Skills ================ */
.skill-block{margin-bottom:36px}
.skill-block h4{font-family:"Special Elite";letter-spacing:2.5px;color:var(--rust);font-size:13px;margin-bottom:14px;text-transform:uppercase}
.chips{display:flex;flex-wrap:wrap;gap:10px}
.chip{
padding:8px 16px;border-radius:4px;background:var(--cream);border:1px solid var(--ink);
font-size:15px;color:var(--ink);box-shadow:3px 3px 0 var(--amber);transition:all .2s ease;
font-family:"Noto Serif SC","Cormorant Garamond",serif;font-weight:500;
}
.chip:hover{transform:translate(-2px,-2px);box-shadow:5px 5px 0 var(--rust)}
.chip.olive{box-shadow:3px 3px 0 var(--olive)}
.chip.olive:hover{box-shadow:5px 5px 0 var(--olive)}

/* ================ Contact ================ */
.envelope{
max-width:780px;margin:0 auto;background:var(--cream);
border:1px solid var(--line);border-radius:6px;padding:54px 56px 48px;position:relative;box-shadow:var(--shadow);
}
.envelope::before{content:"";position:absolute;inset:0;background:var(--paper-noise);opacity:.3;mix-blend-mode:multiply;border-radius:6px;pointer-events:none}
.envelope::after{
content:"";position:absolute;top:-1px;left:-1px;right:-1px;height:30px;
background:repeating-linear-gradient(45deg,var(--rust) 0 12px,var(--cream) 12px 24px,var(--ink) 24px 36px,var(--cream) 36px 48px);
opacity:.85;
}
.env-inner{padding-top:28px}
.stamp-img{
position:absolute;right:40px;top:60px;width:90px;height:110px;background:var(--cream);
border:1px dashed var(--rust);display:grid;place-items:center;text-align:center;
font-family:"Special Elite";color:var(--rust);font-size:11px;letter-spacing:1.5px;line-height:1.3;
transform:rotate(6deg);box-shadow:var(--shadow);padding:8px;
}
.contact-grid{display:grid;grid-template-columns:1fr 1fr;gap:18px 32px;margin-top:24px}
.c-row{border-bottom:1px dashed var(--line);padding:10px 0}
.c-row .lbl{font-family:"Special Elite";font-size:10.5px;letter-spacing:2px;color:var(--rust);text-transform:uppercase;margin-bottom:4px}
.c-row .val{font-size:16px;color:var(--ink);font-family:"Noto Serif SC","Cormorant Garamond",serif}
footer{
text-align:center;padding:40px 24px 60px;font-family:"Special Elite";font-size:12px;
letter-spacing:2.5px;color:var(--ink-soft);border-top:1px dashed var(--line);margin:0 8%;
}
footer .ft-orn{display:block;margin-bottom:10px;color:var(--rust);font-family:"Playfair Display",serif;font-size:16px;letter-spacing:8px}

/* paw cursor follower */
.paw-trail{position:fixed;width:24px;height:24px;pointer-events:none;z-index:9999;opacity:0;transition:opacity .6s ease}
.paw-trail svg{width:100%;height:100%}

/* ================ Responsive ================ */
@media (max-width:900px){
.mobile-menu-btn{display:block!important}
.sidebar{transform:translateX(-100%);z-index:1050;width:280px}
.sidebar.open{transform:translateX(0)}
.mobile-overlay{display:block;opacity:0;visibility:hidden;transition:opacity .3s ease,visibility .3s;z-index:1040}
.mobile-overlay.show{opacity:1;visibility:visible}
main{margin-left:0}
section{padding:84px 6% 80px}
.hero-grid,.story-grid,.culture-grid,.plan-grid,.revenue-grid{grid-template-columns:1fr;gap:40px}
.hero h1{font-size:42px}
.section-title{font-size:32px}
.services-grid,.doing-grid,.contact-grid,.market-grid{grid-template-columns:1fr}
.market-grid{grid-template-columns:1fr 1fr}
.stamp-img{position:relative;right:auto;top:auto;margin:0 auto 20px}
.envelope{padding:48px 24px}
.hero-collage{height:auto;display:flex;flex-direction:column;gap:24px;align-items:center}
.hero-card.c1,.hero-card.c2{position:relative;top:auto;left:auto;right:auto;bottom:auto;width:260px;transform:rotate(2deg)}
.hero-card.c2{transform:rotate(-3deg)}
.hero-stamp-circle{position:relative;bottom:auto;right:auto;margin:0 auto}
}
@media (max-width:540px){
.market-grid{grid-template-columns:1fr}
}
</style>
</head>
<body>
<button class="mobile-menu-btn" id="mobileMenuBtn">☰ MENU</button>
<div class="mobile-overlay" id="mobileOverlay"></div>
<aside class="sidebar" id="sidebar">
<div class="brand">
<div class="brand-mark">P&P</div>
<div class="brand-name">Paws &amp; Peace<br>Pet Companion<br>Therapy Station</div>
<div class="brand-sub">EST. 2026 · HEALING HEARTS</div>
</div>
<nav class="nav" id="nav">
<a href="#home" class="active">Home</a>
<a href="#story">Our Story</a>
<a href="#market">Market &amp; Why Now</a>
<a href="#culture">Culture &amp; Mission</a>
<a href="#services">Therapy Services</a>
<a href="#map">Healing Footprint</a>
<a href="#journal">Milestones</a>
<a href="#skills">Skills &amp; Passions</a>
<a href="#contact">Letters &amp; Contact</a>
</nav>
<div class="side-foot">
<em>"Paws for comfort,<br/>peace for soul."</em>
A VINTAGE HEALING DIARY
</div>
</aside>
<main>
<!-- HERO -->
<section id="home">
<div class="hero-grid">
<div class="hero reveal">
<span class="eyebrow"><span class="dot"></span>PAWS &amp; PEACE · EST. 2026</span>
<h1><span class="paws-text">Paws for comfort,</span><br/><span class="ital">peace for soul.</span><span class="stamp">SINCE 2026</span></h1>
<div class="slogan">Let every gentle touch become a quiet harbor for the soul --- healing modern loneliness through pet companionship.</div>
<p class="intro">Paws &amp; Peace is a professional pet companion therapy station. We pair trained therapy animals with licensed counselors to deliver warm, personalized emotional support --- a space where the human-animal bond becomes a doorway back to inner peace.</p>
<div class="btn-row">
<a href="#contact" class="btn primary">◈ Book a Session</a>
<a href="#story" class="btn">Read Our Story</a>
</div>
</div>
<div class="reveal hero-collage">
<div class="hero-card c1">
<div class="polaroid">
<span class="tape"></span>
<div class="ph">FIELD NOTES · 2026</div>
<div class="cap">--- Therapy dog "Biscuit"</div>
</div>
</div>
<div class="hero-card c2">
<div class="polaroid">
<span class="tape"></span>
<div class="ph">QUIET HOURS</div>
<div class="cap">--- Cat "Maple"</div>
</div>
</div>
<div class="hero-stamp-circle">
APPROVED<br/><b>2026</b>PAWS &amp; PEACE
</div>
</div>
</div>
</section>

<!-- STORY -->
<section id="story">
<div class="ornament"><span class="line"></span><span class="glyph">❦ ❦ ❦</span><span class="line"></span></div>
<span class="section-tag reveal">CHAPTER I · OUR STORY</span>
<h2 class="section-title reveal">Warm paws, <em>quiet hearts</em></h2>
<p class="section-lead reveal">Paws &amp; Peace was founded on a single belief --- that animals are nature's most patient therapists, and that the simple act of being together is itself a form of healing.</p>
<div class="story-grid">
<div class="story-text reveal">
<p>In a fast-paced, digitally exhausted world, more and more people quietly carry anxiety, loneliness and emotional fatigue. Yet many cannot keep a pet --- housing limits, busy schedules, allergies, or the responsibility itself become barriers. Paws &amp; Peace fills that quiet gap, offering a professional, warm space where every visitor can interact with well-trained therapy pets under the guidance of certified counselors and animal trainers.</p>
<div class="pull-quote">"Paws are not only companions --- they are emotional bridges connecting people to inner peace."</div>
<p>Our slogan, "Paws for comfort, peace for soul," is more than a tagline. <b>Paws</b> are our therapy animals --- the gentle carriers of our service. <b>Comfort</b> is the immediate relief we offer: lowered stress, softened anxiety, an emotional reset. <b>Peace</b> is our long-term promise: a calmer mind, a quieter heart, a more compassionate connection to the world.</p>
<p>This is not a pet café. It is a slow, gentle, carefully designed healing journey --- built on three pillars: professionalism, warmth, and personalization.</p>
</div>
<div class="focus-box reveal">
<h4>✦ What we focus on &amp; learn</h4>
<div class="focus-list">
<div class="item"><span class="num">01</span><div><b>Animal-Assisted Intervention (AAI)</b><span>Scientifically proven to lower cortisol, ease anxiety and improve mood.</span></div></div>
<div class="item"><span class="num">02</span><div><b>Mental Health &amp; Emotional Wellbeing</b><span>One-on-one sessions, group activities and pet-assisted counseling.</span></div></div>
<div class="item"><span class="num">03</span><div><b>Pet Care Education</b><span>Training courses and mental health workshops for the community.</span></div></div>
<div class="item"><span class="num">04</span><div><b>End-of-life Emotional Support</b><span>Compassionate companionship through farewells and grief.</span></div></div>
</div>
</div>
</div>
</section>

<!-- MARKET -->
<section id="market">
<div class="ornament"><span class="line"></span><span class="glyph">✦ ❦ ✦</span><span class="line"></span></div>
<span class="section-tag reveal">CHAPTER II · MARKET &amp; WHY NOW</span>
<h2 class="section-title reveal">A quiet revolution in <em>wellness</em></h2>
<p class="section-lead reveal">The global pet-therapy economy is growing --- and the emotional needs behind it are growing even faster. Our project sits at the meeting point of mental-health awareness and the human-animal bond.</p>
<div class="market-grid">
<div class="stat-card reveal">
<div class="stat-num">$368.88<em>M</em></div>
<div class="stat-label">Global Market by 2030</div>
<div class="stat-desc">Projected size of the global pet-therapy market.</div>
</div>
<div class="stat-card reveal">
<div class="stat-num">7.58<em>%</em></div>
<div class="stat-label">CAGR · 2024-2030</div>
<div class="stat-desc">Compound annual growth rate of pet-therapy services.</div>
</div>
<div class="stat-card reveal">
<div class="stat-num">2030</div>
<div class="stat-label">Cultural Shift</div>
<div class="stat-desc">Urban pets in China expected to outnumber children under four.</div>
</div>
<div class="stat-card reveal">
<div class="stat-num">↓ Cortisol</div>
<div class="stat-label">Clinical Effect</div>
<div class="stat-desc">Time with animals measurably reduces stress &amp; relieves negative emotions.</div>
</div>
</div>
<div class="gap-note reveal">
Many people long for the comfort of a pet --- yet living conditions, work pressure, allergies or schedules prevent them from keeping one. <b>Our pet companion therapy station fills exactly that gap</b>, making professional, healing pet companionship accessible to everyone.
</div>
</section>

<!-- CULTURE & MISSION -->
<section id="culture">
<div class="ornament"><span class="line"></span><span class="glyph">❦ ✦ ❦</span><span class="line"></span></div>
<span class="section-tag reveal">CHAPTER III · CULTURE &amp; MISSION</span>
<h2 class="section-title reveal">Healing through <em>every paw</em></h2>
<p class="section-lead reveal">Three pillars hold up our work --- and a single mission unites them: to heal modern loneliness through the natural, generous love of animals.</p>
<div class="culture-grid">
<div class="culture-card reveal">
<div class="svc-icon" style="background:var(--amber)">📋</div>
<div class="pillar-num">PILLAR · 01</div>
<h3>Professionalism <em>--- trust through science</em></h3>
<p>Unlike ordinary pet cafés, we combine emotional support, simple psychological guidance and well-trained therapy pets to create a meaningful healing experience. Every therapy animal receives behavior training and regular health checks to ensure safe, comfortable interactions.</p>
</div>
<div class="culture-card reveal">
<div class="svc-icon" style="background:var(--rust)">🤍</div>
<div class="pillar-num">PILLAR · 02</div>
<h3>Warmth <em>--- a safe sanctuary</em></h3>
<p>Soft lighting, calming music, natural materials and low-stimulation environments reduce stress and anxiety. Staff communicate with empathy and patience --- every visitor feels respected, understood, and quietly at home.</p>
</div>
<div class="culture-card reveal">
<div class="svc-icon" style="background:var(--olive)">🌟</div>
<div class="pillar-num">PILLAR · 03</div>
<h3>Personalization <em>--- every journey honored</em></h3>
<p>Before therapy, clients receive emotional assessments and preference evaluations. Quiet cats may help highly sensitive individuals relax; energetic dogs can encourage elderly clients to reconnect socially. Each plan is tailored.</p>
</div>
</div>
<div class="focus-box reveal" style="margin-top:48px">
<h4>✦ Our Mission · Healing modern loneliness through pet companionship</h4>
<div class="mission-list">
<div class="mission-item">
<span class="mission-num">1</span>
<div><b>Responding to the mental-health challenges of modern society</b><div class="m-body">Rapid urbanization, digital dependence and competitive lifestyles intensify anxiety, loneliness and emotional fatigue across all ages. Traditional counseling can feel too formal --- we make emotional support warmer and more approachable through the natural human-animal bond.</div></div>
</div>
<div class="mission-item">
<span class="mission-num">2</span>
<div><b>Making emotional healing more accessible</b><div class="m-body">Through professional therapy spaces, guided interaction sessions and mobile companion services, we bring the healing benefits of pet companionship to people who cannot keep a pet themselves.</div></div>
</div>
<div class="mission-item">
<span class="mission-num">3</span>
<div><b>Promoting social responsibility &amp; public wellness</b><div class="m-body">Beyond commercial development, we organize public mental-health workshops, elderly companionship programs, student stress-relief activities and community pet-therapy events with schools, hospitals and non-profits --- contributing to a more compassionate society.</div></div>
</div>
</div>
</div>
<div class="story-grid vision-plan reveal" style="margin-top:24px; gap:28px; align-items:stretch">
<div class="focus-box">
<h4>✦ Our Vision</h4>
<p style="color:var(--ink-soft);font-family:'Noto Serif SC','Cormorant Garamond',serif;font-size:18px;line-height:1.75">Paws &amp; Peace hopes to create a warm and relaxing space where people can reduce stress and feel emotionally supported through pet companionship. As mental-health awareness grows, pet-assisted therapy will become increasingly popular among young people, students and the elderly.</p>
<p style="margin-top:16px;font-family:'Noto Serif SC','Cormorant Garamond',serif;color:var(--ink-soft);font-size:17px"><b style="font-family:'Playfair Display',serif;color:var(--ink)">Long-term goal:</b> not to become the biggest company, but to help more people feel relaxed, understood, and emotionally connected.</p>
</div>
<div class="focus-box">
<h4>✦ Strategic Development Plan</h4>
<div class="plan-grid" style="grid-template-columns:1fr;gap:12px">
<div class="plan-card"><h4>📅 Short-term · 1--2 yrs</h4><p>Offline therapy space + online booking platform. Grow through social media &amp; community activities. Partner with local counseling centers.</p></div>
<div class="plan-card"><h4>📅 Mid-term · 3--5 yrs</h4><p>Expand into schools, nursing homes and companies with customized programs. Develop training systems for therapy pets and staff.</p></div>
<div class="plan-card"><h4>📅 Long-term · 5+ yrs</h4><p>Open therapy stations in more cities. Become a trusted emotional-wellness brand for young people and families.</p></div>
</div>
</div>
</div>
</section>

<!-- SERVICES & MODEL -->
<section id="services">
<div class="ornament"><span class="line"></span><span class="glyph">✦ ❦ ✦</span><span class="line"></span></div>
<span class="section-tag reveal">CHAPTER IV · THERAPY SERVICES</span>
<h2 class="section-title reveal">Healing through <em>gentle paws</em></h2>
<p class="section-lead reveal">Our core offering is personalized pet companion therapy --- designed around emotional needs rather than entertainment. Every guest begins with a psychological assessment; counselors and pet trainers then co-design a fitting therapy plan.</p>
<div class="services-grid">
<div class="svc-card reveal"><div class="svc-icon">◈</div><h3>One-on-One Companion Sessions</h3><p>Private 50-minute sessions with a calm therapy pet and a licensed counselor. Gentle pets are paired with clients managing anxiety; simple psychological guidance supports relaxation and reset.</p><div class="meta">SERVICE · 01</div></div>
<div class="svc-card reveal"><div class="svc-icon">◈</div><h3>Group Interaction Activities</h3><p>Small-group workshops where participants bond with therapy pets and with each other --- reducing loneliness and quietly rebuilding social trust.</p><div class="meta">SERVICE · 02</div></div>
<div class="svc-card reveal"><div class="svc-icon">◈</div><h3>Pet-Assisted Counseling &amp; Outreach</h3><p>Integrated mental-health sessions in our studio, plus on-site services in hospitals, nursing homes, schools and enterprises through partnership programs.</p><div class="meta">SERVICE · 03</div></div>
</div>
<h3 style="font-family:'Playfair Display',serif;color:var(--ink);font-size:24px;margin-bottom:6px;letter-spacing:-.3px">Operation &amp; <em style="color:var(--rust);font-family:'Cormorant Garamond',serif;font-style:italic;font-weight:600">profit model</em></h3>
<p style="color:var(--ink-soft);font-family:'Noto Serif SC','Cormorant Garamond',serif;font-size:18px;max-width:760px">An integrated <b>"physical store + online service"</b> model. Customers book online or walk in; we also bring therapy on-site through partnerships with hospitals, nursing homes, schools and enterprises.</p>
<div class="revenue-grid">
<div class="revenue-list reveal">
<div class="rev-row"><span class="rev-num">01</span><div><b>Companion Therapy Fees</b><span>One-on-one session fees and group activity fees --- our primary revenue.</span></div></div>
<div class="rev-row"><span class="rev-num">02</span><div><b>Pet-Related Product Sales</b><span>Curated pet toys, pet food, and vintage-style brand souvenirs.</span></div></div>
<div class="rev-row"><span class="rev-num">03</span><div><b>Training &amp; Mental-Health Courses</b><span>Pet care training, mental-health lectures and community workshops.</span></div></div>
<div class="rev-row"><span class="rev-num">04</span><div><b>Institutional Cooperation</b><span>Customized programs with hospitals, schools and companies --- stable income.</span></div></div>
</div>
<div class="marketing-box reveal">
<h4>✦ Marketing Highlights</h4>
<div class="mk-item"><b>Emotional Marketing</b><p>We share the concept of "pet companion healing" through short videos, social media and public-welfare activities --- building real emotional connection rather than transactional reach.</p></div>
<div class="mk-item"><b>Joint &amp; Community Marketing</b><p>Cross-industry collaboration with psychological counseling institutions, health clubs and community centers expands our influence and trust.</p></div>
<div class="mk-item"><b>Membership &amp; Loyalty</b><p>Vintage-style membership cards and seasonal preferential activities reward returning visitors and strengthen long-term care.</p></div>
</div>
</div>
<div class="doing-grid">
<div class="doing reveal"><span class="stamp-tag">CURRENT PROJECT</span><h4>"Healing Living Room" Pop-up</h4><p>Partnering with community centers in 4 cities to offer free trial sessions for stressed urban workers and senior residents.</p></div>
<div class="doing reveal"><span class="stamp-tag">SELF-GROWTH</span><h4>Research &amp; Education</h4><p>A 6-month study on pet therapy's effect on workplace burnout, conducted with local universities and shared via open workshops.</p></div>
</div>
</section>

<!-- MAP -->
<section id="map">
<div class="ornament"><span class="line"></span><span class="glyph">❦ ✦ ❦</span><span class="line"></span></div>
<span class="section-tag reveal">CHAPTER V · HEALING FOOTPRINT</span>
<h2 class="section-title reveal">Our <em>cities</em> of comfort</h2>
<p class="section-lead reveal">Each pin on the map represents a place where Paws &amp; Peace brings comfort. Click a cat-paw marker to read its short field note.</p>
<div class="map-wrap reveal">
<div id="vintageMap"></div>
</div>
<div class="city-tags reveal" id="cityTags"></div>
</section>

<!-- MILESTONES -->
<section id="journal">
<div class="ornament"><span class="line"></span><span class="glyph">✦ ❦ ✦</span><span class="line"></span></div>
<span class="section-tag reveal">CHAPTER VI · MILESTONES</span>
<h2 class="section-title reveal">A <em>fading diary</em> of our journey</h2>
<p class="section-lead reveal">Every quiet step we've taken --- recorded in the pages of a slow, vintage journal.</p>
<div class="timeline">
<div class="tl-item reveal"><div class="tl-year">★ SPRING 2026</div><h4>Brand Launch &amp; First Therapy Dog "Biscuit"</h4><p>Opened our first studio in a renovated vintage house. Began weekly visits to a local nursing home.</p></div>
<div class="tl-item reveal"><div class="tl-year">★ AUTUMN 2026</div><h4>Partnership with Mental-Health Hospital</h4><p>Launched an AAI program in pediatric and psychiatric wards, serving 500+ patients in the first half-year.</p></div>
<div class="tl-item reveal"><div class="tl-year">★ SUMMER 2027</div><h4>National Tour · "Old Times, Warm Paws"</h4><p>Traveled to 12 cities, documenting pet-human bonds through vintage film photography and hand-bound journals.</p></div>
<div class="tl-item reveal"><div class="tl-year">★ 2028 · NOW</div><h4>Four Permanent "Healing Living Rooms"</h4><p>Established physical spaces in Beijing, Shanghai, Chengdu and Guangzhou --- open daily by appointment.</p></div>
</div>
</section>

<!-- SKILLS -->
<section id="skills">
<div class="ornament"><span class="line"></span><span class="glyph">❦ ✦ ❦</span><span class="line"></span></div>
<span class="section-tag reveal">CHAPTER VII · SKILLS &amp; PASSIONS</span>
<h2 class="section-title reveal">Craftsmanship &amp; <em>heartfelt tools</em></h2>
<p class="section-lead reveal">We are both scientific practitioners and slow-life enthusiasts --- every certification sits beside an old film camera and a stack of handwritten letters.</p>
<div class="skill-block reveal"><h4>✦ Professional Skills</h4><div class="chips"><span class="chip">Therapy Dog Certification (IAHAIO)</span><span class="chip">Pet Nutrition &amp; Wellness</span><span class="chip">Animal Behavior Consulting · IAABC</span><span class="chip">Pet First Aid &amp; CPR</span><span class="chip">End-of-life Doula Training</span><span class="chip">Mental Health First Aid</span></div></div>
<div class="skill-block reveal"><h4>✦ Personal Passions</h4><div class="chips"><span class="chip olive">Vintage Film Photography</span><span class="chip olive">Handwritten Letters</span><span class="chip olive">Mid-century Furniture</span><span class="chip olive">Jazz &amp; Vinyl Records</span><span class="chip olive">Journaling &amp; Collage</span><span class="chip olive">Herbal Gardening</span></div></div>
<div class="skill-block reveal"><h4>✦ Continuous Learning</h4><div class="chips"><span class="chip">Animal Welfare Policy</span><span class="chip">Vintage Healing Aesthetics</span><span class="chip">Human-Animal Bond Research</span><span class="chip">Geriatric Pet Medicine</span></div></div>
</section>

<!-- CONTACT -->
<section id="contact">
<div class="ornament"><span class="line"></span><span class="glyph">✦ ❦ ✦</span><span class="line"></span></div>
<span class="section-tag reveal">CHAPTER VIII · LETTERS &amp; COLLABORATION</span>
<h2 class="section-title reveal">Write us a <em>slower letter</em></h2>
<p class="section-lead reveal">For therapy appointments, partnerships, or simply to say hello --- we reply with care, the way letters used to be answered.</p>
<div class="envelope reveal">
<div class="stamp-img">PET<br/>HEALING<br/>★ ★ ★<br/>POSTAGE<br/>2026</div>
<div class="env-inner">
<h3 style="font-family:'Special Elite', monospace; color:var(--rust); font-size:26px; margin-bottom:6px; letter-spacing:2px;">To the one who slows down</h3>
<p style="color:var(--ink-soft);font-size:17px;font-family:'Noto Serif SC','Cormorant Garamond',serif">Reach us through any of these vintage channels:</p>
<div class="contact-grid">
<div class="c-row"><div class="lbl">EMAIL</div><div class="val">hello@pawsandpeace.com</div></div>
<div class="c-row"><div class="lbl">TELEPHONE</div><div class="val">+86 (10) 6502 8833</div></div>
<div class="c-row"><div class="lbl">WECHAT OFFICIAL</div><div class="val">PawsAndPeace</div></div>
<div class="c-row"><div class="lbl">INSTAGRAM / 小红书</div><div class="val">@pawsandpeace</div></div>
<div class="c-row"><div class="lbl">STUDIO ADDRESS</div><div class="val">Beijing · Shanghai · Chengdu · Guangzhou</div></div>
<div class="c-row"><div class="lbl">PARTNERSHIP</div><div class="val">partner@pawsandpeace.com</div></div>
</div>
<p style="margin-top:30px;font-style:italic;color:var(--ink-soft);font-family:'Cormorant Garamond','Playfair Display',serif;font-size:18px">--- Yours, with a soft paw.</p>
</div>
</div>
</section>
<footer>
<span class="ft-orn">❦ ✦ ❦</span>
© 2026 PAWS &amp; PEACE · PET COMPANION THERAPY STATION · "PAWS FOR COMFORT, PEACE FOR SOUL"
</footer>
</main>

<div class="paw-trail" id="paw">
<svg viewBox="0 0 64 64"><g fill="#9C4A2A" opacity=".7"><circle cx='20' cy='22' r='6'/><circle cx='44' cy='22' r='6'/><circle cx='12' cy='38' r='5'/><circle cx='52' cy='38' r='5'/><ellipse cx='32' cy='46' rx='14' ry='11'/></g></svg>
</div>

<script>
const mobileBtn=document.getElementById('mobileMenuBtn');
const sidebarEl=document.getElementById('sidebar');
const overlay=document.getElementById('mobileOverlay');
const navLinkItems=document.querySelectorAll('#nav a');
function openSidebar(){sidebarEl.classList.add('open');overlay&&overlay.classList.add('show');document.body.style.overflow='hidden'}
function closeSidebar(){sidebarEl.classList.remove('open');overlay&&overlay.classList.remove('show');document.body.style.overflow=''}
mobileBtn&&mobileBtn.addEventListener('click',e=>{e.stopPropagation();sidebarEl.classList.contains('open')?closeSidebar():openSidebar()});
overlay&&overlay.addEventListener('click',closeSidebar);
navLinkItems.forEach(l=>l.addEventListener('click',()=>{if(window.innerWidth<=900)closeSidebar()}));
window.addEventListener('resize',()=>{if(window.innerWidth>900)closeSidebar()});
const sections=[...document.querySelectorAll('#home,#story,#market,#culture,#services,#map,#journal,#skills,#contact')];
window.addEventListener('scroll',()=>{
const y=window.scrollY+140;let idx=0;
sections.forEach((s,i)=>{if(s&&s.offsetTop<=y)idx=i});
navLinkItems.forEach((a,i)=>a.classList.toggle('active',i===idx));
});
const io=new IntersectionObserver(es=>es.forEach(e=>{if(e.isIntersecting)e.target.classList.add('visible')}),{threshold:0.12});
document.querySelectorAll('.reveal').forEach(el=>io.observe(el));
const paw=document.getElementById('paw');let ptTimer=0;
window.addEventListener('mousemove',e=>{
if(window.innerWidth<=768)return;
paw.style.left=(e.clientX-12)+'px';paw.style.top=(e.clientY+14)+'px';paw.style.opacity='0.85';
clearTimeout(ptTimer);ptTimer=setTimeout(()=>paw.style.opacity='0',400);
});
// ===== Map =====
const cities=[
{name:'Beijing',lat:39.9042,lng:116.4074,desc:'Headquarters · Healing Living Room',addr:'Dongcheng District · Vintage alleyway space'},
{name:'Shanghai',lat:31.2304,lng:121.4737,desc:'Collaboration Studio',addr:'Jing\'an District · French Concession garden house'},
{name:'Chengdu',lat:30.5728,lng:104.0668,desc:'Therapy Dog Training Base',addr:'Qingyang District · Courtyard training field'},
{name:'Shenzhen',lat:22.5431,lng:114.0579,desc:'Creative Content Studio',addr:'Nanshan District · Renovated seafront factory'},
{name:'Guangzhou',lat:23.1291,lng:113.2644,desc:'AAI Hospital Partner',addr:'Yuexiu District · Pediatric ward'},
{name:'Hangzhou',lat:30.2741,lng:120.1551,desc:'Seasonal Pop-up Point',addr:'West Lake District · Mountain retreat'}
];
const catPawSVG=`<svg viewBox="0 0 64 64" xmlns="http://www.w3.org/2000/svg" width="30" height="30"><g fill="#9C4A2A" stroke="#5e2e1a" stroke-width="0.8"><path d="M32 44c-8 0-12-4-12-9 0-4 3-7 6-8 1 0 3-0.5 6-0.5 3 0 5 0.5 6 0.5 3 1 6 4 6 8 0 5-4 9-12 9z"/><ellipse cx="20" cy="28" rx="4.5" ry="6"/><ellipse cx="44" cy="28" rx="4.5" ry="6"/><ellipse cx="27" cy="20" rx="4" ry="5.5"/><ellipse cx="37" cy="20" rx="4" ry="5.5"/></g></svg>`;
const map=L.map('vintageMap',{maxBounds:L.latLngBounds([[-60,-30],[80,240]]),maxBoundsViscosity:1}).setView([35,108],5);
L.tileLayer('https://{s}.basemaps.cartocdn.com/light_all/{z}/{x}/{y}{r}.png',{attribution:'© OSM & CartoDB',subdomains:'abcd',maxZoom:12,minZoom:4}).addTo(map);
cities.forEach(c=>{
L.circle([c.lat,c.lng],{color:'#C89F6E',weight:1.5,fillColor:'#E0BB84',fillOpacity:.25,radius:60000,interactive:false}).addTo(map);
const icon=L.divIcon({className:'paw-marker',html:`<div style="width:44px;height:44px;display:flex;align-items:center;justify-content:center;background:#FDF8EE;border:2px solid #9C4A2A;border-radius:50%;box-shadow:2px 2px 0 rgba(59,42,30,.25);">${catPawSVG}</div>`,iconSize:[44,44],iconAnchor:[22,22],popupAnchor:[0,-24]});
L.marker([c.lat,c.lng],{icon}).addTo(map).bindPopup(`<div class="pop-name">◈ ${c.name}</div><div class="pop-desc">${c.desc}</div><div class="pop-addr">${c.addr}</div>`,{maxWidth:240,autoPan:true,keepInView:true,autoPanPadding:[20,20]});
});
window.addEventListener('resize',()=>setTimeout(()=>map.invalidateSize(),100));
window.addEventListener('load',()=>setTimeout(()=>map.invalidateSize(),200));
const mc=document.getElementById('vintageMap');
if(mc){new ResizeObserver(()=>map.invalidateSize()).observe(mc)}
const tagWrap=document.getElementById('cityTags');
cities.forEach(c=>{const t=document.createElement('span');t.className='tag';t.textContent='◈ '+c.name+' · '+c.desc;tagWrap.appendChild(t)});
</script>
</body>
</html>
