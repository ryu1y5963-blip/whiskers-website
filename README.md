[style.css.rtf](https://github.com/user-attachments/files/33074845/style.css.rtf)
{\rtf1\ansi\ansicpg932\cocoartf2822
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fnil\fcharset0 HelveticaNeue;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\deftab560
\pard\pardeftab560\slleading20\pardirnatural\partightenfactor0

\f0\fs26 \cf0 /* --- \uc0\u22522 \u26412 \u35373 \u23450  --- */\
* \{\
    margin: 0;\
    padding: 0;\
    box-sizing: border-box;\
\}\
\
body \{\
    font-family: 'Noto Sans JP', 'Plus Jakarta Sans', sans-serif;\
    background-color: #0d0e12;\
    color: #ffffff;\
    line-height: 1.6;\
\}\
\
a \{\
    text-decoration: none;\
    color: inherit;\
\}\
\
.container \{\
    max-width: 1100px;\
    margin: 0 auto;\
    padding: 0 20px;\
\}\
\
/* --- \uc0\u12504 \u12483 \u12480 \u12540  --- */\
.header \{\
    position: fixed;\
    top: 0;\
    left: 0;\
    width: 100%;\
    background: rgba(13, 14, 18, 0.85);\
    backdrop-filter: blur(10px);\
    z-index: 1000;\
    border-bottom: 1px solid rgba(255, 255, 255, 0.1);\
\}\
\
.header-container \{\
    max-width: 1200px;\
    margin: 0 auto;\
    display: flex;\
    justify-content: space-between;\
    align-items: center;\
    padding: 15px 25px;\
\}\
\
.logo \{\
    display: flex;\
    align-items: center;\
    gap: 10px;\
    font-weight: 900;\
    font-size: 1.4rem;\
    color: #ff2a85;\
\}\
\
.nav ul \{\
    display: flex;\
    list-style: none;\
    align-items: center;\
    gap: 25px;\
\}\
\
.nav a \{\
    font-weight: 700;\
    font-size: 0.9rem;\
    letter-spacing: 1px;\
    transition: color 0.3s;\
\}\
\
.nav a:hover \{\
    color: #ff2a85;\
\}\
\
.nav-btn \{\
    background: linear-gradient(135deg, #ff2a85, #7928ca);\
    padding: 8px 18px;\
    border-radius: 20px;\
\}\
\
/* --- \uc0\u12498 \u12540 \u12525 \u12540 \u12475 \u12463 \u12471 \u12519 \u12531  --- */\
.hero \{\
    min-height: 100vh;\
    display: flex;\
    align-items: center;\
    justify-content: center;\
    text-align: center;\
    background: radial-gradient(circle at center, #1f112e 0%, #0d0e12 70%);\
    padding: 120px 20px 60px;\
\}\
\
.hero-sub \{\
    color: #00dfd8;\
    font-weight: 800;\
    letter-spacing: 2px;\
    margin-bottom: 15px;\
\}\
\
.hero-title \{\
    font-size: 2.8rem;\
    font-weight: 900;\
    line-height: 1.3;\
    margin-bottom: 20px;\
\}\
\
.highlight \{\
    background: linear-gradient(135deg, #ff2a85, #00dfd8);\
    -webkit-background-clip: text;\
    -webkit-text-fill-color: transparent;\
\}\
\
.hero-desc \{\
    color: #a0a0ab;\
    max-width: 600px;\
    margin: 0 auto 35px;\
    font-size: 1rem;\
\}\
\
.hero-buttons \{\
    display: flex;\
    gap: 15px;\
    justify-content: center;\
    flex-wrap: wrap;\
\}\
\
.btn \{\
    padding: 14px 32px;\
    border-radius: 30px;\
    font-weight: 700;\
    transition: transform 0.2s, box-shadow 0.2s;\
\}\
\
.btn:hover \{\
    transform: translateY(-2px);\
\}\
\
.primary-btn \{\
    background: linear-gradient(135deg, #ff2a85, #7928ca);\
    box-shadow: 0 4px 20px rgba(255, 42, 133, 0.4);\
\}\
\
.secondary-btn \{\
    border: 1px solid rgba(255, 255, 255, 0.3);\
\}\
\
/* --- \uc0\u12475 \u12463 \u12471 \u12519 \u12531 \u12479 \u12452 \u12488 \u12523  --- */\
.section-title \{\
    text-align: center;\
    font-size: 2.2rem;\
    font-weight: 900;\
    margin-bottom: 50px;\
    letter-spacing: 1px;\
\}\
\
.section-title span \{\
    display: block;\
    font-size: 0.9rem;\
    color: #ff2a85;\
    margin-top: 5px;\
\}\
\
/* --- ABOUT --- */\
.about \{\
    padding: 100px 0;\
\}\
\
.features-grid \{\
    display: grid;\
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));\
    gap: 25px;\
\}\
\
.feature-card \{\
    background: #161821;\
    padding: 35px 25px;\
    border-radius: 16px;\
    border: 1px solid rgba(255, 255, 255, 0.05);\
    text-align: center;\
\}\
\
.feature-icon \{\
    font-size: 2.5rem;\
    margin-bottom: 15px;\
\}\
\
.feature-card h3 \{\
    margin-bottom: 12px;\
    font-size: 1.2rem;\
\}\
\
.feature-card p \{\
    color: #a0a0ab;\
    font-size: 0.9rem;\
\}\
\
/* --- TALENTS --- */\
.talents \{\
    padding: 100px 0;\
    background-color: #12131a;\
\}\
\
.talent-grid \{\
    display: grid;\
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));\
    gap: 30px;\
\}\
\
.talent-card \{\
    background: #1b1d28;\
    border-radius: 20px;\
    overflow: hidden;\
    border: 1px solid rgba(255, 255, 255, 0.05);\
    transition: transform 0.3s;\
\}\
\
.talent-card:hover \{\
    transform: translateY(-8px);\
\}\
\
.talent-avatar \{\
    height: 260px;\
    background-size: cover;\
    background-position: center;\
\}\
\
.talent-info \{\
    padding: 20px;\
\}\
\
.talent-tag \{\
    background: rgba(255, 42, 133, 0.2);\
    color: #ff2a85;\
    padding: 3px 10px;\
    border-radius: 10px;\
    font-size: 0.75rem;\
    font-weight: 700;\
\}\
\
.talent-info h3 \{\
    margin: 8px 0 2px;\
    font-size: 1.3rem;\
\}\
\
.talent-mark \{\
    font-size: 0.85rem;\
    margin-bottom: 10px;\
\}\
\
.talent-bio \{\
    color: #a0a0ab;\
    font-size: 0.85rem;\
\}\
\
/* --- AUDITION / FORM --- */\
.audition \{\
    padding: 100px 0;\
\}\
\
.audition-box \{\
    background: #161821;\
    border-radius: 24px;\
    padding: 50px 30px;\
    border: 1px solid rgba(255, 42, 133, 0.2);\
    max-width: 700px;\
    margin: 0 auto;\
\}\
\
.audition-intro \{\
    text-align: center;\
    color: #a0a0ab;\
    margin-bottom: 35px;\
    font-size: 0.95rem;\
\}\
\
.audition-form .form-group \{\
    margin-bottom: 20px;\
\}\
\
.audition-form label \{\
    display: block;\
    margin-bottom: 8px;\
    font-size: 0.9rem;\
    font-weight: 700;\
\}\
\
.required \{\
    background: #ff2a85;\
    color: #fff;\
    font-size: 0.65rem;\
    padding: 2px 6px;\
    border-radius: 4px;\
    margin-left: 6px;\
\}\
\
.audition-form input,\
.audition-form textarea \{\
    width: 100%;\
    padding: 12px 16px;\
    background: #0d0e12;\
    border: 1px solid rgba(255, 255, 255, 0.1);\
    border-radius: 8px;\
    color: #fff;\
    font-size: 0.95rem;\
    outline: none;\
\}\
\
.audition-form input:focus,\
.audition-form textarea:focus \{\
    border-color: #ff2a85;\
\}\
\
.submit-btn \{\
    width: 100%;\
    padding: 15px;\
    background: linear-gradient(135deg, #ff2a85, #7928ca);\
    color: #fff;\
    border: none;\
    border-radius: 30px;\
    font-size: 1rem;\
    font-weight: 700;\
    cursor: pointer;\
    margin-top: 10px;\
\}\
\
/* --- FOOTER --- */\
.footer \{\
    padding: 40px 0;\
    text-align: center;\
    border-top: 1px solid rgba(255, 255, 255, 0.05);\
\}\
\
.footer-logo \{\
    font-size: 1.5rem;\
    font-weight: 900;\
    color: #ff2a85;\
    margin-bottom: 8px;\
\}\
\
.copyright \{\
    color: #666;\
    font-size: 0.8rem;\
\}\
\
/* --- \uc0\u12473 \u12510 \u12507 \u23550 \u24540  (\u12524 \u12473 \u12509 \u12531 \u12471 \u12502 ) --- */\
@media (max-width: 768px) \{\
    .hero-title \{\
        font-size: 2rem;\
    \}\
    .audition-box \{\
        padding: 30px 20px;\
    \}\
\}\
}
