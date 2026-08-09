```html
<!DOCTYPE html>
<html lang="gu">
<head>
  <meta charset="UTF-8">

  <meta name="viewport"
        content="width=device-width, initial-scale=1.0">

  <title>ગુજરાતી Trader | Market Updates</title>

  <meta name="description"
        content="ગુજરાતી Trader - Stock market related updates and educational information.">

  <meta name="theme-color" content="#07100a">

  <!-- =====================================================
       META PIXEL
       ===================================================== -->
  <script>
    !function(f,b,e,v,n,t,s)
    {
      if(f.fbq)return;
      n=f.fbq=function(){
        n.callMethod ?
        n.callMethod.apply(n,arguments) :
        n.queue.push(arguments)
      };

      if(!f._fbq)f._fbq=n;

      n.push=n;
      n.loaded=!0;
      n.version='2.0';
      n.queue=[];

      t=b.createElement(e);
      t.async=!0;
      t.src=v;

      s=b.getElementsByTagName(e)[0];
      s.parentNode.insertBefore(t,s)
    }
    (window, document, 'script',
     'https://connect.facebook.net/en_US/fbevents.js');

    fbq('init', '1037527839255522');
    fbq('track', 'PageView');
  </script>

  <noscript>
    <img
      height="1"
      width="1"
      style="display:none"
      src="https://www.facebook.com/tr?id=1037527839255522&ev=PageView&noscript=1"
      alt="">
  </noscript>

  <!-- Fonts -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>

  <link
    href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=Noto+Sans+Gujarati:wght@400;500;600;700;800&display=swap"
    rel="stylesheet">

  <style>

    /* =====================================================
       RESET
       ===================================================== */

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    html {
      scroll-behavior: smooth;
    }

    body {
      width: 100%;
      min-height: 100vh;

      overflow-x: hidden;

      font-family:
        "Noto Sans Gujarati",
        "Inter",
        sans-serif;

      color: #ffffff;

      background:
        radial-gradient(
          circle at 50% -10%,
          rgba(34,197,94,.14),
          transparent 38%
        ),
        #07100a;
    }

    a {
      color: inherit;
      text-decoration: none;
    }

    img {
      max-width: 100%;
      display: block;
    }

    button,
    a {
      -webkit-tap-highlight-color: transparent;
    }

    /* =====================================================
       CONTAINER
       ===================================================== */

    .container {
      width: calc(100% - 24px);
      max-width: 1050px;
      margin: 0 auto;
    }

    /* =====================================================
       TOP BAR
       ===================================================== */

    .topbar {
      padding: 12px 0 0;
    }

    .topbar-inner {
      min-height: 60px;

      display: flex;
      align-items: center;
      justify-content: space-between;

      gap: 10px;

      padding: 9px 11px;

      border-radius: 16px;

      background: rgba(255,255,255,.045);

      border:
        1px solid rgba(255,255,255,.075);

      backdrop-filter: blur(12px);
      -webkit-backdrop-filter: blur(12px);
    }

    .brand {
      display: flex;
      align-items: center;
      gap: 9px;

      min-width: 0;
    }

    .brand-logo {
      width: 40px;
      height: 40px;

      flex: 0 0 40px;

      border-radius: 50%;

      object-fit: cover;

      background: #ffffff;

      border:
        2px solid rgba(34,197,94,.75);
    }

    .brand-info {
      min-width: 0;
    }

    .brand-name {
      font-family: "Noto Sans Gujarati", sans-serif;

      font-size: 14px;
      line-height: 1.2;

      font-weight: 800;

      white-space: nowrap;
    }

    .brand-subtitle {
      margin-top: 2px;

      font-family: Inter, sans-serif;

      color: #7f8b82;

      font-size: 8px;
      letter-spacing: .7px;

      white-space: nowrap;
    }

    .status {
      display: flex;
      align-items: center;
      gap: 5px;

      color: #89958c;

      font-family: Inter, sans-serif;

      font-size: 8px;

      white-space: nowrap;
    }

    .status-dot {
      width: 6px;
      height: 6px;

      flex: 0 0 6px;

      border-radius: 50%;

      background: #22c55e;

      box-shadow:
        0 0 9px rgba(34,197,94,.7);
    }

    /* =====================================================
       HERO
       ===================================================== */

    .hero {
      text-align: center;

      padding:
        35px 0
        25px;
    }

    .hero-logo-wrap {
      width: 94px;
      height: 94px;

      margin: 0 auto 18px;

      padding: 4px;

      border-radius: 50%;

      background: #ffffff;

      box-shadow:
        0 0 0 1px rgba(34,197,94,.5),
        0 14px 35px rgba(0,0,0,.35);
    }

    .hero-logo {
      width: 100%;
      height: 100%;

      object-fit: cover;

      border-radius: 50%;
    }

    .eyebrow {
      display: inline-flex;
      align-items: center;
      gap: 6px;

      padding: 6px 10px;

      border-radius: 999px;

      color: #7bea9c;

      background:
        rgba(34,197,94,.08);

      border:
        1px solid rgba(34,197,94,.18);

      font-family: Inter, sans-serif;

      font-size: 9px;
      font-weight: 700;

      margin-bottom: 13px;
    }

    .eyebrow-dot {
      width: 5px;
      height: 5px;

      border-radius: 50%;

      background: #22c55e;
    }

    .hero h1 {
      max-width: 390px;

      margin: 0 auto;

      font-size: clamp(31px, 9vw, 48px);

      line-height: 1.08;

      letter-spacing: -1.4px;

      font-weight: 800;
    }

    .highlight {
      color: #39d866;
    }

    .hero-description {
      max-width: 370px;

      margin: 15px auto 0;

      padding: 0 5px;

      color: #aab5ad;

      font-size: 13px;

      line-height: 1.7;
    }

    /* =====================================================
       CTA
       ===================================================== */

    .cta-area {
      width: 100%;

      margin-top: 22px;
    }

    .telegram-btn {
      width: 100%;
      max-width: 370px;

      min-height: 52px;

      margin: 0 auto;

      display: flex;
      align-items: center;
      justify-content: center;

      gap: 9px;

      padding: 14px 18px;

      border-radius: 14px;

      background:
        linear-gradient(
          135deg,
          #22c55e,
          #16a34a
        );

      color: #ffffff;

      font-family: Inter, sans-serif;

      font-size: 14px;

      font-weight: 800;

      box-shadow:
        0 10px 28px rgba(34,197,94,.20);

      transition:
        transform .18s ease,
        box-shadow .18s ease;
    }

    .telegram-btn:active {
      transform: scale(.98);
    }

    .telegram-icon {
      width: 19px;
      height: 19px;

      fill: currentColor;
    }

    .cta-note {
      margin-top: 8px;

      color: #68736b;

      font-family: Inter, sans-serif;

      font-size: 9px;
    }

    /* =====================================================
       SECTION
       ===================================================== */

    .section {
      padding: 20px 0;
    }

    .section-title {
      text-align: center;

      margin-bottom: 16px;
    }

    .section-title h2 {
      font-size: 22px;

      line-height: 1.25;

      font-weight: 800;
    }

    .section-title p {
      margin-top: 6px;

      color: #737e76;

      font-family: Inter, sans-serif;

      font-size: 10px;
    }

    /* =====================================================
       FEATURE CARDS
       ===================================================== */

    .features {
      display: grid;

      grid-template-columns: 1fr;

      gap: 9px;
    }

    .feature {
      display: grid;

      grid-template-columns: 42px 1fr;

      column-gap: 12px;

      align-items: center;

      padding: 14px;

      border-radius: 16px;

      background:
        linear-gradient(
          145deg,
          rgba(255,255,255,.055),
          rgba(255,255,255,.022)
        );

      border:
        1px solid rgba(255,255,255,.065);
    }

    .feature-icon {
      width: 42px;
      height: 42px;

      display: flex;
      align-items: center;
      justify-content: center;

      grid-row: span 2;

      border-radius: 12px;

      color: #43dc6c;

      background:
        rgba(34,197,94,.09);

      border:
        1px solid rgba(34,197,94,.14);

      font-family: Inter, sans-serif;

      font-size: 17px;
      font-weight: 700;
    }

    .feature h3 {
      align-self: end;

      font-size: 13px;

      line-height: 1.3;

      font-weight: 800;
    }

    .feature p {
      align-self: start;

      margin-top: 3px;

      color: #7f8a82;

      font-size: 10px;

      line-height: 1.55;
    }

    /* =====================================================
       INFORMATION BOX
       ===================================================== */

    .info-box {
      padding: 18px;

      border-radius: 18px;

      background:
        linear-gradient(
          135deg,
          rgba(34,197,94,.085),
          rgba(255,255,255,.025)
        );

      border:
        1px solid rgba(34,197,94,.13);
    }

    .info-box h2 {
      font-size: 19px;

      line-height: 1.3;

      font-weight: 800;
    }

    .info-box > p {
      margin-top: 8px;

      color: #929d95;

      font-size: 11px;

      line-height: 1.7;
    }

    .check-list {
      display: grid;

      grid-template-columns: 1fr;

      gap: 8px;

      margin-top: 14px;
    }

    .check-item {
      display: flex;

      align-items: center;

      gap: 8px;

      color: #b6c0b9;

      font-size: 10px;
    }

    .check {
      width: 18px;
      height: 18px;

      flex: 0 0 18px;

      display: flex;
      align-items: center;
      justify-content: center;

      border-radius: 50%;

      color: #42db6c;

      background:
        rgba(34,197,94,.10);

      font-family: Inter, sans-serif;

      font-size: 9px;
      font-weight: 800;
    }

    /* =====================================================
       FINAL CTA
       ===================================================== */

    .final-cta {
      text-align: center;

      padding:
        20px 0
        32px;
    }

    .final-cta h2 {
      font-size: 21px;

      line-height: 1.3;

      font-weight: 800;
    }

    .final-cta p {
      max-width: 330px;

      margin: 7px auto 15px;

      color: #7d8880;

      font-size: 10px;

      line-height: 1.6;
    }

    /* =====================================================
       DISCLAIMER
       ===================================================== */

    .disclaimer {
      padding:
        18px 0
        25px;

      border-top:
        1px solid rgba(255,255,255,.055);
    }

    .disclaimer-text {
      max-width: 750px;

      margin: 0 auto;

      text-align: center;

      color: #626d65;

      font-family: Inter, sans-serif;

      font-size: 8px;

      line-height: 1.7;
    }

    .disclaimer-title {
      color: #7c877f;

      font-size: 9px;

      font-weight: 700;

      margin-bottom: 4px;
    }

    /* =====================================================
       FOOTER
       ===================================================== */

    footer {
      padding: 0 0 25px;

      text-align: center;

      color: #4f5952;

      font-family: Inter, sans-serif;

      font-size: 8px;
    }

    .footer-name {
      color: #707b72;

      font-weight: 700;

      margin-bottom: 3px;
    }

    /* =====================================================
       TABLET
       ===================================================== */

    @media (min-width: 600px) {

      .container {
        width: calc(100% - 40px);
      }

      .hero {
        padding-top: 50px;
      }

      .hero-logo-wrap {
        width: 110px;
        height: 110px;
      }

      .hero h1 {
        font-size: 48px;
        max-width: 650px;
      }

      .hero-description {
        font-size: 14px;
        max-width: 580px;
      }

      .features {
        grid-template-columns:
          repeat(3, 1fr);

        gap: 12px;
      }

      .feature {
        display: block;
        padding: 18px;
      }

      .feature-icon {
        margin-bottom: 13px;
      }

      .feature h3 {
        margin-bottom: 4px;
      }

      .check-list {
        grid-template-columns:
          repeat(2, 1fr);
      }
    }

    /* =====================================================
       DESKTOP
       ===================================================== */

    @media (min-width: 900px) {

      .container {
        width: min(100% - 48px, 1050px);
      }

      .hero {
        padding-top: 60px;
      }

      .hero h1 {
        font-size: 60px;
      }

      .hero-description {
        font-size: 15px;
      }

      .telegram-btn {
        min-height: 54px;
      }
    }

    /* =====================================================
       VERY SMALL PHONES
       ===================================================== */

    @media (max-width: 340px) {

      .container {
        width: calc(100% - 18px);
      }

      .topbar-inner {
        padding: 8px;
      }

      .brand-logo {
        width: 36px;
        height: 36px;

        flex-basis: 36px;
      }

      .brand-name {
        font-size: 12px;
      }

      .status {
        display: none;
      }

      .hero {
        padding-top: 28px;
      }

      .hero-logo-wrap {
        width: 84px;
        height: 84px;
      }

      .hero h1 {
        font-size: 29px;
      }

      .hero-description {
        font-size: 12px;
      }

      .telegram-btn {
        min-height: 50px;
      }
    }

    /* =====================================================
       REDUCED MOTION
       ===================================================== */

    @media (prefers-reduced-motion: reduce) {

      html {
        scroll-behavior: auto;
      }

      *,
      *::before,
      *::after {
        transition: none !important;
      }
    }

  </style>
</head>

<body>

  <!-- =====================================================
       TOP BAR
       ===================================================== -->

  <header class="topbar">

    <div class="container">

      <div class="topbar-inner">

        <div class="brand">

          <img
            class="brand-logo"
            src="https://uploads.onecompiler.io/44rdhnhnp/1785086478000/WhatsApp%20Image%202026-07-26%20at%2010.50.28%20PM.jpeg"
            alt="ગુજરાતી Trader Logo"
            width="40"
            height="40"
            fetchpriority="high">

          <div class="brand-info">

            <div class="brand-name">
              ગુજરાતી Trader
            </div>

            <div class="brand-subtitle">
              MARKET UPDATES
            </div>

          </div>

        </div>

        <div class="status">
          <span class="status-dot"></span>
          Telegram
        </div>

      </div>

    </div>

  </header>


  <!-- =====================================================
       MAIN
       ===================================================== -->

  <main>

    <!-- HERO -->

    <section class="hero">

      <div class="container">

        <div class="hero-logo-wrap">

          <img
            class="hero-logo"
            src="https://uploads.onecompiler.io/44rdhnhnp/1785086478000/WhatsApp%20Image%202026-07-26%20at%2010.50.28%20PM.jpeg"
            alt="ગુજરાતી Trader"
            width="94"
            height="94"
            fetchpriority="high">

        </div>


        <div class="eyebrow">

          <span class="eyebrow-dot"></span>

          ગુજરાતી Trader Community

        </div>


        <h1>

          Stay Updated With

          <span class="highlight">
            Market Updates
          </span>

        </h1>


        <p class="hero-description">

          ગુજરાતી Trader Telegram community દ્વારા
          stock market સંબંધિત updates અને
          educational information મેળવો.

        </p>


        <div class="cta-area">

          <a
            class="telegram-btn"
            href="https://t.me/+FWwle06Fb2QxMzI1"
            target="_blank"
            rel="noopener noreferrer"
            onclick="trackTelegramClick();">

            <svg
              class="telegram-icon"
              viewBox="0 0 24 24"
              aria-hidden="true">

              <path d="M21.5 3.5 2.8 10.7c-1.3.5-1.3 1.2-.2 1.5l4.8 1.5 1.8 5.7c.2.6.1.8.7.8.5 0 .7-.2 1-.5l2.3-2.2 4.8 3.5c.9.5 1.5.3 1.7-.8l3.2-15.2c.3-1.3-.5-1.9-1.4-1.5ZM8.1 13.3l10.9-6.9c.5-.3 1-.1.6.2l-8.9 8-.3 3.1-1.5-4.4-.8-.3Z"/>

            </svg>

            Join Telegram

          </a>


          <div class="cta-note">
            Tap the button to open Telegram
          </div>

        </div>

      </div>

    </section>


    <!-- FEATURES -->

    <section class="section">

      <div class="container">

        <div class="section-title">

          <h2>
            Community માં શું મળશે?
          </h2>

          <p>
            Useful market-related information
          </p>

        </div>


        <div class="features">


          <article class="feature">

            <div class="feature-icon">
              ↗
            </div>

            <h3>
              Market Updates
            </h3>

            <p>
              Market સંબંધિત મહત્વપૂર્ણ
              updates અને information.
            </p>

          </article>


          <article class="feature">

            <div class="feature-icon">
              ◈
            </div>

            <h3>
              Educational Content
            </h3>

            <p>
              Trading અને market વિષયક
              learning information.
            </p>

          </article>


          <article class="feature">

            <div class="feature-icon">
              ✓
            </div>

            <h3>
              Gujarati Community
            </h3>

            <p>
              Gujarati language માં
              market-related community.
            </p>

          </article>


        </div>

      </div>

    </section>


    <!-- INFORMATION -->

    <section class="section">

      <div class="container">

        <div class="info-box">

          <h2>
            Telegram પર જોડાઓ
          </h2>

          <p>
            Stock market સંબંધિત updates અને
            educational information follow કરવા
            માટે અમારી Telegram community જોઈ શકો છો.
          </p>


          <div class="check-list">


            <div class="check-item">

              <span class="check">
                ✓
              </span>

              Market-related updates

            </div>


            <div class="check-item">

              <span class="check">
                ✓
              </span>

              Educational information

            </div>


            <div class="check-item">

              <span class="check">
                ✓
              </span>

              Gujarati language content

            </div>


            <div class="check-item">

              <span class="check">
                ✓
              </span>

              Direct Telegram access

            </div>


          </div>

        </div>

      </div>

    </section>


    <!-- FINAL CTA -->

    <section class="final-cta">

      <div class="container">

        <h2>
          ગુજરાતી Trader સાથે જોડાઓ
        </h2>

        <p>
          Telegram community જોવા માટે
          નીચેનું button પસંદ કરો.
        </p>


        <a
          class="telegram-btn"
          href="https://t.me/+FWwle06Fb2QxMzI1"
          target="_blank"
          rel="noopener noreferrer"
          onclick="trackTelegramClick();">

          <svg
            class="telegram-icon"
            viewBox="0 0 24 24"
            aria-hidden="true">

            <path d="M21.5 3.5 2.8 10.7c-1.3.5-1.3 1.2-.2 1.5l4.8 1.5 1.8 5.7c.2.6.1.8.7.8.5 0 .7-.2 1-.5l2.3-2.2 4.8 3.5c.9.5 1.5.3 1.7-.8l3.2-15.2c.3-1.3-.5-1.9-1.4-1.5ZM8.1 13.3l10.9-6.9c.5-.3 1-.1.6.2l-8.9 8-.3 3.1-1.5-4.4-.8-.3Z"/>

          </svg>

          Join Telegram

        </a>

      </div>

    </section>

  </main>


  <!-- =====================================================
       DISCLAIMER
       ===================================================== -->

  <section class="disclaimer">

    <div class="container">

      <div class="disclaimer-text">

        <div class="disclaimer-title">
          Disclaimer
        </div>

        This page is for informational and educational
        purposes only. Stock market investments are
        subject to market risks. Please conduct your
        own research and consult a qualified financial
        professional before making investment decisions.

        Past performance does not guarantee future results.

      </div>

    </div>

  </section>


  <!-- =====================================================
       FOOTER
       ===================================================== -->

  <footer>

    <div class="container">

      <div class="footer-name">
        ગુજરાતી Trader
      </div>

      © 2026 Gujarati Trader. All rights reserved.

    </div>

  </footer>


  <!-- =====================================================
       TELEGRAM CLICK TRACKING
       ===================================================== -->

  <script>

    function trackTelegramClick() {

      if (typeof fbq === "function") {

        fbq(
          "trackCustom",
          "TelegramJoinClick"
        );

      }

    }

  </script>


  <!-- =====================================================
       BASIC PERFORMANCE
       ===================================================== -->

  <script>

    window.addEventListener(
      "error",
      function () {
        /* Prevent non-critical errors
           from breaking the page */
      },
      true
    );

  </script>

</body>
</html>
```
