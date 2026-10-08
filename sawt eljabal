<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>صوت الجبل | من الوعي إلى المشاركة</title>

<meta name="description" content="صوت الجبل منصة شبابية تهتم بقضايا الجبال والقرى، وتجمع بين الوعي، الحوار، الأفكار، الأنشطة والمشاركة الميدانية.">

<style>
/* =========================================================
   صوت الجبل — DESIGN SYSTEM
   ========================================================= */

:root{
    --bg:#07100d;
    --bg2:#0c1713;
    --card:#101f19;
    --card2:#14271f;
    --green:#b9e67c;
    --green2:#7fcf61;
    --white:#f5f7f2;
    --muted:#a8b5ae;
    --line:rgba(255,255,255,.09);
    --danger:#e58c78;
    --gold:#e7c56a;
    --shadow:0 25px 70px rgba(0,0,0,.35);
    --radius:24px;
    --max:1220px;
}

*{
    box-sizing:border-box;
    margin:0;
    padding:0;
}

html{
    scroll-behavior:smooth;
}

body{
    font-family:
      "Tajawal",
      "Cairo",
      Arial,
      sans-serif;
    background:
      radial-gradient(circle at 90% 0%, rgba(127,207,97,.08), transparent 30%),
      var(--bg);
    color:var(--white);
    line-height:1.8;
    overflow-x:hidden;
}

button,
input,
textarea,
select{
    font-family:inherit;
}

button{
    cursor:pointer;
}

a{
    color:inherit;
    text-decoration:none;
}

img{
    max-width:100%;
    display:block;
}

/* =========================================================
   GLOBAL
   ========================================================= */

.container{
    width:min(var(--max), calc(100% - 40px));
    margin:auto;
}

.section{
    padding:110px 0;
    position:relative;
}

.section-header{
    max-width:760px;
    margin-bottom:50px;
}

.eyebrow{
    display:inline-flex;
    align-items:center;
    gap:8px;
    padding:7px 13px;
    border:1px solid rgba(185,230,124,.22);
    background:rgba(185,230,124,.06);
    color:var(--green);
    border-radius:999px;
    font-size:13px;
    margin-bottom:18px;
}

.section-title{
    font-size:clamp(32px,5vw,58px);
    line-height:1.1;
    letter-spacing:-1.5px;
    margin-bottom:18px;
}

.section-description{
    color:var(--muted);
    font-size:17px;
    max-width:680px;
}

.btn{
    border:0;
    border-radius:14px;
    padding:13px 21px;
    font-size:15px;
    font-weight:800;
    transition:.25s ease;
    display:inline-flex;
    justify-content:center;
    align-items:center;
    gap:8px;
}

.btn:hover{
    transform:translateY(-3px);
}

.btn-primary{
    background:var(--green);
    color:#09100b;
    box-shadow:0 10px 35px rgba(185,230,124,.14);
}

.btn-secondary{
    background:rgba(255,255,255,.06);
    border:1px solid var(--line);
    color:white;
}

.btn-danger{
    background:#351b18;
    color:#ffc0b1;
    border:1px solid rgba(229,140,120,.2);
}

.muted{
    color:var(--muted);
}

.grid{
    display:grid;
    gap:22px;
}

/* =========================================================
   HEADER
   ========================================================= */

header{
    position:fixed;
    top:0;
    right:0;
    left:0;
    z-index:1000;
    background:rgba(7,16,13,.72);
    backdrop-filter:blur(18px);
    border-bottom:1px solid var(--line);
}

.nav{
    min-height:76px;
    display:flex;
    align-items:center;
    justify-content:space-between;
    gap:20px;
}

.logo{
    display:flex;
    align-items:center;
    gap:11px;
    font-weight:900;
    font-size:20px;
}

.logo-mark{
    width:39px;
    height:39px;
    border-radius:12px;
    display:grid;
    place-items:center;
    background:var(--green);
    color:#07100d;
    font-size:21px;
}

.logo small{
    display:block;
    color:var(--muted);
    font-size:9px;
    font-weight:500;
    line-height:1;
    margin-top:2px;
}

.nav-links{
    display:flex;
    align-items:center;
    gap:5px;
}

