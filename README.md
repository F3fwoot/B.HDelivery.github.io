# B.HDelivery.github.io
B.HDelivery 

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="description" content="B.H Delivery — Professional courier and logistics services across California and all 50 states. Medical, legal, freight, parcel, food, and retail delivery. Headquartered in Fullerton, CA.">
<title>B.H Delivery — Courier &amp; Logistics Services | California &amp; All 50 States</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@400;500;600;700&family=Inter:wght@400;500;600&family=JetBrains+Mono:wght@400;500&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@tabler/icons-webfont@2.44.0/tabler-icons.min.css">
<style>
/* ===================================================
   RESET & TOKENS
=================================================== */
*,*::before,*::after{margin:0;padding:0;box-sizing:border-box;}
html{scroll-behavior:smooth;font-size:16px;}
body{
  font-family:'Inter',system-ui,sans-serif;
  background:#F5F3EE;
  color:#0F1B2D;
  line-height:1.65;
  -webkit-font-smoothing:antialiased;
  -moz-osx-font-smoothing:grayscale;
}
h1,h2,h3,h4,h5{
  font-family:'Space Grotesk',sans-serif;
  letter-spacing:-0.02em;
  line-height:1.1;
}
a{color:inherit;text-decoration:none;}
img{max-width:100%;display:block;}
:root{
  --ink:       #0F1B2D;
  --ink-soft:  #1E3045;
  --steel:     #24425F;
  --steel-soft:#3A5B7D;
  --amber:     #E8871E;
  --amber-dark:#C46E10;
  --amber-glow:rgba(232,135,30,.15);
  --paper:     #F5F3EE;
  --paper-dim: #EBE7DD;
  --muted:     #5C6773;
  --border:    #D8D3C7;
  --border-dark:rgba(255,255,255,.1);
  --white:     #FFFFFF;
  --green:     #22C55E;
  --radius:    8px;
  --radius-lg: 14px;
  --shadow-sm: 0 1px 3px rgba(0,0,0,.06),0 1px 2px rgba(0,0,0,.04);
  --shadow-md: 0 4px 16px rgba(0,0,0,.08);
  --shadow-lg: 0 12px 40px rgba(0,0,0,.12);
}
:focus-visible{outline:2px solid var(--amber);outline-offset:3px;border-radius:3px;}
@media(prefers-reduced-motion:reduce){*{animation-duration:.01ms!important;transition-duration:.01ms!important;}}

