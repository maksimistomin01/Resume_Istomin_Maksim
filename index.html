<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Pulse — сквозная аналитика для Telegram | Считай ROMI</title>
<meta name="description" content="Считай ROMI по каждому Telegram-каналу автоматически. CPL, LTV, конверсии — без Excel. Подключение 20 минут.">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="anonymous">
<link href="https://fonts.googleapis.com/css2?family=Space+Mono:ital,wght@0,400;0,700;1,400&amp;family=Onest:wght@300;400;500;600&amp;display=swap" rel="stylesheet">
<style>

*,*::before,*::after{box-sizing:border-box;margin:0;padding:0}
:root{
  --bg:#F0EBE0;
  --green:#2D5A3D;
  --orange:#C85A1E;
  --dark:#1A2E22;
  --text:#1A2E22;
  --muted:#5A7060;
  --light:#E8E3D8;
  --border:rgba(45,90,61,0.14);
  --card:#FFFFFF;
  --card2:rgba(45,90,61,0.05);
}
html{scroll-behavior:smooth}
body{font-family:'Onest',sans-serif;background:var(--bg);color:var(--text);-webkit-font-smoothing:antialiased;overflow-x:hidden}

/* NAV */
nav{position:sticky;top:0;z-index:100;background:var(--dark);padding:0 48px;display:flex;align-items:center;justify-content:space-between;height:60px}
.logo{font-family:'Space Mono',monospace;font-size:17px;font-weight:700;color:var(--orange);letter-spacing:2px;text-decoration:none}
.nav-links{display:flex;gap:28px;list-style:none}
.nav-links a{font-family:'Onest',sans-serif;font-size:13px;color:rgba(240,235,224,0.6);text-decoration:none;transition:color .2s}
.nav-links a:hover{color:var(--bg)}
.nav-btn{background:var(--orange);color:#FFFFFF !important;border:none;border-radius:50px;padding:10px 22px;font-family:'Onest',sans-serif;font-size:13px;font-weight:600;cursor:pointer;text-decoration:none;transition:opacity .2s}
.nav-btn:hover{opacity:.88}

/* UTILS */
.sec{padding:80px 48px;border-bottom:1px solid var(--border)}
.sec-alt{background:var(--card2)}
.wrap{max-width:1200px;margin:0 auto}
.eyebrow{font-family:'Space Mono',monospace;font-size:10px;letter-spacing:3px;text-transform:uppercase;color:var(--muted);margin-bottom:10px;display:block}
h2{font-family:'Space Mono',monospace;font-size:clamp(28px,4vw,42px);font-weight:700;color:var(--text);line-height:1.1;margin-bottom:32px}
h3{font-family:'Space Mono',monospace;font-size:14px;font-weight:700;color:var(--text);margin-bottom:8px;line-height:1.4}
.bt{font-size:14px;color:var(--muted);line-height:1.7}
.divider{height:1px;background:var(--border);margin:20px 0}

/* BUTTONS */
.btn-primary{background:var(--orange);color:#FFFFFF !important;border:none;border-radius:50px;padding:14px 28px;font-family:'Onest',sans-serif;font-size:14px;font-weight:600;cursor:pointer;text-decoration:none;display:inline-block;transition:opacity .2s}
.btn-primary:hover{opacity:.88}
.btn-outline{background:transparent;color:var(--green);border:1.5px solid var(--green);border-radius:50px;padding:13px 28px;font-family:'Onest',sans-serif;font-size:14px;font-weight:500;cursor:pointer;text-decoration:none;display:inline-block;transition:background .2s,color .2s}
.btn-outline:hover{background:var(--green);color:var(--bg)}
.btn-row{display:flex;gap:12px;flex-wrap:wrap;margin-top:28px}

/* HERO */
.hero{background:var(--dark);padding:72px 48px 80px;position:relative;overflow:hidden}
.hero::before{content:'';position:absolute;top:-180px;right:-180px;width:520px;height:520px;border-radius:50%;border:1px solid rgba(200,90,30,0.1);pointer-events:none}
.hero::after{content:'';position:absolute;top:-80px;right:-80px;width:320px;height:320px;border-radius:50%;border:1px solid rgba(200,90,30,0.07);pointer-events:none}
.hero-grid{display:grid;grid-template-columns:1fr 400px;gap:64px;align-items:center;position:relative;z-index:1}
.hero-tag{font-family:'Space Mono',monospace;font-size:11px;color:rgba(240,235,224,0.4);letter-spacing:2px;margin-bottom:20px;display:block}
.hero h1{font-family:'Space Mono',monospace;font-size:clamp(36px,5vw,56px);font-weight:700;color:var(--bg);line-height:1.08;margin-bottom:16px}
.hero-urgent{font-size:15px;color:rgba(200,90,30,0.85);font-style:italic;margin-bottom:18px;line-height:1.55}
.hero-sub{font-size:15px;color:rgba(240,235,224,0.6);line-height:1.7;margin-bottom:24px}
.pills{display:flex;gap:8px;flex-wrap:wrap;margin-bottom:8px}
.pill{background:rgba(240,235,224,0.07);border:1px solid rgba(240,235,224,0.12);border-radius:50px;padding:8px 16px;font-size:12px;color:rgba(240,235,224,0.6)}
.pill strong{display:block;font-family:'Space Mono',monospace;font-size:15px;font-weight:700;color:var(--bg);line-height:1.2}
.hero .btn-row{margin-top:24px}
.hero .btn-primary{background:var(--orange)}
.hero .btn-outline{color:var(--bg);border-color:rgba(240,235,224,0.25)}
.hero .btn-outline:hover{background:rgba(240,235,224,0.1);color:var(--bg)}

/* DASH MOCK */
.dash{background:rgba(255,255,255,0.05);border:1px solid rgba(255,255,255,0.09);border-radius:14px;padding:20px}
.dash-hdr{font-family:'Space Mono',monospace;font-size:9px;letter-spacing:2px;text-transform:uppercase;color:rgba(240,235,224,0.3);margin-bottom:14px}
.dash-r{display:flex;justify-content:space-between;align-items:center;background:rgba(255,255,255,0.04);border:1px solid rgba(255,255,255,0.07);border-radius:8px;padding:11px 13px;margin-bottom:8px}
.dash-lbl{font-size:11px;color:rgba(240,235,224,0.45)}
.dash-val{font-family:'Space Mono',monospace;font-size:12px;font-weight:700;color:var(--bg)}
.dash-mets{display:grid;grid-template-columns:repeat(3,1fr);gap:6px;margin-top:10px}
.dash-met{background:rgba(255,255,255,0.04);border:1px solid rgba(255,255,255,0.06);border-radius:8px;padding:10px;text-align:center}
.dash-met-n{font-family:'Space Mono',monospace;font-size:14px;font-weight:700;color:var(--bg)}
.dash-met-l{font-size:10px;color:rgba(240,235,224,0.35);margin-top:3px}

/* GRIDS */
.g3{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
.g4{display:grid;grid-template-columns:repeat(4,1fr);gap:16px}
.g2{display:grid;grid-template-columns:1fr 1fr;gap:16px}

/* CARDS */
.card{background:var(--card);border:1px solid var(--border);border-radius:14px;padding:24px}
.card-dark{background:var(--card2);border:1px solid var(--border);border-radius:14px;padding:24px}
.card-green{background:var(--dark);border-radius:14px;padding:24px}

/* FOR WHOM */
.who-role{font-family:'Space Mono',monospace;font-size:9px;letter-spacing:2px;text-transform:uppercase;color:var(--muted);margin-bottom:12px}
.who-hook{font-size:13px;font-style:italic;font-weight:500;color:var(--text);border-left:2px solid var(--green);padding-left:12px;margin-bottom:10px;line-height:1.55}
.who-pain{font-size:13px;color:var(--muted);line-height:1.65}

/* PROBLEMS */
.prob-num{font-family:'Space Mono',monospace;font-size:40px;font-weight:700;color:rgba(45,90,61,0.12);line-height:1;margin-bottom:12px}
.prob-num-dark{font-family:'Space Mono',monospace;font-size:40px;font-weight:700;color:rgba(240,235,224,0.08);line-height:1;margin-bottom:12px}
.prob-hook{font-size:13px;font-style:italic;font-weight:600;color:var(--text);margin-bottom:10px;line-height:1.55}
.prob-hook-dark{font-size:13px;font-style:italic;font-weight:600;color:var(--bg);margin-bottom:10px;line-height:1.55}
.prob-pain{font-size:12px;color:var(--muted);line-height:1.65;margin-bottom:10px}
.prob-pain-dark{font-size:12px;color:rgba(240,235,224,0.5);line-height:1.65;margin-bottom:10px}
.prob-sting{font-family:'Space Mono',monospace;font-size:12px;font-weight:700;color:var(--green);border-top:1px solid var(--border);padding-top:10px;line-height:1.5}
.prob-sting-dark{font-family:'Space Mono',monospace;font-size:12px;font-weight:700;color:var(--orange);border-top:1px solid rgba(240,235,224,0.1);padding-top:10px;line-height:1.5}

/* STEPS */
.step-num{width:34px;height:34px;border-radius:50%;background:var(--green);color:var(--bg);display:flex;align-items:center;justify-content:center;font-family:'Space Mono',monospace;font-size:14px;font-weight:700;margin-bottom:14px}
.badge{display:inline-block;background:var(--card2);border:1px solid var(--border);border-radius:50px;padding:4px 12px;font-family:'Space Mono',monospace;font-size:10px;color:var(--green);font-weight:700;margin-top:10px}

/* DESIGNER PLACEHOLDER */
.dph{border:1.5px dashed rgba(45,90,61,0.2);border-radius:12px;padding:36px;text-align:center;margin-top:24px}
.dph-label{font-family:'Space Mono',monospace;font-size:9px;letter-spacing:2px;color:var(--orange);text-transform:uppercase;margin-bottom:6px}
.dph p{font-size:13px;color:var(--muted)}

/* FORMAT CARDS */
.fmt-tag{font-family:'Space Mono',monospace;font-size:9px;letter-spacing:2px;text-transform:uppercase;color:var(--muted);margin-bottom:10px}
.fmt-ph{border:1px dashed rgba(45,90,61,0.18);border-radius:8px;padding:18px;text-align:center;font-family:'Space Mono',monospace;font-size:10px;color:var(--muted);letter-spacing:1px;text-transform:uppercase;margin-top:12px}

/* CALC */
.calc-grid{display:grid;grid-template-columns:1fr 1fr;gap:40px;align-items:start;margin-bottom:20px}
.calc-side{background:var(--card2);border:1px solid var(--border);border-radius:14px;padding:28px}
.calc-p{font-size:14px;color:var(--muted);line-height:1.7;margin-bottom:14px}
.calc-p strong{color:var(--text);font-weight:600}
.calc-arrow{font-family:'Space Mono',monospace;font-size:13px;font-weight:700;color:var(--green)}
.calc-label{font-size:12px;color:var(--muted);margin-bottom:8px;font-family:'Space Mono',monospace;letter-spacing:1px}
.calc-val{font-family:'Space Mono',monospace;font-size:15px;font-weight:700;color:var(--text);margin:6px 0 22px}
input[type=range]{width:100%;-webkit-appearance:none;height:3px;border-radius:2px;background:var(--border);outline:none}
input[type=range]::-webkit-slider-thumb{-webkit-appearance:none;width:18px;height:18px;border-radius:50%;background:var(--green);cursor:pointer;border:2px solid var(--bg);box-shadow:0 2px 6px rgba(45,90,61,0.3)}
.results{display:grid;grid-template-columns:repeat(3,1fr);gap:12px;margin-bottom:16px}
.res-card{background:var(--dark);border-radius:14px;padding:22px;display:flex;flex-direction:column}
.res-eye{font-size:11px;color:rgba(240,235,224,0.45);line-height:1.5;margin-bottom:16px;flex:1;font-family:'Space Mono',monospace;letter-spacing:.5px}
.res-num{font-family:'Space Mono',monospace;font-size:28px;font-weight:700;color:var(--bg);line-height:1}

/* CASE */
.case-lbl{font-family:'Space Mono',monospace;font-size:9px;letter-spacing:2px;text-transform:uppercase;color:var(--muted);margin-bottom:12px}
.case-quote{border-left:3px solid var(--orange);padding-left:16px;font-style:italic;font-size:15px;color:var(--muted);line-height:1.65;margin:18px 0}

/* PRICING */
.price-card{background:var(--card);border:1px solid var(--border);border-radius:14px;padding:24px;display:flex;flex-direction:column}
.price-card.feat{border:2px solid var(--green)}
.price-pop{font-family:'Space Mono',monospace;font-size:9px;font-weight:700;background:var(--green);color:var(--bg);padding:3px 10px;border-radius:50px;margin-bottom:10px;display:inline-block;letter-spacing:1px}
.price-tier{font-family:'Space Mono',monospace;font-size:10px;letter-spacing:2px;text-transform:uppercase;color:var(--muted);margin-bottom:6px}
.price-amt{font-family:'Space Mono',monospace;font-size:28px;font-weight:700;color:var(--text);line-height:1.1}
.price-per{font-size:11px;color:var(--muted);margin-bottom:4px}
.price-disc{font-family:'Space Mono',monospace;font-size:14px;font-weight:700;color:var(--orange);margin-top:6px}
.price-sp{flex:1;min-height:16px}
.btn-green{background:var(--green);color:var(--bg);border:none;border-radius:50px;padding:11px 20px;font-family:'Onest',sans-serif;font-size:13px;font-weight:600;cursor:pointer;width:100%;margin-top:18px;text-decoration:none;display:block;text-align:center;transition:opacity .2s}
.btn-green:hover{opacity:.85}
.btn-green-outline{background:transparent;color:var(--green);border:1.5px solid var(--green);border-radius:50px;padding:10px 20px;font-family:'Onest',sans-serif;font-size:13px;font-weight:600;cursor:pointer;width:100%;margin-top:18px;text-decoration:none;display:block;text-align:center;transition:background .2s,color .2s}
.btn-green-outline:hover{background:var(--green);color:var(--bg)}
.price-fn{font-family:'Space Mono',monospace;font-size:10px;color:var(--muted);text-align:center;margin-top:18px;letter-spacing:.5px}

/* FAQ */
.faq-item{border-bottom:1px solid var(--border)}
.faq-btn{width:100%;display:flex;justify-content:space-between;align-items:center;padding:20px 0;background:none;border:none;cursor:pointer;text-align:left;gap:16px}
.faq-q{font-size:15px;font-weight:500;color:var(--text);line-height:1.4;font-family:'Onest',sans-serif}
.faq-ic{width:26px;height:26px;border:1.5px solid var(--border);border-radius:50%;display:flex;align-items:center;justify-content:center;flex-shrink:0;transition:.2s}
.faq-ic svg{width:10px;height:10px;stroke:var(--muted);fill:none;stroke-width:2.5;transition:transform .25s}
.faq-item.open .faq-ic{background:var(--green);border-color:var(--green)}
.faq-item.open .faq-ic svg{stroke:var(--bg);transform:rotate(180deg)}
.faq-body{font-size:14px;color:var(--muted);line-height:1.7;padding:0 0 20px;display:none;max-width:680px}
.faq-item.open .faq-body{display:block}

/* CTA */
.cta-sec{background:var(--dark);padding:88px 48px;text-align:center;position:relative;overflow:hidden}
.cta-ring{position:absolute;width:500px;height:500px;border-radius:50%;border:1px solid rgba(200,90,30,0.08);top:50%;left:50%;transform:translate(-50%,-50%);pointer-events:none}
.cta-ring2{position:absolute;width:320px;height:320px;border-radius:50%;border:1px solid rgba(200,90,30,0.12);top:50%;left:50%;transform:translate(-50%,-50%);pointer-events:none}
.cta-sec h2{font-family:'Space Mono',monospace;color:var(--bg);font-size:clamp(28px,4vw,44px);position:relative;z-index:1;margin-bottom:14px}
.cta-sec p{font-size:16px;color:rgba(240,235,224,0.55);margin-bottom:32px;position:relative;z-index:1}
.cta-hint{font-family:'Space Mono',monospace;font-size:10px;color:rgba(240,235,224,0.28);letter-spacing:2px;margin-top:14px;position:relative;z-index:1;text-transform:uppercase}
.cta-btn{background:var(--orange);color:#FFFFFF !important;border:none;border-radius:50px;padding:16px 40px;font-family:'Onest',sans-serif;font-size:15px;font-weight:600;cursor:pointer;text-decoration:none;display:inline-block;position:relative;z-index:1;transition:opacity .2s}
.cta-btn:hover{opacity:.88}

/* FOOTER */
footer{background:#0F1A12;padding:28px 48px;display:flex;justify-content:space-between;align-items:center}
.f-logo{font-family:'Space Mono',monospace;font-size:16px;font-weight:700;color:var(--orange);letter-spacing:2px}
.f-sub{font-family:'Space Mono',monospace;font-size:10px;color:rgba(240,235,224,0.25);margin-top:4px;letter-spacing:1px}
.f-links{display:flex;gap:24px;list-style:none}
.f-links a{font-family:'Space Mono',monospace;font-size:10px;color:rgba(240,235,224,0.3);text-decoration:none;letter-spacing:.5px;transition:color .2s}
.f-links a:hover{color:rgba(240,235,224,0.65)}

@media(max-width:900px){
  nav{padding:0 20px}
  .nav-links{display:none}
  .hero{padding:48px 20px 60px}
  .hero-grid{grid-template-columns:1fr;gap:40px}
  .sec{padding:56px 20px}
  .g3,.g4{grid-template-columns:1fr 1fr}
  .g2,.calc-grid{grid-template-columns:1fr}
  .results{grid-template-columns:1fr}
  footer{flex-direction:column;gap:16px;text-align:center;padding:24px 20px}
  .f-links{flex-wrap:wrap;justify-content:center}
}
@media(max-width:600px){
  .g3,.g4{grid-template-columns:1fr}
  .pr-grid{grid-template-columns:1fr 1fr}
}
.pr-grid{display:grid;grid-template-columns:repeat(4,1fr);gap:14px}
@media(max-width:900px){.pr-grid{grid-template-columns:1fr 1fr}}
@media(max-width:600px){.pr-grid{grid-template-columns:1fr}}

/* ============ КЕЙС / РЕЗУЛЬТАТЫ ============ */
.case-head{display:flex;align-items:center;gap:18px;margin-bottom:24px}
.case-company{font-family:'Space Mono',monospace;font-size:19px;font-weight:700;color:var(--text);line-height:1.2}
.case-descriptor{font-size:13px;color:var(--muted);line-height:1.5;margin-top:5px;max-width:520px}
.case-intro{font-size:15px;color:var(--muted);line-height:1.7;max-width:680px;margin-bottom:44px}
.case-intro b{color:var(--text);font-weight:600}
.grouplbl{font-family:'Space Mono',monospace;font-size:10px;letter-spacing:2px;text-transform:uppercase;color:var(--muted);margin:0 0 16px;display:flex;align-items:center;gap:14px}
.grouplbl::after{content:'';flex:1;height:1px;background:var(--border)}
.results-row{display:grid;grid-template-columns:1.5fr 1fr;gap:16px;margin-bottom:48px}
.result-card{background:var(--dark);border-radius:16px;padding:34px 36px;position:relative;overflow:hidden;display:flex;flex-direction:column}
.result-card::before{content:'';position:absolute;top:-120px;right:-120px;width:320px;height:320px;border-radius:50%;border:1px solid rgba(200,90,30,0.13);pointer-events:none}
.result-card::after{content:'';position:absolute;top:-60px;right:-60px;width:200px;height:200px;border-radius:50%;border:1px solid rgba(200,90,30,0.08);pointer-events:none}
.result-eye{font-family:'Space Mono',monospace;font-size:10px;letter-spacing:2px;text-transform:uppercase;color:rgba(240,235,224,0.42);margin-bottom:auto;position:relative;z-index:1}
.hero-num{font-family:'Space Mono',monospace;font-size:clamp(58px,9vw,88px);font-weight:700;color:var(--bg);line-height:.95;margin:28px 0 0;position:relative;z-index:1;letter-spacing:-1px}
.hero-num .accent{color:var(--orange)}
.result-desc{font-size:13px;color:rgba(240,235,224,0.55);line-height:1.65;margin-top:18px;position:relative;z-index:1;max-width:400px}
.result-desc b{color:rgba(240,235,224,0.85);font-weight:600}
.flow{display:flex;flex-direction:column;gap:6px;margin:28px 0 0;position:relative;z-index:1}
.flow-from{font-family:'Space Mono',monospace;font-size:clamp(22px,3vw,26px);font-weight:700;color:rgba(240,235,224,0.32);line-height:1;text-decoration:line-through;text-decoration-color:rgba(200,90,30,0.5)}
.flow-to{font-family:'Space Mono',monospace;font-size:clamp(38px,5.5vw,52px);font-weight:700;color:var(--bg);line-height:1}
.flow-to .arrow{color:var(--orange);margin-right:10px}
.sources{display:flex;flex-wrap:wrap;align-items:center;gap:10px;margin:-20px 0 44px}
.sources-lbl{font-family:'Space Mono',monospace;font-size:10px;letter-spacing:2px;text-transform:uppercase;color:var(--muted);margin-right:6px}
.src-pill{font-family:'Space Mono',monospace;font-size:12px;font-weight:700;color:var(--green);background:var(--card);border:1px solid var(--border);border-radius:50px;padding:7px 15px}
.scale-grid{display:grid;grid-template-columns:repeat(4,1fr);gap:16px}
.stat{background:var(--card);border:1px solid var(--border);border-radius:14px;padding:26px 24px;border-top:2px solid var(--green)}
.stat-num{font-family:'Space Mono',monospace;font-size:clamp(26px,3.2vw,32px);font-weight:700;color:var(--green);line-height:1;margin-bottom:12px;letter-spacing:-.5px;white-space:nowrap}
.stat-num span{font-size:16px;color:var(--muted);font-weight:400}
.stat-lbl{font-size:13px;color:var(--muted);line-height:1.55}
.takeaway{margin-top:44px;padding-top:28px;border-top:1px solid var(--border);display:flex;gap:16px;align-items:flex-start;max-width:860px}
.takeaway-mark{font-family:'Space Mono',monospace;font-size:20px;font-weight:700;color:var(--orange);line-height:1.3;flex-shrink:0}
.takeaway p{font-size:16px;color:var(--text);line-height:1.65;font-weight:400}
.takeaway p b{font-weight:600}
.case-quote{margin-top:44px;background:var(--card);border:1px solid var(--border);border-left:3px solid var(--orange);border-radius:12px;padding:28px 30px;max-width:820px}
.case-quote-text{font-style:italic;font-size:17px;color:var(--text);line-height:1.6}
.case-quote-foot{margin-top:20px}
.case-quote-author{font-family:'Space Mono',monospace;font-size:12px;letter-spacing:.5px;color:var(--text)}
.case-quote-author small{display:block;font-family:'Onest',sans-serif;font-size:12px;letter-spacing:0;color:var(--muted);margin-top:3px;font-weight:400}
@media(max-width:900px){
  .results-row{grid-template-columns:1fr}
  .scale-grid{grid-template-columns:1fr 1fr}
  .case-head{flex-wrap:wrap;gap:14px}
}
@media(max-width:520px){
  .scale-grid{grid-template-columns:1fr}
}

/* ПЛАВНОЕ ПОЯВЛЕНИЕ СЕКЦИЙ ПРИ СКРОЛЛЕ (мягко, без резкости) */
@media (prefers-reduced-motion:no-preference){
  .js section:not(.hero) > .wrap{opacity:0;transform:translateY(22px);transition:opacity .7s cubic-bezier(.22,.61,.36,1),transform .7s cubic-bezier(.22,.61,.36,1)}
  .js section:not(.hero) > .wrap.is-in{opacity:1;transform:none}
}
</style>
<script>document.documentElement.classList.add('js')</script>
</head>
<body>

<nav>
  <a href="#" class="logo">PULSE</a>
  <ul class="nav-links">
    <li><a href="#for-whom">Для кого</a></li>
    <li><a href="#how">Как работает</a></li>
    <li><a href="#pricing">Тарифы</a></li>
    <li><a href="https://pulsecloud.ru/blog" rel="noopener noreferrer" target="_blank">Блог</a></li>
  </ul>
  <a href="https://t.me/m_istomin" class="nav-btn" rel="noopener noreferrer" target="_blank">Записаться на демо</a>
</nav>

<!-- HERO -->
<section class="hero">
  <div class="wrap">
    <div class="hero-grid">
      <div>
        <span class="hero-tag">// сквозная аналитика для telegram-каналов</span>
        <h1>Узнай, какие Telegram-каналы реально приносят деньги</h1>
        <p class="hero-urgent">Цена лида в Telegram растёт. Без аналитики платишь за результат вслепую.</p>
        <p class="hero-sub">Pulse связывает каждое размещение с реальной выручкой. CPL, ROMI, LTV — в одном дашборде. Подключение за 20 минут.</p>
        <div class="pills">
          <div class="pill"><strong>CPL · ROMI</strong>по каждой ссылке</div>
          <div class="pill"><strong>без Excel</strong>без ручных сводок</div>
          <div class="pill"><strong>20 мин</strong>подключение</div>
          <div class="pill"><strong>до 30%</strong>экономим бюджета</div>
        </div>
        <div class="btn-row">
          <a href="https://t.me/m_istomin" class="btn-primary" rel="noopener noreferrer" target="_blank">Записаться на демо</a>
          <a href="#how" class="btn-outline">Как работает платформа</a>
        </div>
      </div>
      <div>
        <div class="dash">
          <div class="dash-hdr">Дашборд — реальное время</div>
          <div class="dash-r"><span class="dash-lbl">Telega.in | Блогер 156</span><span class="dash-val">ROMI 714%</span></div>
          <div class="dash-r"><span class="dash-lbl">Telegram Ads | Кампания 34</span><span class="dash-val">CPL 2 500 ₽</span></div>
          <div class="dash-r"><span class="dash-lbl">Influence | Блогер 89</span><span class="dash-val">+54 подписчика</span></div>
          <div class="dash-mets">
            <div class="dash-met"><div class="dash-met-n">7 000 ₽</div><div class="dash-met-l">Выручка</div></div>
            <div class="dash-met"><div class="dash-met-n">1 000 ₽</div><div class="dash-met-l">Расход</div></div>
            <div class="dash-met"><div class="dash-met-n">7.1%</div><div class="dash-met-l">Конверсия</div></div>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- FOR WHOM -->
<section class="sec" id="for-whom">
  <div class="wrap">
    <span class="eyebrow">Для кого Pulse</span>
    <h2>Для кого Pulse</h2>
    <div class="g3">
      <div class="card"><div class="who-role">CMO / Перфоманс-маркетолог</div><div class="who-hook">«На созвоне с руководителем хочу отвечать цифрами, а не ощущениями»</div><div class="who-pain">Telegram — проблемная площадка для аналитики. Непонятно, кто из подписчиков пришёл с какого размещения, и тем более — кто купил. Всё, что есть — стоимость подписки.</div></div>
      <div class="card"><div class="who-role">Media buyer / Агентство</div><div class="who-hook">«Отчёт занимает полдня, а клиент всё равно не верит»</div><div class="who-pain">10–100 размещений в месяц. Ручная сводка из разных таблиц. Клиент видит только клики и подписчиков — не деньги.</div></div>
      <div class="card"><div class="who-role">Владелец бизнеса</div><div class="who-hook">«Даю деньги на рекламу в Telegram — и не знаю, окупается ли»</div><div class="who-pain">Таргетолог отчитывается подписчиками и кликами. Сколько из этого реальных продаж — непонятно.</div></div>
      <div class="card"><div class="who-role">Head of Sales / CRM</div><div class="who-hook">«Лидов много, а продаж нет — непонятно, где проблема»</div><div class="who-pain">CRM не бьётся с маркетингом. UTM теряются на стыке Telegram → сайт → CRM.</div></div>
      <div class="card"><div class="who-role">CEO / CFO</div><div class="who-hook">«Планирую бюджет на Telegram — и фактически гадаю»</div><div class="who-pain">Нет ни ROMI по каналам, ни когортного разреза. Каждый новый квартал бюджет ставится на глазок.</div></div>
      <div class="card"><div class="who-role">Таргетолог / Маркетолог</div><div class="who-hook">«Всё, что остаётся после размещения — пригласительная ссылка с названием в канале»</div><div class="who-pain">В Telegram нет UTM-меток — только пригласительные ссылки. Кто эти люди и купили ли — неизвестно.</div></div>
    </div>
  </div>
</section>

<!-- PROBLEMS -->
<section class="sec sec-alt">
  <div class="wrap">
    <span class="eyebrow">Проблемы</span>
    <h2>Если хоть раз думал об этом — Pulse для тебя</h2>
    <div class="g4">
      <div class="card-green"><div class="prob-num-dark">01</div><div class="prob-hook-dark">«Деньги в Telegram уходят — а увеличивать бюджет или резать, и что именно, непонятно»</div><div class="prob-pain-dark">Нет системы отслеживания — нет и решений. Работаешь на интуиции.</div><div class="prob-sting-dark">Без данных любое решение по бюджету — это угадайка.</div></div>
      <div class="card-green"><div class="prob-num-dark">02</div><div class="prob-hook-dark">«Подрядчик принёс отчёт: 800 подписчиков, CPL — 300 рублей. Только продаж с этого — ноль»</div><div class="prob-pain-dark">Подписчики есть — и это всё, что ты знаешь. Купили ли что-то — неизвестно.</div><div class="prob-sting-dark">Красивый CPL и реальная выручка — это не одно и то же.</div></div>
      <div class="card-green"><div class="prob-num-dark">03</div><div class="prob-hook-dark">«Хочу выжать из Telegram максимум, но выжимать нечем — нет ни одной нормальной цифры»</div><div class="prob-pain-dark">KPI горят, канал есть, бюджет есть. Какое размещение даёт лиды — всё в ощущениях.</div><div class="prob-sting-dark">Telegram может работать в разы лучше. Просто ты не знаешь, где давить.</div></div>
      <div class="card-green"><div class="prob-num-dark">04</div><div class="prob-hook-dark">«Дал троим подрядчикам бюджет на Telegram — и не знаю кто из них реально отработал»</div><div class="prob-pain-dark">У каждого свои ссылки и свои отчёты. Сравнить по единой системе невозможно.</div><div class="prob-sting-dark">Без единой системы тестирование подрядчиков — это просто трата денег.</div></div>
    </div>
  </div>
</section>

<!-- HOW IT WORKS -->
<section class="sec" id="how">
  <div class="wrap">
    <span class="eyebrow">Как работает</span>
    <h2>Как работает Pulse: три шага</h2>
    <div class="g3" style="margin-bottom:28px">
      <div><div class="step-num">1</div><h3>Создаёте ссылку на канал или пост с UTM-меткой</h3><p class="bt">Генерируете пригласительную ссылку на Telegram-канал или ссылку на конкретный рекламный пост — и передаёте в размещение. Подключение — 20 минут один раз.</p><span class="badge">1–2 минуты</span></div>
      <div><div class="step-num">2</div><h3>Размещаете в рекламу</h3><p class="bt">Каждый новый подписчик автоматически попадает в базу: фиксируем ID, дату подписки и источник трафика.</p><span class="badge">Автоматически</span></div>
      <div><div class="step-num">3</div><h3>Получаете дашборд</h3><p class="bt">CPL, ROMI, CAC считаются сами. Заходишь — и сразу видишь, что окупилось, а что нет.</p><span class="badge">В реальном времени</span></div>
    </div>
  </div>
</section>

<!-- FEATURES -->
<section class="sec sec-alt">
  <div class="wrap">
    <span class="eyebrow">Функционал</span>
    <h2>Возможности платформы Pulse</h2>
    <div class="g3" style="margin-bottom:16px">
      <div class="card"><h3>UTM-ссылки и аналитика подписок</h3><p class="bt" style="margin-top:8px">Генерация ссылок и автоматический подсчёт подписок/отписок по каждой.</p></div>
      <div class="card"><h3>CPL и ROMI в реальном времени</h3><p class="bt" style="margin-top:8px">Лиды, продажи, конверсии по каждой ссылке. Без ручного счёта.</p></div>
      <div class="card"><h3>Интеграция с CRM</h3><p class="bt" style="margin-top:8px">Продажи из CRM — подключаем сами. Видно, какой канал привёл деньги.</p></div>
      <div class="card"><h3>Когортный и PnL отчёты</h3><p class="bt" style="margin-top:8px">Срезы по периодам. Сравниваете каналы по деньгам до оплаты, а не по кликам.</p></div>
      <div class="card"><h3>Алерты по CAC и ROMI</h3><p class="bt" style="margin-top:8px">Скажем, когда канал вышел за порог. Стоп или масштаб — видно сразу.</p></div>
      <div class="card"><h3>Кастомные дашборды</h3><p class="bt" style="margin-top:8px">Настраиваем под ваши метрики и процессы команды.</p></div>
    </div>
    <div class="g2">
      <div class="card"><div class="fmt-tag">Формат 1</div><h3>Ссылка на Telegram-канал</h3><p class="bt" style="margin-top:8px">Подписчик переходит по пригласительной ссылке и попадает в канал. Pulse фиксирует источник и привязывает его ко всем дальнейшим действиям.</p></div>
      <div class="card"><div class="fmt-tag">Формат 2</div><h3>Ссылка на конкретный пост</h3><p class="bt" style="margin-top:8px">Ссылка ведёт на конкретный рекламный пост в канале. Можно отслеживать, с какого именно поста пришёл подписчик и как он конвертировался.</p></div>
    </div>
  </div>
</section>

<!-- CALCULATOR -->
<section class="sec">
  <div class="wrap">
    <span class="eyebrow">Калькулятор</span>
    <h2>Посчитай, сколько ты теряешь без аналитики</h2>
    <div class="calc-grid">
      <div class="calc-side">
        <p class="calc-p"><strong>В среднем 30% бюджета уходит на каналы, которые не окупаются.</strong></p>
        <p class="calc-p">Ты знаешь средний CPL. Но эта цифра усредняет всё — и размещения, которые работают, и те, что тихо сливают бюджет. Один канал даёт лид за 300 ₽, другой за 3 000 ₽ — в среднем выходит «нормально».</p>
        <p class="calc-arrow">Посчитай сколько это у тебя →</p>
      </div>
      <div>
        <div class="calc-label">Ежемесячный бюджет на Telegram-рекламу</div>
        <input type="range" min="50000" max="5000000" value="500000" step="50000" id="budget">
        <div class="calc-val">Бюджет: <span id="budget-out">500 000 ₽</span></div>
        <div class="calc-label">Текущая стоимость лида (CPL)</div>
        <input type="range" min="100" max="10000" value="1500" step="100" id="cpl">
        <div class="calc-val">CPL сейчас: <span id="cpl-out">1 500 ₽</span></div>
      </div>
    </div>
    <div class="divider"></div>
    <div class="results">
      <div class="res-card"><div class="res-eye">Примерные потери на неэффективных каналах без аналитики</div><div class="res-num" id="losses">~150 000 ₽</div></div>
      <div class="res-card"><div class="res-eye">CPL после оптимизации</div><div class="res-num" id="cpl-new">1 050 ₽</div></div>
      <div class="res-card"><div class="res-eye">Экономия на каждом лиде</div><div class="res-num" id="cpl-economy">−450 ₽</div></div>
    </div>
    <a href="https://t.me/m_istomin" class="btn-primary" style="display:block;text-align:center;border-radius:50px;padding:16px;font-size:14px;margin-top:4px" rel="noopener noreferrer" target="_blank">Хочу эти цифры → Записаться на демо</a>
  </div>
</section>

<!-- CASE / КЕЙС «100БАЛЛЬНЫЙ РЕПЕТИТОР» -->
<section class="sec sec-alt" id="case">
  <div class="wrap">
    <span class="eyebrow">// кейс</span>

    <div class="case-head">
      <div class="case-head-txt">
        <div class="case-company">100балльный репетитор</div>
        <div class="case-descriptor">Онлайн-школа: курсы подготовки к&nbsp;ЕГЭ и&nbsp;ОГЭ. <!-- ← сверьте с официальным самоназванием компании --></div>
      </div>
    </div>

    <h2>Не клики, а деньги: eROMI 340%+ по всем каналам трафика</h2>
    <p class="case-intro">Задача была в&nbsp;масштабе — и&nbsp;вширь, и&nbsp;вглубь. В&nbsp;работе все каналы привлечения сразу, а внутри каждого — <b>сотни рекламных кампаний и&nbsp;закупов</b>. Так набегают тысячи размещений и&nbsp;десятки тысяч ссылок, и на&nbsp;выходе не&nbsp;видно, что реально приносит оплаты, а что просто жжёт бюджет. Pulse свёл всё это к&nbsp;деньгам — до&nbsp;конкретного размещения. Вот что получилось.</p>

    <div class="sources">
      <span class="sources-lbl">Под контролем:</span>
      <span class="src-pill">Telegram Ads</span>
      <span class="src-pill">Telega.in</span>
      <span class="src-pill">TikTok</span>
      <span class="src-pill">Influence</span>
      <span class="src-pill">YouTube</span>
      <span class="src-pill">Авито</span>
      <span class="src-pill">Max</span>
    </div>

    <div class="grouplbl">Что это дало</div>
    <div class="results-row">
      <div class="result-card">
        <div class="result-eye">Средний eROMI по каждому размещению</div>
        <div class="hero-num"><span class="accent">340%</span>+</div>
        <div class="result-desc"><b>eROMI</b> — окупаемость с учётом повторных покупок: по всей выручке за срок жизни клиента, а не по первой оплате. И видно это <b>по каждому источнику и до конкретного блогера, закупа, даже отдельного поста</b> — кто реально возвращает деньги. Дальше решение за вами: добавить бюджет туда, где он окупается, и убрать оттуда, где сгорает. Те&nbsp;же деньги приносят больше.</div>
      </div>
      <div class="result-card">
        <div class="result-eye">Ежедневная работа с аналитикой</div>
        <div class="flow">
          <span class="flow-from">было 4 часа</span>
          <span class="flow-to"><span class="arrow">→</span>15–30 мин</span>
        </div>
        <div class="result-desc">Создать ссылки под&nbsp;каждое размещение, собрать данные по&nbsp;каналам, свести всё в&nbsp;таблицы — раньше это и были те&nbsp;самые часы. Теперь ссылки генерируются в&nbsp;пару кликов, а данные собираются и сводятся <b>автоматически</b>.</div>
      </div>
    </div>

    <div class="grouplbl">Масштаб проекта</div>
    <div class="scale-grid">
      <div class="stat">
        <div class="stat-num">20 млн ₽<span>+</span></div>
        <div class="stat-lbl">рекламного бюджета прошло через аналитику Pulse</div>
      </div>
      <div class="stat">
        <div class="stat-num">700 000<span>+</span></div>
        <div class="stat-lbl">подписчиков отслежено до&nbsp;источника трафика</div>
      </div>
      <div class="stat">
        <div class="stat-num">35 000<span>+</span></div>
        <div class="stat-lbl">ссылок отслеживания создано под&nbsp;размещения</div>
      </div>
      <div class="stat">
        <div class="stat-num">42</div>
        <div class="stat-lbl">Telegram-канала подключено к&nbsp;аналитике</div>
      </div>
    </div>

    <div class="takeaway">
      <span class="takeaway-mark">→</span>
      <p>Pulse показывает, <b>где деньги реально возвращаются</b> — вплоть до отдельного поста. Видно, какие размещения приносят выручку, а какие её тихо съедают, — и рычаг у вас: вложить туда, где бюджет работает. <b>Те же деньги приносят больше.</b></p>
    </div>

    <!-- ЦИТАТА — раскомментируйте и заполните, когда согласуете отзыв клиента
    <blockquote class="case-quote">
      <div class="case-quote-text">«Здесь живая цитата клиента: что было больно, что изменилось, какой результат.»</div>
      <div class="case-quote-foot">
        <div class="case-quote-author">Имя Фамилия<small>Должность · 100балльный репетитор</small></div>
      </div>
    </blockquote>
    -->

  </div>
</section>

<!-- PRICING -->
<section class="sec" id="pricing">
  <div class="wrap">
    <span class="eyebrow">Тарифы</span>
    <h2>Тарифы Pulse</h2>
    <p style="font-family:'Space Mono',monospace;font-size:12px;font-weight:700;color:var(--text);margin-bottom:24px">Чем больше Telegram-каналов — тем ниже цена за каждый</p>
    <div class="pr-grid">
      <div class="price-card"><div class="price-tier">1 канал</div><div class="price-amt">14 990 ₽</div><div class="price-per">в месяц</div><div class="price-sp"></div><a href="https://t.me/m_istomin" class="btn-green-outline" rel="noopener noreferrer" target="_blank">Начать работу</a></div>
      <div class="price-card feat"><div class="price-pop">Популярный</div><div class="price-tier">2–4 канала</div><div class="price-amt">11 990 ₽</div><div class="price-per">за канал / месяц</div><div class="price-disc">−20%</div><div class="price-sp"></div><a href="https://t.me/m_istomin" class="btn-green" rel="noopener noreferrer" target="_blank">Начать работу</a></div>
      <div class="price-card"><div class="price-tier">5–9 каналов</div><div class="price-amt">8 990 ₽</div><div class="price-per">за канал / месяц</div><div class="price-disc">−40%</div><div class="price-sp"></div><a href="https://t.me/m_istomin" class="btn-green-outline" rel="noopener noreferrer" target="_blank">Начать работу</a></div>
      <div class="price-card"><div class="price-tier">от 10 каналов</div><div class="price-amt">6 990 ₽</div><div class="price-per">за канал / месяц</div><div class="price-disc">−53%</div><div class="price-sp"></div><a href="https://t.me/m_istomin" class="btn-green-outline" rel="noopener noreferrer" target="_blank">Обсудить условия</a></div>
    </div>
    <p class="price-fn">Весь функционал включён во все тарифы — Интеграция с CRM подключаем сами</p>
  </div>
</section>

<!-- FAQ -->
<section class="sec sec-alt">
  <div class="wrap">
    <span class="eyebrow">Частые вопросы</span>
    <h2>Частые вопросы</h2>
    <div class="faq-item open"><button class="faq-btn"><span class="faq-q">Как настроить сквозную аналитику в Telegram?</span><span class="faq-ic"><svg viewBox="0 0 10 6"><polyline points="1,1 5,5 9,1"/></svg></span></button><div class="faq-body">Подключение занимает 20 минут: добавляете бота в канал, создаёте UTM-ссылки — CRM подключаем сами. Даём доступ к платформе, помогаем с подключением и первыми шагами. Технических знаний не нужно.</div></div>
    <div class="faq-item"><button class="faq-btn"><span class="faq-q">Можно ли подключить несколько Telegram-каналов если в компании их несколько?</span><span class="faq-ic"><svg viewBox="0 0 10 6"><polyline points="1,1 5,5 9,1"/></svg></span></button><div class="faq-body">Да, конечно. На платформе вы увидите все данные по всем вашим каналам и рекламным размещениям в одном месте.</div></div>
    <div class="faq-item"><button class="faq-btn"><span class="faq-q">Как посчитать ROMI в Telegram-канале автоматически?</span><span class="faq-ic"><svg viewBox="0 0 10 6"><polyline points="1,1 5,5 9,1"/></svg></span></button><div class="faq-body">Pulse берёт расходы, данные подписчиков и продажи из CRM — считает ROMI сам. В реальном времени по каждому каналу и размещению.</div></div>
    <div class="faq-item"><button class="faq-btn"><span class="faq-q">Где смотреть всю отчётность по рекламе в Telegram?</span><span class="faq-ic"><svg viewBox="0 0 10 6"><polyline points="1,1 5,5 9,1"/></svg></span></button><div class="faq-body">В дашборде Pulse видно всю отчётность — CPL, ROMI, CAC, UTM-метки, когортные отчёты и PnL. Всё в одном месте, обновляется автоматически.</div></div>
    <div class="faq-item"><button class="faq-btn"><span class="faq-q">Как посмотреть окупаемость Telegram-рекламы?</span><span class="faq-ic"><svg viewBox="0 0 10 6"><polyline points="1,1 5,5 9,1"/></svg></span></button><div class="faq-body">Pulse формирует отчёт «канал → пост → деньги» с цифрами ROMI, CAC, PnL. Заходите в дашборд и смотрите сами.</div></div>
  </div>
</section>

<!-- CTA -->
<section class="cta-sec" id="demo">
  <div class="cta-ring"></div>
  <div class="cta-ring2"></div>
  <div class="wrap" style="position:relative;z-index:1">
    <h2>Возьми бюджет на Telegram под контроль</h2>
    <p>Напиши в Telegram — покажем платформу и обсудим подключение.</p>
    <a href="https://t.me/m_istomin" class="cta-btn" rel="noopener noreferrer" target="_blank">Написать в Telegram →</a>
  </div>
</section>

<footer>
  <div><div class="f-logo">PULSE</div><div class="f-sub">// сквозная аналитика для telegram</div></div>
  <div style="font-family:'Space Mono',monospace;font-size:10px;color:rgba(240,235,224,0.3);letter-spacing:1px">© 2025 Pulse</div>
</footer>

<script>
const budget=document.getElementById('budget'),cpl=document.getElementById('cpl');
function update(){
  const b=parseInt(budget.value),c=parseInt(cpl.value);
  document.getElementById('budget-out').textContent=b.toLocaleString('ru-RU')+' ₽';
  document.getElementById('cpl-out').textContent=c.toLocaleString('ru-RU')+' ₽';
  document.getElementById('losses').textContent='~'+Math.round(b*.3).toLocaleString('ru-RU')+' ₽';
  document.getElementById('cpl-new').textContent=Math.round(c*.7).toLocaleString('ru-RU')+' ₽';
  document.getElementById('cpl-economy').textContent='−'+Math.round(c*.3).toLocaleString('ru-RU')+' ₽';
}
budget.addEventListener('input',update);cpl.addEventListener('input',update);update();
document.querySelectorAll('.faq-btn').forEach(b=>b.addEventListener('click',()=>b.closest('.faq-item').classList.toggle('open')));

/* плавное появление секций при скролле */
(function(){
  var els=document.querySelectorAll('section:not(.hero) > .wrap');
  if('IntersectionObserver' in window){
    var io=new IntersectionObserver(function(ents,obs){
      ents.forEach(function(e){if(e.isIntersecting){e.target.classList.add('is-in');obs.unobserve(e.target);}});
    },{threshold:0.1,rootMargin:'0px 0px -6% 0px'});
    els.forEach(function(el){io.observe(el);});
  }else{
    els.forEach(function(el){el.classList.add('is-in');});
  }
})();
</script>
</body>
</html>