.nav-links button{
    background:none;
    border:0;
    color:#d8ded9;
    padding:10px 13px;
    border-radius:10px;
    font-weight:700;
    font-size:14px;
}

.nav-links button:hover{
    background:rgba(255,255,255,.06);
    color:white;
}

.nav-join{
    margin-right:5px;
}

.menu-btn{
    display:none;
    background:none;
    border:1px solid var(--line);
    color:white;
    width:42px;
    height:42px;
    border-radius:12px;
    font-size:21px;
}

/* =========================================================
   HERO
   ========================================================= */

.hero{
    min-height:100vh;
    display:flex;
    align-items:center;
    position:relative;
    overflow:hidden;
    padding-top:100px;

    background:
      linear-gradient(90deg,
        rgba(7,16,13,.98) 0%,
        rgba(7,16,13,.88) 42%,
        rgba(7,16,13,.45) 100%),
      url("images/hero-winter.jpg") center/cover no-repeat;
}

.hero::after{
    content:"";
    position:absolute;
    inset:auto 0 0 0;
    height:190px;
    background:linear-gradient(transparent,var(--bg));
    pointer-events:none;
}

.hero-content{
    position:relative;
    z-index:2;
    max-width:780px;
    padding:80px 0;
}

.hero-kicker{
    color:var(--green);
    font-weight:800;
    letter-spacing:.5px;
    margin-bottom:20px;
}

.hero h1{
    font-size:clamp(48px,8vw,96px);
    line-height:.98;
    letter-spacing:-4px;
    margin-bottom:25px;
}

.hero h1 span{
    color:var(--green);
}

.hero-text{
    color:#d2dad5;
    font-size:19px;
    max-width:690px;
    margin-bottom:32px;
}

.hero-actions{
    display:flex;
    gap:12px;
    flex-wrap:wrap;
}

.hero-proof{
    margin-top:55px;
    display:flex;
    gap:14px;
    flex-wrap:wrap;
}

.proof{
    padding:12px 16px;
    background:rgba(0,0,0,.28);
    backdrop-filter:blur(12px);
    border:1px solid var(--line);
    border-radius:15px;
    color:#dce4df;
    font-size:13px;
}

/* =========================================================
   INTRO / MISSION
   ========================================================= */

.mission-grid{
    grid-template-columns:1.1fr .9fr;
    align-items:stretch;
}

.mission-main{
    padding:40px;
    border-radius:var(--radius);
    background:
      linear-gradient(135deg,rgba(185,230,124,.09),transparent),
      var(--card);
    border:1px solid var(--line);
    box-shadow:var(--shadow);
}

.mission-main h3{
    font-size:29px;
    margin-bottom:15px;
}

.mission-main p{
    color:var(--muted);
    font-size:16px;
}

.mission-list{
    display:grid;
    gap:14px;
    margin-top:25px;
}

.mission-item{
    display:flex;
    gap:12px;
    align-items:flex-start;
}

.mission-icon{
    min-width:38px;
    height:38px;
    border-radius:11px;
    background:rgba(185,230,124,.1);
    display:grid;
    place-items:center;
}

.mission-item strong{
    display:block;
    margin-bottom:2px;
}

.mission-item span{
    color:var(--muted);
    font-size:13px;
}

.stats{
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:15px;
}

.stat{
    padding:28px;
    border:1px solid var(--line);
    border-radius:20px;
    background:var(--card);
    display:flex;
    flex-direction:column;
    justify-content:center;
}

.stat-number{
    font-size:38px;
    color:var(--green);
    font-weight:900;
}

.stat span{
    color:var(--muted);
    font-size:13px;
}

/* =========================================================
   FEATURE CARDS
   ========================================================= */

.feature-grid{
    grid-template-columns:repeat(4,1fr);
}

.feature{
    min-height:220px;
    padding:26px;
    background:var(--card);
    border:1px solid var(--line);
    border-radius:22px;
    transition:.3s;
    position:relative;
    overflow:hidden;
}

.feature:hover{
    transform:translateY(-7px);
    border-color:rgba(185,230,124,.28);
}