/* ===================================================
   UTILITIES
=================================================== */
.wrap{max-width:1160px;margin:0 auto;padding:0 28px;}
.section{padding:96px 0;}
.eyebrow{
  display:inline-flex;align-items:center;gap:10px;
  font-family:'JetBrains Mono',monospace;
  font-size:11.5px;letter-spacing:0.18em;
  color:var(--amber);text-transform:uppercase;
  margin-bottom:18px;
}
.eyebrow::before{content:"";width:24px;height:1.5px;background:currentColor;display:inline-block;flex-shrink:0;}
.btn{
  display:inline-flex;align-items:center;justify-content:center;gap:8px;
  padding:12px 26px;border-radius:var(--radius);
  font-family:'Space Grotesk',sans-serif;
  font-weight:600;font-size:14.5px;
  border:1.5px solid transparent;
  cursor:pointer;transition:all .18s ease;
  white-space:nowrap;text-decoration:none;
}
.btn-amber{background:var(--amber);color:var(--ink);border-color:var(--amber);}
.btn-amber:hover{background:var(--amber-dark);border-color:var(--amber-dark);transform:translateY(-1px);box-shadow:0 4px 12px rgba(232,135,30,.35);}
.btn-outline{border-color:var(--steel);color:var(--steel);}
.btn-outline:hover{border-color:var(--ink);color:var(--ink);background:rgba(0,0,0,.03);}
.btn-ghost{border-color:rgba(255,255,255,.3);color:#fff;}
.btn-ghost:hover{border-color:rgba(255,255,255,.7);background:rgba(255,255,255,.08);}

/* ===================================================
   UTILITY BAR
=================================================== */
.utility-bar{
  background:var(--ink);
  border-bottom:1px solid rgba(255,255,255,.06);
  font-family:'JetBrains Mono',monospace;
  font-size:11.5px;letter-spacing:0.04em;
  color:#7A8FA0;
}
.utility-bar .wrap{
  display:flex;justify-content:space-between;align-items:center;
  padding-top:8px;padding-bottom:8px;gap:12px;flex-wrap:wrap;
}
.utility-bar .u-left{display:flex;align-items:center;gap:6px;}
.utility-bar .u-left .dot-label{color:#C0CAD4;letter-spacing:.1em;}
.u-right a{
  color:var(--green);letter-spacing:.08em;
  display:inline-flex;align-items:center;gap:6px;
}
.u-right a::before{
  content:"";width:7px;height:7px;border-radius:50%;
  background:var(--green);box-shadow:0 0 0 3px rgba(34,197,94,.2);
  display:inline-block;animation:blink 1.8s ease-in-out infinite;
}
@keyframes blink{0%,100%{opacity:1}50%{opacity:.4}}

/* ===================================================
   NAVIGATION
=================================================== */
header.main-nav{
  background:var(--paper);
  border-bottom:1px solid var(--border);
  position:sticky;top:0;z-index:100;
  transition:box-shadow .2s ease;
}
header.main-nav.scrolled{box-shadow:0 2px 20px rgba(0,0,0,.07);}
.nav-inner{
  display:flex;align-items:center;justify-content:space-between;
  padding:14px 28px;gap:24px;
}
.wordmark{display:flex;align-items:center;gap:12px;}
.wordmark img{height:38px;width:auto;}
.wordmark-text{
  font-family:'Space Grotesk',sans-serif;
  font-weight:700;font-size:18px;
  letter-spacing:-0.01em;line-height:1.1;
  color:var(--ink);
}
.wordmark-text small{
  display:block;
  font-family:'JetBrains Mono',monospace;
  font-weight:400;font-size:9px;
  letter-spacing:0.16em;color:var(--muted);
  margin-top:2px;
}
nav.links{display:flex;align-items:center;gap:30px;}
nav.links a{
  font-size:14px;font-weight:500;
  color:var(--steel);padding:4px 0;
  position:relative;transition:color .15s;
}
nav.links a:hover{color:var(--ink);}
nav.links a::after{
  content:"";position:absolute;bottom:-2px;left:0;
  width:0;height:2px;background:var(--amber);
  border-radius:2px;transition:width .2s ease;
}
nav.links a:hover::after,nav.links a.active::after{width:100%;}
nav.links a.active{color:var(--ink);}
.nav-cta{display:flex;align-items:center;gap:12px;}
.menu-toggle{
  display:none;background:none;border:none;
  cursor:pointer;padding:6px;border-radius:4px;
}
.menu-toggle span{
  display:block;width:22px;height:2px;
  background:var(--ink);margin:5px 0;border-radius:2px;
  transition:all .2s ease;
}

/* ===================================================
   HERO
=================================================== */
.hero{
  background:
    linear-gradient(140deg,rgba(9,19,31,.94) 0%,rgba(15,27,45,.85) 55%,rgba(36,66,95,.78) 100%),
    url('https://images.unsplash.com/photo-1586528116311-ad8dd3c8310d?w=1800&q=85&auto=format&fit=crop') center/cover no-repeat;
  color:var(--white);
  position:relative;overflow:hidden;
}
.hero::before{
  content:"";position:absolute;inset:0;
  background-image:
    linear-gradient(rgba(232,135,30,.05) 1px,transparent 1px),
    linear-gradient(90deg,rgba(232,135,30,.05) 1px,transparent 1px);
  background-size:52px 52px;pointer-events:none;
}
.hero::after{
  content:"";position:absolute;
  top:-160px;right:-120px;
  width:620px;height:620px;border-radius:50%;
  background:radial-gradient(circle,rgba(232,135,30,.16) 0%,transparent 68%);
  pointer-events:none;
}
.hero-orb{
  position:absolute;bottom:-80px;left:-120px;
  width:480px;height:480px;border-radius:50%;
  background:radial-gradient(circle,rgba(36,66,95,.45) 0%,transparent 68%);
  pointer-events:none;z-index:0;
}
.hero .wrap{
  display:grid;grid-template-columns:1.1fr 0.9fr;
  gap:56px;align-items:center;
  padding-top:96px;padding-bottom:104px;
  position:relative;z-index:1;
}
.hero h1{
  font-size:clamp(38px,4.8vw,60px);
  font-weight:700;letter-spacing:-0.025em;
  line-height:1.05;margin-bottom:22px;
  color:#FFFFFF;
}
.hero h1 span{color:var(--amber);}
.hero .lede{
  font-size:16.5px;line-height:1.7;
  color:#B8C8D8;max-width:480px;margin-bottom:36px;
}
.hero-actions{display:flex;align-items:center;gap:20px;flex-wrap:wrap;}
.live-badge{
  display:inline-flex;align-items:center;gap:8px;
  font-family:'JetBrains Mono',monospace;
  font-size:12px;color:#8BAFC8;
}
.live-dot{
  width:8px;height:8px;border-radius:50%;
  background:var(--green);flex-shrink:0;
  box-shadow:0 0 0 3px rgba(34,197,94,.2);
  animation:blink 1.8s ease-in-out infinite;
}

/* Dispatch widget */
.dispatch-widget{display:flex;flex-direction:column;gap:14px;}
.dispatch-card{
  background:rgba(15,27,45,.85);
  border:1px solid rgba(58,91,125,.6);
  border-radius:var(--radius-lg);
  padding:22px 24px;
  backdrop-filter:blur(8px);
}
.dispatch-label{
  font-family:'JetBrains Mono',monospace;
  font-size:10px;color:var(--amber);
  letter-spacing:.12em;margin-bottom:14px;
  text-transform:uppercase;
}
.dispatch-routes{display:flex;flex-direction:column;gap:11px;}
.dispatch-row{
  display:flex;align-items:center;gap:10px;
  font-family:'JetBrains Mono',monospace;font-size:12px;
}
.dispatch-row .route-name{color:#D0DCE8;flex:1;}
.status-en-route{color:var(--green);font-size:11px;}
.status-pickup{color:var(--amber);font-size:11px;}
.dispatch-stats{display:grid;grid-template-columns:1fr 1fr;gap:12px;}
.stat-card{
  background:rgba(15,27,45,.85);
  border:1px solid rgba(58,91,125,.6);
  border-radius:var(--radius-lg);padding:18px 20px;
  backdrop-filter:blur(8px);
}
.stat-card .sc-label{
  font-family:'JetBrains Mono',monospace;
  font-size:9.5px;color:#7A8FA0;
  letter-spacing:.1em;text-transform:uppercase;
  margin-bottom:8px;
}
.stat-card .sc-value{
  font-family:'Space Grotesk',sans-serif;
  font-size:30px;font-weight:700;color:#FFFFFF;line-height:1;
}
.stat-card .sc-value span{font-size:13px;font-weight:400;color:#7A8FA0;margin-left:2px;}
.stat-card .sc-sub{font-size:12px;color:var(--green);margin-top:5px;}
.stat-card .sc-sub.neutral{color:#7A8FA0;}

/* ===================================================
   WHY SECTION
=================================================== */
.why{
  background:var(--paper);
  position:relative;overflow:hidden;
}
.why::before{
  content:"";position:absolute;inset:0;
  background-image:radial-gradient(var(--border) 1.2px,transparent 1.2px);
  background-size:26px 26px;opacity:.7;pointer-events:none;
}
.why .wrap{
  display:grid;grid-template-columns:0.85fr 1.15fr;
  gap:64px;align-items:start;position:relative;z-index:1;
}
.why-left h2{
  font-size:clamp(28px,3.2vw,42px);
  font-weight:700;color:var(--ink);margin-bottom:16px;
}
.why-left .sub{
  font-size:15px;color:var(--muted);line-height:1.7;
}
.why-right p{
  font-size:15.5px;color:var(--muted);
  line-height:1.75;margin-bottom:22px;
}
.stat-row{
  display:grid;grid-template-columns:repeat(3,1fr);
  gap:16px;margin:28px 0 32px;
}
.stat{
  border-left:3px solid var(--amber);
  padding:10px 0 10px 16px;
  background:var(--paper-dim);
  border-radius:0 var(--radius) var(--radius) 0;
}
.stat b{
  font-family:'Space Grotesk',sans-serif;
  font-size:28px;font-weight:700;
  display:block;color:var(--ink);line-height:1.1;
}
.stat span{font-size:12px;color:var(--muted);line-height:1.4;display:block;margin-top:3px;}

/* ===================================================
   SERVICES
=================================================== */
.services{
  background:
    linear-gradient(180deg,rgba(9,19,31,.97) 0%,rgba(15,27,45,.96) 100%),
    url('https://images.unsplash.com/photo-1519003722824-194d4455a60c?w=1800&q=85&auto=format&fit=crop') center/cover no-repeat fixed;
  color:var(--white);
  position:relative;overflow:hidden;
}
.services::before{
  content:"";position:absolute;
  top:0;left:0;right:0;height:2px;
  background:linear-gradient(90deg,transparent,var(--amber) 35%,var(--amber) 65%,transparent);
}
.services::after{
  content:"";position:absolute;
  top:-180px;right:-180px;width:560px;height:560px;border-radius:50%;
  background:radial-gradient(circle,rgba(232,135,30,.08) 0%,transparent 65%);
  pointer-events:none;
}
.services .wrap{position:relative;z-index:1;}
.services .section-head h2{color:var(--white);font-size:clamp(26px,3vw,38px);}
.services .section-head p{color:#8BAFC8;font-size:15px;margin-top:10px;}
.manifest{border-top:1px solid rgba(255,255,255,.1);margin-top:40px;}
.manifest-row{
  display:grid;
  grid-template-columns:96px 1fr 170px 42px;
  align-items:center;gap:20px;
  padding:24px 4px;
  border-bottom:1px solid rgba(255,255,255,.08);
  cursor:pointer;
  border-left:3px solid transparent;
  transition:background .15s ease,border-color .15s ease;
}
.manifest-row:hover{
  background:rgba(232,135,30,.06);
  border-left-color:var(--amber);
  padding-left:10px;
}
.manifest-code{
  font-family:'JetBrains Mono',monospace;
  font-size:12.5px;color:var(--amber);letter-spacing:.05em;
}
.manifest-title{
  font-family:'Space Grotesk',sans-serif;
  font-size:19px;font-weight:600;color:#F0EDE8;
}
.manifest-tag{
  font-family:'JetBrains Mono',monospace;
  font-size:11px;color:#6E8CA8;
  text-align:right;letter-spacing:.04em;
}
.manifest-arrow{
  width:36px;height:36px;border-radius:50%;
  border:1px solid rgba(255,255,255,.2);
  display:flex;align-items:center;justify-content:center;
  transition:all .15s ease;flex-shrink:0;
}
.manifest-row:hover .manifest-arrow{
  background:var(--amber);border-color:var(--amber);
}
.manifest-row:hover .manifest-arrow svg{stroke:var(--ink);}
.manifest-arrow svg{width:15px;height:15px;stroke:#FFFFFF;}

/* ===================================================
   SERVICE MODAL
=================================================== */
.modal-overlay{
  display:none;position:fixed;inset:0;
  background:rgba(8,15,25,.8);
  backdrop-filter:blur(6px);
  z-index:300;align-items:center;justify-content:center;padding:24px;
}
.modal-overlay.open{display:flex;}
.modal-box{
  background:#0d1a2a;
  border:1px solid rgba(58,91,125,.7);
  border-radius:18px;
  max-width:500px;width:100%;
  padding:40px 36px 36px;
  position:relative;
  box-shadow:0 24px 64px rgba(0,0,0,.5);
  animation:modalIn .22s cubic-bezier(.34,1.56,.64,1);
}
@keyframes modalIn{from{opacity:0;transform:translateY(20px) scale(.97)}to{opacity:1;transform:none}}
.modal-close{
  position:absolute;top:18px;right:18px;
  background:rgba(255,255,255,.06);border:none;
  width:32px;height:32px;border-radius:50%;
  color:#6E8098;font-size:16px;cursor:pointer;
  display:flex;align-items:center;justify-content:center;
  transition:all .15s;
}
.modal-close:hover{background:rgba(255,255,255,.12);color:#fff;}
.modal-code{
  font-family:'JetBrains Mono',monospace;
  font-size:11px;color:var(--amber);
  letter-spacing:.12em;margin-bottom:10px;
}
.modal-title{
  font-family:'Space Grotesk',sans-serif;
  font-size:24px;font-weight:700;
  color:#F0EDE8;margin-bottom:10px;
}
.modal-tag{
  display:inline-block;
  font-family:'JetBrains Mono',monospace;font-size:10px;
  letter-spacing:.08em;color:#8BAFC8;
  border:1px solid rgba(58,91,125,.6);
  padding:4px 12px;border-radius:100px;margin-bottom:20px;
}
.modal-body{font-size:15px;color:#8BAFC8;line-height:1.8;}
.modal-cta{margin-top:28px;}

/* ===================================================
   WHAT SETS US APART
=================================================== */
.apart{
  background:var(--paper-dim);
  position:relative;overflow:hidden;
}
.apart::before{
  content:"";position:absolute;inset:0;
  background:repeating-linear-gradient(
    -45deg,transparent,transparent 22px,
    rgba(200,196,188,.18) 22px,rgba(200,196,188,.18) 23px
  );
  pointer-events:none;
}
.apart::after{
  content:"";position:absolute;top:0;left:0;right:0;height:3px;
  background:linear-gradient(90deg,transparent,var(--amber) 25%,var(--amber-dark) 75%,transparent);
}
.apart .wrap{position:relative;z-index:1;}
.apart h2{font-size:clamp(26px,3vw,38px);font-weight:700;color:var(--ink);}
.apart-grid{
  display:grid;grid-template-columns:repeat(4,1fr);
  gap:0;margin-top:44px;
  border:1px solid var(--border);
  border-radius:var(--radius-lg);overflow:hidden;
}
.apart-card{
  background:var(--paper-dim);
  padding:36px 28px;
  border-right:1px solid var(--border);
  transition:background .2s ease,transform .2s ease;
  position:relative;
}
.apart-card:last-child{border-right:none;}
.apart-card:hover{background:var(--paper);}
.apart-card::after{
  content:"";position:absolute;bottom:0;left:0;right:0;height:3px;
  background:var(--amber);transform:scaleX(0);
  transition:transform .2s ease;transform-origin:left;
}
.apart-card:hover::after{transform:scaleX(1);}
.apart-icon{
  width:44px;height:44px;border-radius:10px;
  background:var(--amber-glow);
  display:flex;align-items:center;justify-content:center;
  margin-bottom:20px;
}
.apart-icon svg{width:22px;height:22px;stroke:var(--amber-dark);}
.apart-card h3{font-size:16px;font-weight:600;margin-bottom:10px;color:var(--ink);}
.apart-card p{font-size:13.5px;color:var(--muted);line-height:1.65;}

/* ===================================================
   HOW IT WORKS
=================================================== */
.how-it-works{
  background:
    linear-gradient(180deg,rgba(9,19,31,.97) 0%,rgba(15,27,45,.95) 100%),
    url('https://images.unsplash.com/photo-1494412574643-ff11b0a5c1c3?w=1800&q=85&auto=format&fit=crop') center/cover no-repeat fixed;
  color:var(--white);padding:96px 0;
  position:relative;overflow:hidden;
}
.how-it-works::before{
  content:"";position:absolute;inset:0;
  background-image:
    linear-gradient(rgba(58,91,125,.1) 1px,transparent 1px),
    linear-gradient(90deg,rgba(58,91,125,.1) 1px,transparent 1px);
  background-size:60px 60px;pointer-events:none;
}
.how-it-works .wrap{position:relative;z-index:1;max-width:860px;}
.how-it-works .section-head{text-align:center;margin-bottom:64px;}
.how-it-works .section-head h2{color:#FFFFFF;font-size:clamp(26px,3vw,38px);margin-bottom:12px;}
.how-it-works .section-head p{color:#8BAFC8;font-size:15px;max-width:500px;margin:0 auto;}
.timeline{position:relative;}
.timeline-line{
  position:absolute;left:50%;top:0;bottom:0;
  width:2px;transform:translateX(-50%);
  background:linear-gradient(to bottom,transparent,rgba(58,91,125,.8) 8%,rgba(58,91,125,.8) 92%,transparent);
}
.tl-row{
  display:grid;grid-template-columns:1fr 56px 1fr;
  align-items:center;gap:0;margin-bottom:52px;
}
.tl-row:last-child{margin-bottom:0;}
.tl-content{padding:0 32px;}
.tl-content.right{text-align:right;}
.tl-step-label{
  font-family:'JetBrains Mono',monospace;
  font-size:10.5px;color:var(--amber);
  letter-spacing:.1em;margin-bottom:6px;
}
.tl-content h3{
  font-size:17px;font-weight:600;
  color:#F0EDE8;margin-bottom:6px;
}
.tl-content p{
  font-size:14px;color:#8BAFC8;line-height:1.65;
}
.tl-node{
  width:52px;height:52px;border-radius:50%;
  background:#0F1B2D;border:2px solid var(--amber);
  display:flex;align-items:center;justify-content:center;
  z-index:2;position:relative;flex-shrink:0;
  margin:0 auto;
}
.tl-node.final{background:var(--amber);}
.tl-node.final svg{stroke:#fff!important;}
.tl-node svg{width:20px;height:20px;stroke:var(--amber);stroke-width:1.8;fill:none;}
.pulse-ring{
  position:absolute;top:50%;left:50%;
  width:70px;height:70px;border-radius:50%;
  border:1px solid rgba(232,135,30,.3);
  transform:translate(-50%,-50%);
  animation:ringPulse 2.2s ease-out infinite;
  pointer-events:none;
}
@keyframes ringPulse{
  0%{transform:translate(-50%,-50%) scale(.8);opacity:.9}
  100%{transform:translate(-50%,-50%) scale(1.5);opacity:0}
}

/* ===================================================
   CTA STRIP
=================================================== */
.cta-strip{
  background:
    linear-gradient(135deg,rgba(9,19,31,.95) 0%,rgba(26,53,80,.92) 50%,rgba(36,66,95,.92) 100%),
    url('https://images.unsplash.com/photo-1601584115197-04ecc0da31d7?w=1800&q=85&auto=format&fit=crop') center/cover no-repeat;
  color:var(--white);
  text-align:center;padding:96px 0;
  position:relative;overflow:hidden;
}
.cta-strip::before{
  content:"";position:absolute;inset:0;
  background-image:
    linear-gradient(rgba(232,135,30,.04) 1px,transparent 1px),
    linear-gradient(90deg,rgba(232,135,30,.04) 1px,transparent 1px);
  background-size:44px 44px;pointer-events:none;
}
.cta-strip::after{
  content:"";position:absolute;
  top:50%;left:50%;transform:translate(-50%,-50%);
  width:700px;height:350px;
  background:radial-gradient(ellipse,rgba(232,135,30,.1) 0%,transparent 70%);
  pointer-events:none;
}
.cta-strip .wrap{position:relative;z-index:1;}
.cta-strip h2{
  font-size:clamp(26px,3.2vw,40px);
  font-weight:700;margin-bottom:16px;
}
.cta-strip p{
  font-size:16px;color:#8BAFC8;
  max-width:520px;margin:0 auto 36px;line-height:1.7;
}
.cta-actions{display:flex;gap:16px;justify-content:center;flex-wrap:wrap;}

/* ===================================================
   FOOTER
=================================================== */
footer{
  background:var(--ink);
  color:#8BAFC8;
  padding:72px 0 32px;
  border-top:3px solid transparent;
  border-image:linear-gradient(90deg,transparent,var(--amber) 30%,var(--steel-soft) 70%,transparent) 1;
}
.footer-grid{
  display:grid;
  grid-template-columns:1.5fr 1fr 1fr 1.2fr;
  gap:44px;margin-bottom:56px;
}
.footer-brand .wordmark{margin-bottom:16px;}
.footer-brand .wordmark img{height:38px;}
.footer-brand .wordmark-text{color:#D8D3C7;}
.footer-brand .wordmark-text small{color:#5C7080;}
.footer-brand p{
  font-size:13.5px;line-height:1.7;
  color:#5C7080;max-width:220px;
}
.footer-col h4{
  font-family:'Space Grotesk',sans-serif;
  font-size:13px;font-weight:600;
  color:#D0D8E0;letter-spacing:.06em;
  text-transform:uppercase;margin-bottom:18px;
}
.footer-col ul{list-style:none;}
.footer-col ul li{margin-bottom:10px;}
.footer-col ul li a{
  font-size:14px;color:#5C7080;
  transition:color .15s;
}
.footer-col ul li a:hover{color:var(--amber);}
.footer-col .contact-item{
  display:flex;gap:10px;margin-bottom:12px;
  font-size:14px;color:#5C7080;
}
.footer-col .contact-item strong{color:#8BAFC8;display:block;font-size:12px;margin-bottom:2px;}
.footer-bottom{
  border-top:1px solid rgba(255,255,255,.07);
  padding-top:24px;
  display:flex;justify-content:space-between;
  align-items:center;flex-wrap:wrap;gap:12px;
  font-family:'JetBrains Mono',monospace;
  font-size:11.5px;color:#3D5068;
}
.footer-bottom a{color:#3D5068;transition:color .15s;}
.footer-bottom a:hover{color:var(--amber);}

/* ===================================================
   SECTION DIVIDER
=================================================== */
.section-divider{
  height:1px;
  background:linear-gradient(90deg,transparent,var(--amber) 40%,var(--amber) 60%,transparent);
}

/* ===================================================
   RESPONSIVE
=================================================== */
@media(max-width:1024px){
  .apart-grid{grid-template-columns:repeat(2,1fr);}
  .apart-card{border-bottom:1px solid var(--border);}
  .apart-card:nth-child(2){border-right:none;}
}
@media(max-width:768px){
  .hero .wrap{grid-template-columns:1fr;padding-top:64px;padding-bottom:72px;gap:40px;}
  .why .wrap{grid-template-columns:1fr;gap:36px;}
  .stat-row{grid-template-columns:repeat(3,1fr);}
  nav.links{display:none;}
  .menu-toggle{display:block;}
  .footer-grid{grid-template-columns:1fr 1fr;}
  .manifest-row{grid-template-columns:72px 1fr 32px;}
  .manifest-tag{display:none;}
  .tl-row{grid-template-columns:1fr 44px 1fr;}
  .tl-content{padding:0 16px;}
  .apart-grid{grid-template-columns:1fr;}
  .apart-card{border-right:none!important;}
}
@media(max-width:480px){
  .wrap{padding:0 18px;}
  .stat-row{grid-template-columns:1fr 1fr;}
  .footer-grid{grid-template-columns:1fr;}
  .hero h1{font-size:34px;}
  .tl-content p{display:none;}
}
</style>
</head>
<body>

<!-- Utility bar -->
<div class="utility-bar">
  <div class="wrap">
    <div class="u-left">
      <span class="dot-label">FULLERTON, CALIFORNIA</span>
    </div>
    <div class="u-right">
      <a href="#quote">24/7 DISPATCH ACTIVE</a>
    </div>
  </div>
</div>

<!-- Navigation -->
<header class="main-nav" id="main-header">
  <div class="nav-inner wrap">
    <a href="#" class="wordmark" aria-label="B.H Delivery — Home">
      <img src="data:image/png;base64,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" alt="B.H Delivery logo" style="height:38px;width:auto;">
      <span class="wordmark-text">B.H DELIVERY<small>COURIER &amp; LOGISTICS &middot; 50 STATES</small></span>
    </a>
    <nav class="links" aria-label="Main navigation">
      <a href="#services">Services</a>
      <a href="#apart">Why Us</a>
      <a href="#how">How It Works</a>
      <a href="#quote">Contact</a>
    </nav>
    <div class="nav-cta">
      <a href="#quote" class="btn btn-amber">Get a Quote</a>
      <button class="menu-toggle" aria-label="Open navigation menu">
        <span></span><span></span><span></span>
      </button>
    </div>
  </div>
</header>

<!-- Hero -->
<section class="hero" aria-label="Hero">
  <div class="hero-orb" aria-hidden="true"></div>
  <div class="wrap">
    <div>
      <div class="eyebrow">Nationwide Reach. California Roots.</div>
      <h1>Smart logistics.<br>Trusted delivery.<br><span>50&#8209;state</span> strong.</h1>
      <p class="lede">Serving Parcel Services, Document Courier Services, Medical Courier Services, Food Courier Services, Retail Courier Services &amp; Freight Courier Services — across California and all 50 states.</p>
      <div class="hero-actions">
        <a href="#quote" class="btn btn-amber">Partner With Us</a>
        <div class="live-badge">
          <span class="live-dot" aria-hidden="true"></span>
          24/7 Dispatch &mdash; Routes Active Now
        </div>
      </div>
    </div>
    <div class="dispatch-widget" aria-label="Live dispatch status">
      <div class="dispatch-card">
        <div class="dispatch-label">Live Dispatch Status</div>
        <div class="dispatch-routes">
          <div class="dispatch-row">
            <span style="width:8px;height:8px;border-radius:50%;background:var(--green);flex-shrink:0;box-shadow:0 0 6px var(--green);animation:blink 1.5s infinite;" aria-hidden="true"></span>
            <span class="route-name">Route 1 &mdash; California Statewide</span>
            <span class="status-en-route">EN ROUTE</span>
          </div>
          <div class="dispatch-row">
            <span style="width:8px;height:8px;border-radius:50%;background:var(--green);flex-shrink:0;box-shadow:0 0 6px var(--green);animation:blink 1.5s infinite .3s;" aria-hidden="true"></span>
            <span class="route-name">Route 2 &mdash; Southwest Region</span>
            <span class="status-en-route">EN ROUTE</span>
          </div>
          <div class="dispatch-row">
            <span style="width:8px;height:8px;border-radius:50%;background:var(--amber);flex-shrink:0;box-shadow:0 0 6px var(--amber);" aria-hidden="true"></span>
            <span class="route-name">Route 3 &mdash; National Corridor</span>
            <span class="status-pickup">PICKUP</span>
          </div>
        </div>
      </div>
      <div class="dispatch-stats">
        <div class="stat-card">
          <div class="sc-label">Today&rsquo;s Runs</div>
          <div class="sc-value">24</div>
          <div class="sc-sub">&uarr; All on time</div>
        </div>
        <div class="stat-card">
          <div class="sc-label">Avg. Delivery</div>
          <div class="sc-value">47<span>min</span></div>
          <div class="sc-sub neutral">Across all routes</div>
        </div>
      </div>
    </div>
  </div>
</section>

<div class="section-divider" aria-hidden="true"></div>

<!-- Why Us -->
<section class="why section" id="why">
  <div class="wrap">
    <div class="why-left">
      <div class="eyebrow">Why B.H Delivery</div>
      <h2>California&#8209;based.<br>Nationwide&#8209;capable.</h2>
      <p class="sub" style="margin-top:16px;">Built to deliver anywhere — with the responsiveness of a local team and the reach of a national carrier.</p>
    </div>
    <div class="why-right">
      <p>B.H Delivery is headquartered in Fullerton, California, and built to move shipments beyond state lines. Whether you need time-critical legal documents delivered across the state or medical freight coordinated on a national corridor, our dispatch team handles every mile with the same standard of care.</p>
      <p>With coverage across all 50 states and a dedicated California operation, you get a single, trusted logistics partner — from your first call to the final signature.</p>
      <div class="stat-row">
        <div class="stat">
          <b>6+</b>
          <span>Years of dispatch experience</span>
        </div>
        <div class="stat">
          <b>50</b>
          <span>States covered nationwide</span>
        </div>
        <div class="stat">
          <b>24/7</b>
          <span>Live dispatch &amp; support</span>
        </div>
      </div>
      <a href="#quote" class="btn btn-outline">Contact Our Team</a>
    </div>
  </div>
</section>

<!-- Services -->
<section class="services section" id="services" aria-label="Our services">
  <div class="wrap">
    <div class="section-head">
      <div class="eyebrow">Our Services</div>
      <h2>One platform. Every route.<br>Anywhere in the country.</h2>
      <p>From California&rsquo;s busiest corridors to coast-to-coast freight runs — every service is dispatched, tracked, and delivered with the same disciplined process. Click any service to learn more.</p>
    </div>
    <div class="manifest" role="list">
      <div class="manifest-row" role="listitem button" tabindex="0" aria-label="Learn more about Scheduled Delivery" onclick="openModal('SCH-01','Scheduled Delivery','RECURRING ROUTES','Need a pickup every Monday at 9 AM, or daily runs between the same locations? Our Scheduled Delivery service locks in your route so you never have to call again. We build a recurring dispatch plan around your business hours, volume, and delivery windows — and we show up every time, without reminders.')">
        <div class="manifest-code">SCH&#8209;01</div>
        <div class="manifest-title">Scheduled Delivery</div>
        <div class="manifest-tag">RECURRING ROUTES</div>
        <div class="manifest-arrow"><svg viewBox="0 0 24 24" fill="none"><path d="M5 12h14M13 6l6 6-6 6" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/></svg></div>
      </div>
      <div class="manifest-row" role="listitem button" tabindex="0" aria-label="Learn more about Medical Delivery" onclick="openModal('MED-02','Medical Delivery','CHAIN OF CUSTODY','Medical deliveries require more than speed — they require precision. B.H Delivery handles lab specimens, prescriptions, medical devices, and sensitive health documents with strict chain-of-custody protocols. Every run is tracked, temperature-aware, and handled by trained couriers who understand the stakes.')">
        <div class="manifest-code">MED&#8209;02</div>
        <div class="manifest-title">Medical Delivery</div>
        <div class="manifest-tag">CHAIN OF CUSTODY</div>
        <div class="manifest-arrow"><svg viewBox="0 0 24 24" fill="none"><path d="M5 12h14M13 6l6 6-6 6" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/></svg></div>
      </div>
      <div class="manifest-row" role="listitem button" tabindex="0" aria-label="Learn more about Legal Delivery" onclick="openModal('LEG-03','Legal Delivery','SAME-DAY FILING','Missed court deadlines are not an option. Our Legal Delivery service is built for law firms, courts, and title companies that need same-day document filing, process serving, and contract delivery. We handle time-stamped pickups, secure chain of custody, and rush delivery across California and nationwide.')">
        <div class="manifest-code">LEG&#8209;03</div>
        <div class="manifest-title">Legal Delivery</div>
        <div class="manifest-tag">SAME&#8209;DAY FILING</div>
        <div class="manifest-arrow"><svg viewBox="0 0 24 24" fill="none"><path d="M5 12h14M13 6l6 6-6 6" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/></svg></div>
      </div>
      <div class="manifest-row" role="listitem button" tabindex="0" aria-label="Learn more about Freight and Warehousing" onclick="openModal('FRT-04','Freight & Warehousing','SECURE STORAGE','Moving larger loads? B.H Delivery provides freight transport and secure warehousing for businesses that need more than a courier van. From pallet pickups to racked storage with flexible fulfillment, we handle the heavy lifting — with the same real-time tracking and accountability as every other service we offer.')">
        <div class="manifest-code">FRT&#8209;04</div>
        <div class="manifest-title">Freight &amp; Warehousing</div>
        <div class="manifest-tag">SECURE STORAGE</div>
        <div class="manifest-arrow"><svg viewBox="0 0 24 24" fill="none"><path d="M5 12h14M13 6l6 6-6 6" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/></svg></div>
      </div>
      <div class="manifest-row" role="listitem button" tabindex="0" aria-label="Learn more about Parcel Services" onclick="openModal('PCL-05','Parcel Services','DOOR-TO-DOOR','Fast, reliable parcel delivery for businesses and individuals across California and all 50 states. Whether it is a single package or a high-volume daily shipment, we pick it up at your door and deliver it directly to the recipient — tracked every mile of the way. No drop-off lines, no wait times.')">
        <div class="manifest-code">PCL&#8209;05</div>
        <div class="manifest-title">Parcel Services</div>
        <div class="manifest-tag">DOOR&#8209;TO&#8209;DOOR</div>
        <div class="manifest-arrow"><svg viewBox="0 0 24 24" fill="none"><path d="M5 12h14M13 6l6 6-6 6" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/></svg></div>
      </div>
      <div class="manifest-row" role="listitem button" tabindex="0" aria-label="Learn more about Food Courier Services" onclick="openModal('FOD-06','Food Courier Services','TEMP-CONTROLLED','From restaurant meal kits to wholesale food distribution, our Food Courier service keeps your products fresh from origin to destination. We use temperature-controlled vehicles and timed delivery windows to protect perishables and ensure your customers receive food exactly the way it was meant to arrive.')">
        <div class="manifest-code">FOD&#8209;06</div>
        <div class="manifest-title">Food Courier Services</div>
        <div class="manifest-tag">TEMP&#8209;CONTROLLED</div>
        <div class="manifest-arrow"><svg viewBox="0 0 24 24" fill="none"><path d="M5 12h14M13 6l6 6-6 6" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/></svg></div>
      </div>
      <div class="manifest-row" role="listitem button" tabindex="0" aria-label="Learn more about Retail Courier Services" onclick="openModal('RTL-07','Retail Courier Services','B2B & B2C','Retail moves fast — and so do we. B.H Delivery supports retail businesses with same-day and next-day delivery of products directly to customers or between store locations. Whether you are fulfilling online orders, restocking shelves, or running B2B transfers, our retail courier service keeps your supply chain moving.')">
        <div class="manifest-code">RTL&#8209;07</div>
        <div class="manifest-title">Retail Courier Services</div>
        <div class="manifest-tag">B2B &amp; B2C</div>
        <div class="manifest-arrow"><svg viewBox="0 0 24 24" fill="none"><path d="M5 12h14M13 6l6 6-6 6" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/></svg></div>
      </div>
    </div>
  </div>
</section>

<div class="section-divider" aria-hidden="true"></div>

<!-- What Sets Us Apart -->
<section class="apart section" id="apart" aria-label="What sets us apart">
  <div class="wrap">
    <div class="section-head">
      <div class="eyebrow">What Sets Us Apart</div>
      <h2>Built for California. Scaled for the nation.</h2>
    </div>
    <div class="apart-grid">
      <div class="apart-card">
        <div class="apart-icon"><svg viewBox="0 0 24 24" fill="none" stroke-width="1.8"><path d="M21 10c0 7-9 13-9 13s-9-6-9-13a9 9 0 0118 0z"/><circle cx="12" cy="10" r="3"/></svg></div>
        <h3>Statewide California Coverage</h3>
        <p>Deep operational roots across California — from the Bay Area to the border — with the local expertise to navigate every route efficiently.</p>
      </div>
      <div class="apart-card">
        <div class="apart-icon"><svg viewBox="0 0 24 24" fill="none" stroke-width="1.8"><rect x="2" y="3" width="20" height="14" rx="2"/><path d="M8 21h8M12 17v4"/></svg></div>
        <h3>Advanced Tracking Technology</h3>
        <p>Real-time GPS tracking, digital proof of delivery, and web-based scheduling keep you informed from pickup to final drop — anywhere in the country.</p>
      </div>
      <div class="apart-card">
        <div class="apart-icon"><svg viewBox="0 0 24 24" fill="none" stroke-width="1.8"><circle cx="12" cy="12" r="9"/><path d="M12 7v5l3 3"/></svg></div>
        <h3>Reliable &amp; On Time</h3>
        <p>Whether it&rsquo;s a same-day California run or a multi-state corridor, our dispatch team ensures every shipment arrives on schedule — no exceptions.</p>
      </div>
      <div class="apart-card">
        <div class="apart-icon"><svg viewBox="0 0 24 24" fill="none" stroke-width="1.8"><path d="M3 9l9-7 9 7v11a2 2 0 01-2 2H5a2 2 0 01-2-2z"/><polyline points="9 22 9 12 15 12 15 22"/></svg></div>
        <h3>50-State Reach</h3>
        <p>Licensed and insured to operate across all 50 states — giving your business a single, trusted carrier for both local California deliveries and nationwide freight.</p>
      </div>
    </div>
  </div>
</section>

<!-- How It Works -->
<section class="how-it-works" id="how" aria-label="How it works">
  <div class="wrap">
    <div class="section-head">
      <div class="eyebrow" style="justify-content:center;">How It Works</div>
      <h2>From California to every state &mdash; every time.</h2>
      <p>Six steps. Zero guesswork. Whether your shipment stays in California or crosses the country, B.H Delivery handles every mile with precision — from your first call to the final signature.</p>
    </div>
    <div class="timeline">
      <div class="timeline-line" aria-hidden="true"></div>
      <div class="tl-row">
        <div class="tl-content right">
          <div class="tl-step-label">STEP 01</div>
          <h3>Request Placed</h3>
          <p>Call, text, or submit online. Our dispatch team responds immediately — no hold music, no automated menus.</p>
        </div>
        <div class="tl-node">
          <div class="pulse-ring" aria-hidden="true"></div>
          <svg viewBox="0 0 24 24"><path d="M22 16.92v3a2 2 0 01-2.18 2 19.79 19.79 0 01-8.63-3.07A19.5 19.5 0 013.07 9.8 19.79 19.79 0 01.22 1.18 2 2 0 012.18 0h3a2 2 0 012 1.72c.13.96.36 1.9.7 2.81a2 2 0 01-.45 2.11L6.09 7.91a16 16 0 006 6l1.27-1.27a2 2 0 012.11-.45c.91.34 1.85.57 2.81.7A2 2 0 0122 16.92z"/></svg>
        </div>
        <div></div>
      </div>
      <div class="tl-row">
        <div></div>
        <div class="tl-node">
          <svg viewBox="0 0 24 24"><circle cx="12" cy="12" r="3"/><path d="M12 1v4M12 19v4M4.22 4.22l2.83 2.83M16.95 16.95l2.83 2.83M1 12h4M19 12h4M4.22 19.78l2.83-2.83M16.95 7.05l2.83-2.83"/></svg>
        </div>
        <div class="tl-content">
          <div class="tl-step-label">STEP 02</div>
          <h3>Driver Assigned</h3>
          <p>The nearest available driver is dispatched within minutes. Your ETA is confirmed before they leave the depot.</p>
        </div>
      </div>
      <div class="tl-row">
        <div class="tl-content right">
          <div class="tl-step-label">STEP 03</div>
          <h3>Package Picked Up</h3>
          <p>Your driver arrives, verifies the item, and secures it for transport. Chain of custody begins here.</p>
        </div>
        <div class="tl-node">
          <svg viewBox="0 0 24 24"><path d="M21 10c0 7-9 13-9 13s-9-6-9-13a9 9 0 0118 0z"/><circle cx="12" cy="10" r="3"/></svg>
        </div>
        <div></div>
      </div>
      <div class="tl-row">
        <div></div>
        <div class="tl-node">
          <svg viewBox="0 0 24 24"><rect x="1" y="3" width="15" height="13" rx="1"/><path d="M16 8h4l3 3v5h-7V8z"/><circle cx="5.5" cy="18.5" r="2.5"/><circle cx="18.5" cy="18.5" r="2.5"/></svg>
        </div>
        <div class="tl-content">
          <div class="tl-step-label">STEP 04</div>
          <h3>Live GPS Tracking</h3>
          <p>Your shipment is tracked in real time from pickup to delivery. No black holes, no surprises — just visibility.</p>
        </div>
      </div>
      <div class="tl-row">
        <div class="tl-content right">
          <div class="tl-step-label">STEP 05</div>
          <h3>Delivered &amp; Verified</h3>
          <p>The recipient signs on delivery. Proof of delivery is logged instantly and available on request.</p>
        </div>
        <div class="tl-node">
          <svg viewBox="0 0 24 24"><polyline points="20 6 9 17 4 12"/></svg>
        </div>
        <div></div>
      </div>
      <div class="tl-row">
        <div></div>
        <div class="tl-node final">
          <svg viewBox="0 0 24 24"><path d="M14 2H6a2 2 0 00-2 2v16a2 2 0 002 2h12a2 2 0 002-2V8z"/><polyline points="14 2 14 8 20 8"/><line x1="16" y1="13" x2="8" y2="13"/><line x1="16" y1="17" x2="8" y2="17"/></svg>
        </div>
        <div class="tl-content">
          <div class="tl-step-label">STEP 06</div>
          <h3>Confirmation Sent</h3>
          <p>You receive a full delivery confirmation with a timestamp and signature. Your records are always complete.</p>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- CTA -->
<section class="cta-strip" id="quote" aria-label="Contact us">
  <div class="wrap">
    <div class="eyebrow" style="justify-content:center;">Ready to Ship?</div>
    <h2>One carrier. Every state.<br>Zero compromise.</h2>
    <p>Whether you need a one-time pickup, recurring routes, or a fully managed logistics solution — our dispatch team is ready to build a plan around your schedule.</p>
    <div class="cta-actions">
      <a href="tel:2102289772" class="btn btn-amber">Call Us Now</a>
      <a href="mailto:info@bhdelivery.com" class="btn btn-ghost">Email Us Directly</a>
    </div>
  </div>
</section>

<!-- Footer -->
<footer>
  <div class="wrap">
    <div class="footer-grid">
      <div class="footer-brand">
        <a href="#" class="wordmark" aria-label="B.H Delivery home">
          <img src="data:image/png;base64,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" alt="B.H Delivery logo" style="height:38px;width:auto;">
          <span class="wordmark-text">B.H DELIVERY<small>COURIER &amp; LOGISTICS &middot; 50 STATES</small></span>
        </a>
        <p>Professional courier and logistics services across California and all 50 states. Headquartered in Fullerton, CA.</p>
      </div>
      <div class="footer-col">
        <h4>Services</h4>
        <ul>
          <li><a href="#services">Scheduled Delivery</a></li>
          <li><a href="#services">Medical Delivery</a></li>
          <li><a href="#services">Legal Delivery</a></li>
          <li><a href="#services">Freight &amp; Warehousing</a></li>
          <li><a href="#services">Parcel Services</a></li>
          <li><a href="#services">Food Courier</a></li>
          <li><a href="#services">Retail Courier</a></li>
        </ul>
      </div>
      <div class="footer-col">
        <h4>Company</h4>
        <ul>
          <li><a href="#why">Why B.H Delivery</a></li>
          <li><a href="#how">How It Works</a></li>
          <li><a href="#apart">What Sets Us Apart</a></li>
          <li><a href="#quote">Get a Quote</a></li>
        </ul>
      </div>
      <div class="footer-col">
        <h4>Contact</h4>
        <div class="contact-item">
          <div>
            <strong>Headquarters</strong>
            2900 Madison Ave,<br>Fullerton, CA 92831
          </div>
        </div>
        <div class="contact-item">
          <div>
            <strong>Phone</strong>
            <a href="tel:2102289772" style="color:var(--amber);">(210) 228-9772</a>
          </div>
        </div>
        <div class="contact-item">
          <div>
            <strong>Email</strong>
            <a href="mailto:info@bhdelivery.com" style="color:var(--amber);">info@bhdelivery.com</a>
          </div>
        </div>
      </div>
    </div>
    <div class="footer-bottom">
      <span>&copy; 2026 B.H Delivery LLC. All rights reserved.</span>
      <span>Fullerton, California &middot; Licensed &amp; Insured &middot; 50 States</span>
    </div>
  </div>
</footer>

<!-- Service Modal -->
<div class="modal-overlay" id="serviceModal" role="dialog" aria-modal="true" aria-labelledby="modalTitle">
  <div class="modal-box">
    <button class="modal-close" onclick="closeModal()" aria-label="Close modal">&#x2715;</button>
    <div class="modal-code" id="modalCode"></div>
    <div class="modal-title" id="modalTitle"></div>
    <div class="modal-tag" id="modalTag"></div>
    <div class="modal-body" id="modalBody"></div>
    <div class="modal-cta">
      <a href="#quote" class="btn btn-amber" onclick="closeModal()">Request This Service</a>
    </div>
  </div>
</div>

<script>
// Nav scroll shadow
const header = document.getElementById('main-header');
window.addEventListener('scroll', () => {
  header.classList.toggle('scrolled', window.scrollY > 10);
}, {passive:true});

// Nav active link on scroll
const sections = document.querySelectorAll('section[id]');
const navLinks = document.querySelectorAll('nav.links a');
const observer = new IntersectionObserver((entries) => {
  entries.forEach(entry => {
    if(entry.isIntersecting){
      navLinks.forEach(a => {
        a.classList.toggle('active', a.getAttribute('href') === '#' + entry.target.id);
      });
    }
  });
}, {rootMargin:'-40% 0px -55% 0px'});
sections.forEach(s => observer.observe(s));

// Modal
function openModal(code, title, tag, desc) {
  document.getElementById('modalCode').textContent = code;
  document.getElementById('modalTitle').textContent = title;
  document.getElementById('modalTag').textContent = tag;
  document.getElementById('modalBody').textContent = desc;
  document.getElementById('serviceModal').classList.add('open');
  document.body.style.overflow = 'hidden';
}
function closeModal() {
  document.getElementById('serviceModal').classList.remove('open');
  document.body.style.overflow = '';
}
document.getElementById('serviceModal').addEventListener('click', function(e) {
  if(e.target === this) closeModal();
});
document.addEventListener('keydown', e => { if(e.key === 'Escape') closeModal(); });
document.querySelectorAll('.manifest-row').forEach(row => {
  row.addEventListener('keydown', e => {
    if(e.key === 'Enter' || e.key === ' ') { e.preventDefault(); row.click(); }
  });
});
</script>
</body>
</html>
