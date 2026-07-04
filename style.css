  :root{
    --cream:#FFFFFF;
    --cream-deep:#F5F5F5;
    --white:#FFFFFF;
    --ink:#111111;
    --steel:#575757;
    --line:rgba(0,0,0,0.12);

    --clay:#3A3A3A;
    --clay-deep:#111111;
    --clay-tint:#ECECEC;

    --slate:#2A5C8A;
    --slate-deep:#1E4260;
    --slate-tint:#E4ECF3;

    --teal:#1F7A63;
    --teal-deep:#155845;
    --teal-tint:#E1F0EA;

    --radius:4px;
    --maxw:1200px;
  }

  *{box-sizing:border-box;}
  html{scroll-behavior:smooth;}
  body{
    margin:0;background:var(--cream);color:var(--ink);
    font-family:'Inter',sans-serif;font-size:16px;line-height:1.6;
    -webkit-font-smoothing:antialiased;
  }
  h1,h2,h3,h4{
    font-family:'Space Grotesk',sans-serif;
    letter-spacing:-0.01em;margin:0;color:var(--ink);
  }
  .mono{font-family:'JetBrains Mono',monospace;letter-spacing:0.02em;}
  a{color:inherit;}
  img,svg{max-width:100%;display:block;}
  .wrap{max-width:var(--maxw);margin:0 auto;padding:0 28px;}

  a:focus-visible,button:focus-visible,input:focus-visible,textarea:focus-visible,select:focus-visible{
    outline:3px solid var(--clay-deep);outline-offset:2px;
  }

  /* ---------- HEADER ---------- */
  header{
    position:sticky;top:0;z-index:50;
    background:rgba(255,255,255,0.9);
    backdrop-filter:blur(8px);
    border-bottom:1px solid var(--line);
  }
  .nav{
    display:flex;align-items:center;justify-content:space-between;
    padding:16px 28px;max-width:var(--maxw);margin:0 auto;
  }
  .brand{
    display:flex;align-items:center;gap:10px;text-decoration:none;
  }
  .brand-mark{
    width:38px;height:38px;border-radius:6px;
    background:linear-gradient(135deg,var(--clay),var(--teal));
    display:flex;align-items:center;justify-content:center;
    font-family:'Space Grotesk',sans-serif;color:var(--white);font-weight:700;font-size:1.05rem;
    flex-shrink:0;
  }
  .brand-text{
    font-family:'Space Grotesk',sans-serif;font-size:1.15rem;font-weight:700;
    letter-spacing:0.04em;color:var(--ink);
  }
  .brand-text span{color:var(--clay-deep);}
  .nav-links{display:flex;gap:30px;list-style:none;margin:0;padding:0;}
  .nav-links li{position:relative;}
  .nav-links a{
    color:var(--steel);text-decoration:none;font-size:0.92rem;
    text-transform:uppercase;letter-spacing:0.05em;
    padding-bottom:4px;display:inline-block;
  }
  .nav-links a::after{
    content:"";position:absolute;left:0;bottom:-2px;height:2px;width:0%;
    background:var(--clay);transition:width .25s ease;
  }
  .nav-links a:hover{color:var(--ink);}
  .nav-links a:hover::after{width:100%;}
  .nav-cta{
    display:flex;align-items:center;gap:9px;
    background:var(--ink);color:var(--white);text-decoration:none;
    font-family:'JetBrains Mono',monospace;font-size:0.9rem;
    padding:11px 18px;border-radius:var(--radius);
    transition:background .2s, transform .15s;white-space:nowrap;
  }
  .nav-cta:hover{background:var(--clay-deep);transform:translateY(-1px);}

  /* ---------- HERO ---------- */
  .hero{
    position:relative;overflow:hidden;padding:96px 0 84px;
  }
  .hero-blob{
    position:absolute;border-radius:50%;filter:blur(50px);opacity:0.35;pointer-events:none;
    animation:drift 16s ease-in-out infinite;
  }
  .blob-a{width:380px;height:380px;background:var(--clay-tint);top:-120px;right:-80px;}
  .blob-b{width:300px;height:300px;background:var(--teal-tint);bottom:-100px;left:-60px;animation-delay:-8s;}
  @keyframes drift{
    0%,100%{transform:translate(0,0) scale(1);}
    50%{transform:translate(20px,-25px) scale(1.06);}
  }
  .hero-facade{
    position:absolute;right:-40px;top:50%;transform:translateY(-50%);
    width:46%;max-width:520px;opacity:0.06;pointer-events:none;
  }
  .hero-grid{
    position:relative;z-index:1;display:grid;grid-template-columns:1.05fr 0.95fr;gap:56px;align-items:center;
  }
  .eyebrow{
    font-family:'JetBrains Mono',monospace;color:var(--clay-deep);font-size:0.85rem;
    letter-spacing:0.14em;text-transform:uppercase;margin-bottom:20px;
    display:flex;align-items:center;gap:10px;
  }
  .eyebrow::before{content:"";width:26px;height:1px;background:var(--clay-deep);}
  .hero h1{
    font-size:clamp(2.4rem,5vw,3.8rem);line-height:1.05;font-weight:700;
  }
  .hero .word{display:inline-block;opacity:0;transform:translateY(18px);animation:wordIn .6s ease forwards;}
  .hero .word:nth-child(1){animation-delay:.05s;}
  .hero .word:nth-child(2){animation-delay:.15s;color:var(--clay-deep);}
  .hero .word:nth-child(3){animation-delay:.25s;}
  .hero .word:nth-child(4){animation-delay:.35s;color:var(--slate-deep);}
  .hero .word:nth-child(5){animation-delay:.45s;}
  .hero .word:nth-child(6){animation-delay:.55s;color:var(--teal-deep);}
  @keyframes wordIn{to{opacity:1;transform:translateY(0);}}
  .hero p.lead{
    max-width:48ch;margin-top:24px;font-size:1.1rem;color:var(--steel);
    opacity:0;animation:fadeUp .7s ease forwards;animation-delay:.7s;
  }
  .hero-actions{
    display:flex;gap:14px;flex-wrap:wrap;margin-top:34px;
    opacity:0;animation:fadeUp .7s ease forwards;animation-delay:.85s;
  }
  @keyframes fadeUp{from{opacity:0;transform:translateY(14px);}to{opacity:1;transform:translateY(0);}}

  .btn{
    display:inline-flex;align-items:center;gap:10px;padding:15px 26px;
    font-family:'JetBrains Mono',monospace;font-size:0.92rem;text-decoration:none;
    border-radius:var(--radius);border:1px solid transparent;cursor:pointer;
    transition:transform .15s ease, background .2s, border-color .2s, box-shadow .2s;
  }
  .btn:hover{transform:translateY(-2px);}
  .btn-primary{background:var(--ink);color:var(--white);box-shadow:0 8px 20px -8px rgba(17,17,17,0.5);}
  .btn-primary:hover{background:var(--clay-deep);}
  .btn-outline{border-color:var(--ink);color:var(--ink);}
  .btn-outline:hover{background:var(--ink);color:var(--white);}

  /* before/after slider */
  .ba-wrap{
    position:relative;border-radius:14px;overflow:hidden;
    aspect-ratio:4/3.1;box-shadow:0 30px 60px -25px rgba(42,38,32,0.35);
    opacity:0;animation:fadeUp .8s ease forwards;animation-delay:.3s;
  }
  .ba-layer{position:absolute;inset:0;}
  .ba-before{background:
      radial-gradient(circle at 15% 20%, rgba(0,0,0,0.08) 0, transparent 3%),
      radial-gradient(circle at 65% 10%, rgba(0,0,0,0.07) 0, transparent 2.6%),
      radial-gradient(circle at 40% 55%, rgba(0,0,0,0.09) 0, transparent 3.4%),
      radial-gradient(circle at 80% 60%, rgba(0,0,0,0.06) 0, transparent 2.2%),
      radial-gradient(circle at 25% 80%, rgba(0,0,0,0.08) 0, transparent 3%),
      radial-gradient(circle at 90% 90%, rgba(0,0,0,0.07) 0, transparent 2.6%),
      linear-gradient(160deg,#d7d7d7,#b9b9b9);
    background-size:220px 220px,190px 190px,240px 240px,180px 180px,210px 210px,200px 200px,100% 100%;
  }
  .ba-after{
    background:linear-gradient(155deg,#ffffff,#f2f2f2 60%,#e6e6e6);
    clip-path:inset(0 0 0 50%);
  }
  .ba-after::after{
    content:"";position:absolute;inset:0;
    background:linear-gradient(115deg, transparent 40%, rgba(255,255,255,0.55) 50%, transparent 60%);
  }
  .ba-handle{
    position:absolute;top:0;bottom:0;left:50%;width:3px;background:var(--white);
    transform:translateX(-50%);box-shadow:0 0 0 1px rgba(0,0,0,0.08);
    pointer-events:none;
  }
  .ba-handle::before{
    content:"↔";position:absolute;top:50%;left:50%;transform:translate(-50%,-50%);
    width:44px;height:44px;background:var(--white);border-radius:50%;
    display:flex;align-items:center;justify-content:center;font-size:1.1rem;color:var(--ink);
    box-shadow:0 6px 16px -4px rgba(0,0,0,0.3);
  }
  .ba-range{
    position:absolute;inset:0;width:100%;height:100%;margin:0;
    opacity:0;cursor:ew-resize;appearance:none;
  }
  .ba-tag{
    position:absolute;top:16px;font-family:'JetBrains Mono',monospace;font-size:0.75rem;
    letter-spacing:0.08em;text-transform:uppercase;color:var(--white);
    background:rgba(42,38,32,0.55);padding:6px 12px;border-radius:20px;pointer-events:none;
  }
  .ba-tag-before{left:16px;}
  .ba-tag-after{right:16px;}
  .ba-caption{
    margin-top:14px;font-family:'JetBrains Mono',monospace;font-size:0.82rem;color:var(--steel);
    text-align:center;
  }

  /* ---------- TRUST / STATS ---------- */
  .stats{background:var(--white);border-top:1px solid var(--line);border-bottom:1px solid var(--line);}
  .stats-inner{
    max-width:var(--maxw);margin:0 auto;padding:40px 28px;
    display:grid;grid-template-columns:repeat(4,1fr);gap:24px;text-align:center;
  }
  .stat-num{font-family:'Space Grotesk',sans-serif;font-size:2.4rem;font-weight:700;color:var(--clay-deep);}
  .stat-lbl{font-family:'JetBrains Mono',monospace;font-size:0.8rem;color:var(--steel);text-transform:uppercase;letter-spacing:0.06em;margin-top:4px;}

  /* ---------- SECTIONS GENERIC ---------- */
  .section{padding:96px 0;}
  .section-head{max-width:640px;margin:0 auto 56px;text-align:center;}
  .section-head .eyebrow{justify-content:center;}
  .section-head h2{font-size:clamp(1.9rem,4vw,2.6rem);}
  .section-head p{margin-top:16px;color:var(--steel);font-size:1.05rem;}

  /* ---------- PROJEKTE ---------- */
  .projects{background:var(--cream-deep);}
  .project-grid{
    display:grid;grid-template-columns:repeat(3,1fr);gap:26px;
  }
  .project-card{
    background:var(--white);border-radius:12px;overflow:hidden;
    border:1px solid var(--line);
    transition:transform .35s ease, box-shadow .35s ease;
  }
  .project-card:hover{transform:translateY(-6px);box-shadow:0 20px 36px -18px rgba(17,17,17,0.25);}
  .project-thumb{height:150px;position:relative;overflow:hidden;transition:transform .5s ease;}
  .project-card:hover .project-thumb{transform:scale(1.06);}
  .project-body{padding:22px 22px 26px;}
  .project-size{
    display:inline-block;font-size:0.8rem;color:var(--white);background:var(--ink);
    padding:5px 11px;border-radius:20px;margin-bottom:12px;
  }
  .project-body h3{font-size:1.12rem;margin-bottom:8px;font-weight:600;}
  .project-body p{margin:0;color:var(--steel);font-size:0.92rem;}

  /* ---------- SERVICES ---------- */
  .services{background:var(--cream);}
  .service-cards{display:grid;grid-template-columns:repeat(3,1fr);gap:28px;}
  .service-card{
    background:var(--white);border-radius:14px;padding:34px 30px 30px;
    border:1px solid var(--line);
    transition:transform .3s ease, box-shadow .3s ease;
  }
  .service-card:hover{transform:translateY(-8px);box-shadow:0 24px 40px -20px rgba(42,38,32,0.25);}
  .swatch{
    width:100%;height:110px;border-radius:10px;margin-bottom:22px;position:relative;overflow:hidden;
  }
  .swatch-putz{
    background:
      radial-gradient(circle at 20% 30%, rgba(0,0,0,0.06) 0, transparent 3%),
      radial-gradient(circle at 60% 15%, rgba(0,0,0,0.05) 0, transparent 2.4%),
      radial-gradient(circle at 40% 60%, rgba(0,0,0,0.07) 0, transparent 3%),
      radial-gradient(circle at 80% 70%, rgba(0,0,0,0.05) 0, transparent 2.4%),
      radial-gradient(circle at 15% 85%, rgba(0,0,0,0.06) 0, transparent 2.8%),
      linear-gradient(155deg,var(--clay-tint),#d4d4d4);
    background-size:70px 70px,60px 60px,80px 80px,55px 55px,65px 65px,100% 100%;
  }
  .swatch-trockenbau{
    background:linear-gradient(155deg,var(--slate-tint),#c7dde6);
    background-image:
      linear-gradient(155deg,var(--slate-tint),#c7dde6),
      repeating-linear-gradient(90deg, rgba(55,83,99,0.18) 0 2px, transparent 2px 96px),
      repeating-linear-gradient(0deg, rgba(55,83,99,0.1) 0 1px, transparent 1px 28px);
  }
  .swatch-fliesen{
    background-image:
      repeating-linear-gradient(90deg, rgba(31,97,83,0.22) 0 2px, transparent 2px 40px),
      repeating-linear-gradient(0deg, rgba(31,97,83,0.22) 0 2px, transparent 2px 40px),
      linear-gradient(155deg,var(--teal-tint),#bfe4d8);
  }
  .service-card h3{font-size:1.4rem;margin-bottom:8px;}
  .service-tag{
    font-family:'JetBrains Mono',monospace;font-size:0.78rem;text-transform:none;
    color:var(--steel);margin-bottom:16px;display:block;
  }
  .service-list{list-style:none;margin:0 0 22px;padding:0;display:grid;gap:9px;}
  .service-list li{display:flex;gap:9px;font-size:0.94rem;color:var(--ink);}
  .service-list li::before{content:"✓";color:var(--clay-deep);font-weight:600;flex-shrink:0;}
  .service-card.slate .service-list li::before{color:var(--slate-deep);}
  .service-card.teal .service-list li::before{color:var(--teal-deep);}
  .service-link{
    font-family:'JetBrains Mono',monospace;font-size:0.88rem;color:var(--clay-deep);
    text-decoration:none;display:inline-flex;align-items:center;gap:6px;
  }
  .service-card.slate .service-link{color:var(--slate-deep);}
  .service-card.teal .service-link{color:var(--teal-deep);}
  .service-link .arrow{transition:transform .2s ease;}
  .service-link:hover .arrow{transform:translateX(4px);}

  /* ---------- ABLAUF ---------- */
  .process{background:var(--white);}
  .process-steps{display:grid;grid-template-columns:repeat(4,1fr);gap:22px;}
  .step{
    background:var(--cream);border-radius:12px;padding:28px 22px;
    border:1px solid var(--line);position:relative;
  }
  .step-num{
    font-family:'JetBrains Mono',monospace;color:var(--clay-deep);font-size:0.85rem;
    display:inline-flex;align-items:center;justify-content:center;
    width:30px;height:30px;border-radius:50%;background:var(--clay-tint);
    margin-bottom:16px;
  }
  .step h4{font-size:1.08rem;margin-bottom:8px;}
  .step p{margin:0;color:var(--steel);font-size:0.92rem;}

  /* ---------- FAQ ---------- */
  .faq{background:var(--cream);}
  .faq-list{max-width:760px;margin:0 auto;display:grid;gap:12px;}
  .faq-item{background:var(--white);border:1px solid var(--line);border-radius:10px;overflow:hidden;}
  .faq-q{
    width:100%;text-align:left;background:none;border:none;cursor:pointer;
    padding:20px 22px;display:flex;justify-content:space-between;align-items:center;gap:16px;
    font-family:'Space Grotesk',sans-serif;font-size:1.02rem;text-transform:none;letter-spacing:0;color:var(--ink);
  }
  .faq-q .plus{
    width:26px;height:26px;border-radius:50%;background:var(--clay-tint);color:var(--clay-deep);
    flex-shrink:0;display:flex;align-items:center;justify-content:center;
    transition:transform .3s ease, background .3s ease;font-size:1rem;
  }
  .faq-item.open .faq-q .plus{transform:rotate(135deg);background:var(--clay);color:var(--white);}
  .faq-a{
    max-height:0;overflow:hidden;transition:max-height .35s ease;
  }
  .faq-a p{margin:0;padding:0 22px 20px;color:var(--steel);font-size:0.96rem;}

  /* ---------- CONTACT ---------- */
  .contact{background:var(--ink);color:var(--white);}
  .contact .eyebrow{color:var(--clay-tint);}
  .contact .eyebrow::before{background:var(--clay-tint);}
  .contact .section-head p{color:#cfc9bd;}
  .contact-grid{display:grid;grid-template-columns:1.1fr 1fr;gap:56px;}
  form{display:grid;gap:16px;}
  .form-row{display:grid;grid-template-columns:1fr 1fr;gap:16px;}
  label{
    font-family:'JetBrains Mono',monospace;font-size:0.74rem;text-transform:uppercase;
    letter-spacing:0.08em;color:#cfc9bd;display:block;margin-bottom:8px;
  }
  input,textarea,select{
    width:100%;padding:13px 14px;background:rgba(255,255,255,0.07);
    border:1px solid rgba(255,255,255,0.2);border-radius:var(--radius);
    color:var(--white);font-family:'Inter',sans-serif;font-size:0.98rem;
  }
  input::placeholder,textarea::placeholder{color:rgba(255,255,255,0.4);}
  textarea{resize:vertical;min-height:110px;}
  .form-submit{
    margin-top:4px;background:var(--clay);color:var(--white);border:none;
    padding:15px 26px;font-family:'JetBrains Mono',monospace;font-size:0.92rem;
    border-radius:var(--radius);cursor:pointer;justify-self:start;
    transition:background .2s, transform .15s;
  }
  .form-submit:hover{background:var(--clay-deep);transform:translateY(-2px);}
  .form-note{font-size:0.82rem;color:#a8a191;margin-top:2px;}
  .contact-info dt{
    font-family:'JetBrains Mono',monospace;font-size:0.75rem;color:var(--clay-tint);
    text-transform:uppercase;letter-spacing:0.1em;margin-top:24px;
  }
  .contact-info dt:first-child{margin-top:0;}
  .contact-info dd{margin:6px 0 0;font-size:1.08rem;}
  .contact-info a{text-decoration:none;color:var(--white);border-bottom:1px solid rgba(255,255,255,0.3);}
  .contact-info a:hover{border-color:var(--clay-tint);color:var(--clay-tint);}

  /* ---------- FOOTER ---------- */
  footer{background:#FFFFFF;padding:40px 0 24px;border-top:1px solid var(--line);}
  .footer-inner{
    display:flex;justify-content:space-between;align-items:center;flex-wrap:wrap;gap:14px;
    font-size:0.85rem;color:var(--steel);
  }
  .footer-links{display:flex;gap:20px;list-style:none;padding:0;margin:0;}
  .footer-links a{text-decoration:none;color:var(--steel);}
  .footer-links a:hover{color:var(--clay-deep);}

  /* ---------- REVEAL ---------- */
  .reveal{opacity:0;transform:translateY(24px);transition:opacity .7s ease, transform .7s ease;}
  .reveal.is-visible{opacity:1;transform:translateY(0);}

  @media (prefers-reduced-motion: reduce){
    html{scroll-behavior:auto;}
    .reveal,.hero .word,.hero p.lead,.hero-actions,.ba-wrap{opacity:1;transform:none;animation:none;}
    .hero-blob{animation:none;}
    .btn:hover,.service-card:hover{transform:none;}
  }

  /* ---------- RESPONSIVE ---------- */
  @media (max-width: 980px){
    .nav-links{display:none;}
    .hero-grid{grid-template-columns:1fr;}
    .service-cards{grid-template-columns:1fr;}
    .project-grid{grid-template-columns:1fr 1fr;}
    .process-steps{grid-template-columns:1fr 1fr;}
    .contact-grid{grid-template-columns:1fr;}
    .stats-inner{grid-template-columns:1fr 1fr;}
  }
  @media (max-width: 560px){
    .form-row{grid-template-columns:1fr;}
    .process-steps{grid-template-columns:1fr;}
    .project-grid{grid-template-columns:1fr;}
    .nav-cta span{display:none;}
  }

  /* ---------- EINFACHE INHALTSSEITEN (Impressum, Datenschutz, Kontakt) ---------- */
  .page-header{padding:72px 0 40px;border-bottom:1px solid var(--line);}
  .page-header h1{font-size:clamp(2rem,4vw,2.8rem);}
  .page-header p{color:var(--steel);margin-top:14px;max-width:60ch;}
  .legal{padding:56px 0 100px;}
  .legal .wrap{max-width:820px;}
  .legal h2{font-size:1.3rem;margin-top:40px;margin-bottom:12px;}
  .legal h2:first-child{margin-top:0;}
  .legal p, .legal li{color:var(--steel);font-size:0.98rem;line-height:1.7;}
  .legal a{color:var(--ink);text-decoration:underline;}
  .legal ul{padding-left:20px;}