.feature-icon{
    font-size:30px;
    margin-bottom:25px;
}

.feature h3{
    margin-bottom:8px;
}

.feature p{
    color:var(--muted);
    font-size:14px;
}

/* =========================================================
   HARDSHIP
   ========================================================= */

.hardship{
    background:
      linear-gradient(rgba(7,16,13,.88),rgba(7,16,13,.98)),
      url("images/hardship-road.jpg") center/cover fixed;
}

.hardship-grid{
    grid-template-columns:repeat(3,1fr);
}

.hard-card{
    background:#0d1915;
    border:1px solid var(--line);
    border-radius:22px;
    overflow:hidden;
    transition:.3s;
}

.hard-card:hover{
    transform:translateY(-5px);
}

.hard-image{
    height:210px;
    background:#15231d center/cover no-repeat;
    position:relative;
}

.hard-label{
    position:absolute;
    bottom:13px;
    right:13px;
    background:rgba(0,0,0,.7);
    padding:5px 10px;
    border-radius:999px;
    font-size:11px;
}

.hard-body{
    padding:22px;
}

.hard-body h3{
    margin-bottom:7px;
}

.hard-body p{
    color:var(--muted);
    font-size:14px;
}

/* =========================================================
   ARTICLES
   ========================================================= */

.article-grid{
    grid-template-columns:repeat(3,1fr);
}

.article-card{
    border:1px solid var(--line);
    background:var(--card);
    border-radius:22px;
    overflow:hidden;
    transition:.3s;
}

.article-card:hover{
    transform:translateY(-6px);
}

.article-image{
    height:220px;
    background:center/cover no-repeat;
}

.article-body{
    padding:24px;
}

.article-tag{
    color:var(--green);
    font-size:12px;
    font-weight:800;
}

.article-body h3{
    font-size:21px;
    line-height:1.35;
    margin:9px 0;
}

.article-body p{
    color:var(--muted);
    font-size:14px;
}

.article-footer{
    display:flex;
    justify-content:space-between;
    align-items:center;
    margin-top:20px;
}

/* =========================================================
   VIDEO
   ========================================================= */

.video-grid{
    grid-template-columns:1.3fr .7fr;
}

.video-main{
    background:var(--card);
    border:1px solid var(--line);
    border-radius:24px;
    overflow:hidden;
}

.video-frame{
    aspect-ratio:16/9;
    width:100%;
    border:0;
    background:#000;
}

.video-info{
    padding:24px;
}

.video-info p{
    color:var(--muted);
    font-size:14px;
}

.video-side{
    display:grid;
    gap:15px;
}

.video-note{
    background:var(--card);
    border:1px solid var(--line);
    padding:25px;
    border-radius:20px;
}

.video-note strong{
    display:block;
    margin-bottom:8px;
}

/* =========================================================
   POLL
   ========================================================= */

.poll-wrap{
    max-width:900px;
    background:var(--card);
    border:1px solid var(--line);
    border-radius:28px;
    padding:38px;
    margin:auto;
}

.progress{
    height:7px;
    background:rgba(255,255,255,.07);
    border-radius:99px;
    overflow:hidden;
    margin-bottom:30px;
}

.progress-bar{
    height:100%;
    width:14%;
    background:var(--green);
    transition:.3s;
}

.question-number{
    color:var(--green);
    font-size:13px;
    font-weight:900;
}

.question{
    font-size:28px;
    line-height:1.35;
    margin:9px 0 25px;
}

.options{
    display:grid;
    gap:11px;
}

.option{
    border:1px solid var(--line);
    background:#0b1712;
    color:#e9eee9;
    padding:16px 18px;
    border-radius:14px;
    text-align:right;
    font-size:15px;
    transition:.2s;
}

.option:hover{
    border-color:rgba(185,230,124,.45);
    background:rgba(185,230,124,.06);
}

.poll-actions{
    display:flex;
    justify-content:space-between;
    margin-top:25px;
    gap:10px;
}

.result{
    display:none;
    text-align:center;
    padding:20px 0;
}

.result h3{
    font-size:30px;
    color:var(--green);
    margin-bottom:10px;
}

/* =========================================================
   JOIN
   ========================================================= */

.join-section{
    background:
      radial-gradient(circle at 10% 20%,rgba(185,230,124,.09),transparent 28%),
      var(--bg2);
}

.join-grid{
    grid-template-columns:.75fr 1.25fr;
    align-items:start;
}

.join-intro{
    position:sticky;
    top:105px;
}

.join-intro h2{
    font-size:45px;
    line-height:1.1;
    margin-bottom:18px;
}

.join-intro p{
    color:var(--muted);
}

.join-points{
    display:grid;
    gap:12px;
    margin-top:25px;
}

.join-point{
    display:flex;
    gap:10px;
    color:#d8dfda;
}

.form-card{
    background:var(--card);
    border:1px solid var(--line);
    border-radius:25px;
    padding:30px;
}

.form-grid{
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:16px;
}

.field{
    display:flex;
    flex-direction:column;
    gap:7px;
}

.field.full{
    grid-column:1/-1;
}

.field label{
    font-size:13px;
    color:#d8ded9;
    font-weight:700;
}

.field input,
.field textarea,
.field select{
    width:100%;
    background:#09140f;
    color:white;
    border:1px solid var(--line);
    border-radius:12px;
    padding:13px 14px;
    outline:none;
    font-size:14px;
}

.field input:focus,
.field textarea:focus,
.field select:focus{
    border-color:rgba(185,230,124,.5);
}

.field textarea{
    min-height:130px;
    resize:vertical;
}

.checkbox-grid{
    display:grid;
    grid-template-columns:repeat(2,1fr);
    gap:9px;
}

.check{
    border:1px solid var(--line);
    padding:11px;
    border-radius:11px;
    font-size:13px;
    cursor:pointer;
}

.check input{
    accent-color:var(--green);
    margin-left:7px;
}

.form-submit{
    margin-top:20px;
    width:100%;
}

.privacy{
    margin-top:12px;
    color:#77847c;
    font-size:11px;
}

/* =========================================================
   IDEAS
   ========================================================= */

.idea-grid{
    grid-template-columns:1fr 1fr;
}

.idea-card{
    padding:32px;
    background:var(--card);
    border:1px solid var(--line);
    border-radius:23px;
}

.idea-card h3{
    font-size:25px;
    margin-bottom:9px;
}

.idea-card p{
    color:var(--muted);
    margin-bottom:20px;
}

/* =========================================================
   EVENTS
   ========================================================= */

.event-grid{
    grid-template-columns:repeat(3,1fr);
}

.event-card{
    border:1px solid var(--line);
    border-radius:22px;
    padding:27px;
    background:linear-gradient(145deg,#12231b,#0c1713);
}

.event-date{
    display:inline-block;
    color:var(--green);
    font-size:12px;
    margin-bottom:15px;
}

.event-card h3{
    font-size:23px;
    margin-bottom:10px;
}

.event-card p{
    color:var(--muted);
    font-size:14px;
    margin-bottom:20px;
}

/* =========================================================
   FOOTER
   ========================================================= */

footer{
    border-top:1px solid var(--line);
    padding:55px 0 25px;
    background:#050c09;
}

.footer-grid{
    display:grid;
    grid-template-columns:1.2fr .8fr .8fr;
    gap:35px;
}

.footer-brand p{
    color:var(--muted);
    max-width:430px;
    margin-top:13px;
}

.footer-title{
    font-weight:900;
    margin-bottom:13px;
}

.footer-links{
    display:grid;
    gap:7px;
}

.footer-links button{
    background:none;
    border:0;
    color:var(--muted);
    text-align:right;
    cursor:pointer;
}

.footer-links button:hover{
    color:var(--green);
}

.copyright{
    border-top:1px solid var(--line);
    margin-top:40px;
    padding-top:20px;
    color:#69756e;
    font-size:12px;
    display:flex;
    justify-content:space-between;
    gap:15px;
}

/* =========================================================
   MODAL
   ========================================================= */

.modal{
    position:fixed;
    inset:0;
    z-index:2000;
    background:rgba(0,0,0,.78);
    backdrop-filter:blur(10px);
    display:none;
    align-items:center;
    justify-content:center;
    padding:20px;
}

.modal.active{
    display:flex;
}

.modal-box{
    width:min(850px,100%);
    max-height:90vh;
    overflow:auto;
    background:#0d1915;
    border:1px solid var(--line);
    border-radius:25px;
    padding:35px;
    position:relative;
}

.close{
    position:absolute;
    left:18px;
    top:18px;
    width:38px;
    height:38px;
    border-radius:50%;
    border:1px solid var(--line);
    background:#111e18;
    color:white;
    font-size:18px;
}

.modal-box h2{
    font-size:35px;
    line-height:1.2;
    margin-bottom:20px;
}

.modal-box h3{
    margin:25px 0 8px;
}

.modal-box p{
    color:#b7c2bc;
    margin-bottom:12px;
}

/* =========================================================
   TOAST
   ========================================================= */

.toast{
    position:fixed;
    bottom:25px;
    left:25px;
    z-index:3000;
    background:#dff6bd;
    color:#08100b;
    padding:13px 17px;
    border-radius:13px;
    font-weight:800;
    font-size:13px;
    transform:translateY(100px);
    opacity:0;
    transition:.3s;
}

.toast.show{
    transform:translateY(0);
    opacity:1;
}

/* =========================================================
   RESPONSIVE
   ========================================================= */

@media(max-width:1000px){

    .feature-grid{
        grid-template-columns:1fr 1fr;
    }

    .hardship-grid,
    .article-grid,
    .event-grid{
        grid-template-columns:1fr 1fr;
    }

    .mission-grid,
    .video-grid,
    .join-grid{
        grid-template-columns:1fr;
    }

    .join-intro{
        position:static;
    }

    .footer-grid{
        grid-template-columns:1fr 1fr;
    }
}

@media(max-width:760px){

    .container{
        width:min(var(--max),calc(100% - 26px));
    }

    .section{
        padding:75px 0;
    }

    .nav-links{
        display:none;
        position:absolute;
        top:76px;
        right:12px;
        left:12px;
        padding:10px;
        background:#0a1511;
        border:1px solid var(--line);
        border-radius:18px;
        flex-direction:column;
        align-items:stretch;
    }

    .nav-links.open{
        display:flex;
    }

    .nav-links button{
        width:100%;
        text-align:right;
    }

    .nav-join{
        margin:0;
    }

    .menu-btn{
        display:block;
    }

    .hero{
        min-height:850px;
        background:
          linear-gradient(rgba(7,16,13,.78),rgba(7,16,13,.96)),
          url("images/hero-winter.jpg") center/cover;
    }

    .hero h1{
        font-size:54px;
        letter-spacing:-2px;
    }

    .hero-text{
        font-size:16px;
    }

    .feature-grid,
    .hardship-grid,
    .article-grid,
    .event-grid,
    .idea-grid{
        grid-template-columns:1fr;
    }

    .stats{
        grid-template-columns:1fr 1fr;
    }

    .form-grid{
        grid-template-columns:1fr;
    }

    .field.full{
        grid-column:auto;
    }

    .checkbox-grid{
        grid-template-columns:1fr;
    }

    .footer-grid{
        grid-template-columns:1fr;
    }

    .copyright{
        flex-direction:column;
    }

    .modal-box{
        padding:25px 20px;
    }
}

/* =========================================================
   ACCESSIBILITY
   ========================================================= */

:focus-visible{
    outline:2px solid var(--green);
    outline-offset:3px;
}

::selection{
    background:var(--green);
    color:#07100d;
}
</style>
</head>

<body>

<!-- =======================================================
     HEADER
======================================================= -->

<header>
    <div class="container nav">

        <a href="#home" class="logo">
            <span class="logo-mark">⛰</span>
            <span>
                صوت الجبل
                <small>من الوعي إلى المشاركة</small>
            </span>
        </a>

        <button class="menu-btn" onclick="toggleMenu()" aria-label="القائمة">
            ☰
        </button>

        <nav class="nav-links" id="navLinks">
            <button onclick="go('home')">الرئيسية</button>
            <button onclick="go('hardship')">معاناة الجبل</button>
            <button onclick="go('art
