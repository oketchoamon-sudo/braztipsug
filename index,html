<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=yes">
  <title>BRAZ TIPS UG · 95% Accuracy Odds</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', Roboto, system-ui, -apple-system, BlinkMacSystemFont, sans-serif; }

    :root {
      --bg-dark: #05080f; --bg-card: #0b0f1a; --bg-elevated: #111827;
      --border-dark: #1e2a3a; --border-light: #2a3a50;
      --blue: #1e90ff; --blue-deep: #0a4c8c; --blue-light: #4da6ff;
      --red: #e63946; --red-deep: #a4161a; --red-bright: #ff4d5e;
      --yellow: #ffd166; --yellow-bright: #ffe066;
      --text-light: #f0f4fa; --text-muted: #9aaec9;
    }

    body { background: var(--bg-dark); color: var(--text-light); line-height: 1.5; padding: 1rem; min-height: 100vh; display: flex; flex-direction: column; }
    .container { max-width: 1300px; margin: 0 auto; width: 100%; flex: 1; }

    /* HEADER */
    .header { display: flex; flex-wrap: wrap; justify-content: space-between; align-items: center; padding: 1rem 1.5rem; background: var(--bg-card); border-radius: 2rem; border: 1px solid var(--border-dark); box-shadow: 0 0 25px rgba(30, 144, 255, 0.15), 0 0 10px rgba(230, 57, 70, 0.1); margin-bottom: 2rem; }
    .logo h1 { font-size: 1.8rem; font-weight: 800; letter-spacing: -0.5px; background: linear-gradient(135deg, var(--blue), var(--red), var(--yellow)); -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text; }
    .logo span { font-size: 0.8rem; color: var(--text-muted); display: block; letter-spacing: 2px; }
    .badge-95 { background: rgba(230, 57, 70, 0.15); border: 1px solid var(--red); color: var(--red-bright); padding: 0.4rem 1rem; border-radius: 40px; font-weight: 600; font-size: 0.9rem; display: flex; align-items: center; gap: 0.5rem; backdrop-filter: blur(4px); }
    .badge-95 i { font-size: 1.1rem; color: var(--yellow); }

    /* HERO */
    .hero { background: var(--bg-card); border: 1px solid var(--border-dark); border-radius: 2rem; padding: 2rem 1.8rem; margin-bottom: 2.5rem; box-shadow: 0 10px 30px rgba(0, 0, 0, 0.8), 0 0 0 1px rgba(30, 144, 255, 0.1); position: relative; overflow: hidden; }
    .hero::before { content: ""; position: absolute; top: -30%; right: -10%; width: 350px; height: 350px; background: radial-gradient(circle, rgba(230, 57, 70, 0.15), transparent 70%); border-radius: 50%; z-index: 0; }
    .hero::after { content: ""; position: absolute; bottom: -40%; left: -10%; width: 300px; height: 300px; background: radial-gradient(circle, rgba(255, 209, 102, 0.1), transparent 70%); border-radius: 50%; z-index: 0; }
    .hero h2 { font-size: 2rem; font-weight: 700; margin-bottom: 0.8rem; position: relative; z-index: 1; color: var(--text-light); }
    .hero h2 i { color: var(--yellow); margin-right: 8px; }
    .hero p { font-size: 1.1rem; color: var(--text-muted); max-width: 700px; position: relative; z-index: 1; }
    .highlight { color: var(--blue-light); font-weight: 600; }
    .highlight-red { color: var(--red-bright); font-weight: 600; }

    /* STATS */
    .stats { display: flex; flex-wrap: wrap; gap: 1.5rem; margin-top: 1.5rem; position: relative; z-index: 1; }
    .stat-item { display: flex; align-items: center; gap: 0.6rem; background: var(--bg-elevated); padding: 0.6rem 1.2rem; border-radius: 40px; border: 1px solid var(--border-light); font-weight: 500; font-size: 0.95rem; color: var(--text-light); }
    .stat-item i { color: var(--blue); }
    .stat-item:nth-child(2) i { color: var(--red); }
    .stat-item:nth-child(3) i { color: var(--yellow); }
    .stat-item:nth-child(4) i { color: var(--blue-light); }
    /* SECTION TITLE */
    .section-title { font-size: 1.6rem; font-weight: 600; margin-bottom: 1.2rem; display: flex; align-items: center; gap: 10px; color: var(--text-light); }
    .section-title i { color: var(--red); font-size: 1.8rem; }

    /* CARDS */
    .pricing-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 1.8rem; margin-bottom: 3rem; }
    .card { background: var(--bg-card); border: 1px solid var(--border-dark); border-radius: 1.8rem; padding: 1.8rem 1.5rem; transition: all 0.2s ease; display: flex; flex-direction: column; box-shadow: 0 10px 20px -10px rgba(0, 0, 0, 0.9), 0 0 0 1px rgba(30, 144, 255, 0.05); position: relative; overflow: hidden; }
    .card:hover { border-color: var(--blue); box-shadow: 0 0 25px rgba(30, 144, 255, 0.25), 0 0 0 1px rgba(230, 57, 70, 0.2); transform: translateY(-4px); }
    .card::before { content: ""; position: absolute; top: 0; left: 0; width: 100%; height: 4px; background: linear-gradient(90deg, var(--blue), var(--red), var(--yellow)); }
    .card-icon { font-size: 2.2rem; margin-bottom: 1rem; color: var(--blue); }
    .card:nth-child(2) .card-icon { color: var(--red); }
    .card:nth-child(3) .card-icon { color: var(--yellow); }
    .card:nth-child(4) .card-icon { color: var(--blue-light); }
    .card:nth-child(5) .card-icon { color: var(--red-bright); }
    .card h3 { font-size: 1.5rem; font-weight: 700; margin-bottom: 0.4rem; letter-spacing: -0.3px; color: var(--text-light); }
    .price-tag { font-size: 2rem; font-weight: 800; color: var(--text-light); margin: 0.8rem 0 0.4rem; }
    .price-tag small { font-size: 1rem; font-weight: 400; color: var(--text-muted); margin-left: 6px; }
    .odds-badge { display: inline-block; background: var(--bg-elevated); padding: 0.3rem 1rem; border-radius: 30px; font-weight: 600; color: var(--yellow); margin-bottom: 1.2rem; font-size: 0.9rem; border: 1px solid var(--border-light); }
    .features { list-style: none; margin: 1rem 0 1.8rem; flex: 1; }
    .features li { display: flex; align-items: flex-start; gap: 10px; margin-bottom: 0.7rem; font-size: 0.95rem; color: #cbd5e1; }
    .features i { color: var(--blue); font-size: 0.9rem; margin-top: 3px; }
    .features li:nth-child(2) i { color: var(--red); }
    .features li:nth-child(3) i { color: var(--yellow); }
    .features li:nth-child(4) i { color: var(--blue-light); }

    /* BUTTONS */
    .btn { display: inline-block; background: linear-gradient(135deg, var(--blue), var(--blue-deep)); border: none; border-radius: 50px; padding: 0.9rem 1.5rem; font-weight: 700; font-size: 1rem; color: #ffffff; text-align: center; text-decoration: none; cursor: pointer; transition: 0.2s; border: 1px solid var(--blue); letter-spacing: 0.3px; box-shadow: 0 6px 14px rgba(30, 144, 255, 0.3); }
    .btn i { margin-right: 8px; }
    .btn:hover { background: linear-gradient(135deg, var(--blue-light), var(--blue)); box-shadow: 0 10px 20px rgba(30, 144, 255, 0.5); transform: scale(1.02); }

    /* CONTACT */
    .contact-section { background: var(--bg-card); border: 1px solid var(--border-dark); border-radius: 2rem; padding: 2rem 1.8rem; margin-bottom: 2.5rem; display: flex; flex-wrap: wrap; gap: 2rem; justify-content: space-between; box-shadow: 0 0 20px rgba(230, 57, 70, 0.1); }
    .contact-info h3 { font-size: 1.5rem; margin-bottom: 1.5rem; display: flex; align-items: center; gap: 10px; color: var(--text-light); }
    .contact-info h3 i { color: var(--yellow); }
    .contact-methods { display: flex; flex-wrap: wrap; gap: 1.2rem; }
    .contact-item { display: flex; align-items: center; gap: 1rem; background: var(--bg-elevated); padding: 0.8rem 1.5rem; border-radius: 60px; border: 1px solid var(--border-light); transition: 0.2s; text-decoration: none; color: var(--text-light); font-weight: 500; }
    .contact-item i { font-size: 1.4rem; color: var(--blue); width: 28px; }
    .contact-item:nth-child(2) i { color: #25D366; }
    .contact-item:nth-child(3) i { color: var(--red); }
    .contact-item:hover { border-color: var(--blue); background: #1a2438; transform: translateY(-2px); box-shadow: 0 5px 15px rgba(30, 144, 255, 0.2); }

    /* CHANNEL */
    .channel-link { background: rgba(37, 211, 102, 0.15); border: 1px solid #25D366; border-radius: 50px; padding: 0.7rem 1.2rem; color: #25D366; font-weight: 600; text-decoration: none; display: inline-flex; align-items: center; gap: 8px; transition: 0.2s; }
    .channel-link:hover { background: #25D366; color: #0b0e14; box-shadow: 0 0 20px #25D36680; }
    .channel-link i { font-size: 1.1rem; }
    .small-note { font-size: 0.85rem; color: var(--text-muted); margin-top: 0.5rem; }
    .small-note i { color: var(--yellow); }

    /* FOOTER */
    .footer { text-align: center; padding: 1.8rem 0 0.8rem; border-top: 1px solid var(--border-dark); color: var(--text-muted); font-size: 0.9rem; display: flex; flex-wrap: wrap; justify-content: space-between; align-items: center; gap: 0.8rem; }
    .footer i { color: var(--red); }
    .footer div:last-child i { color: var(--yellow); }

    /* RESPONSIVE */
    @media (max-width: 700px) {
      body { padding: 0.8rem; }
      .header { flex-direction: column; align-items: flex-start; gap: 1rem; padding: 1.2rem; }
      .hero h2 { font-size: 1.6rem; }
      .hero { padding: 1.5rem; }
      .stats { gap: 0.8rem; }
      .stat-item { font-size: 0.85rem; padding: 0.4rem 1rem; }
      .contact-section { flex-direction: column; }
      .contact-methods { flex-direction: column; width: 100%; }
      .contact-item { width: 100%; }
      .footer { flex-direction: column; gap: 0.6rem; }
    }
    @media (max-width: 480px) {
      .pricing-grid { grid-template-columns: 1fr; }
      .card { padding: 1.5rem 1.2rem; }
      .logo h1 { font-size: 1.5rem; }
      .badge-95 { font-size: 0.8rem; padding: 0.3rem 0.8rem; }
    }

    @keyframes glowBlue { 0% { box-shadow: 0 0 5px var(--blue); } 50% { box-shadow: 0 0 20px var(--blue); } 100% { box-shadow: 0 0 5px var(--blue); } }
    .glow-blue { animation: glowBlue 3s infinite; }
    @keyframes pulseRed { 0% { color: var(--red); } 50% { color: var(--red-bright); } 100% { color: var(--red); } }
    .pulse-red { animation: pulseRed 2s infinite; }

    ::-webkit-scrollbar { width: 8px; }
    ::-webkit-scrollbar-track { background: var(--bg-dark); }
    ::-webkit-scrollbar-thumb { background: var(--blue-deep); border-radius: 10px; }
    ::-webkit-scrollbar-thumb:hover { background: var(--red); }
  </style>
</head>
<body>
  <div class="container">
    <!-- HEADER -->
    <header class="header">
      <div class="logo">
        <h1>BRAZ TIPS UG</h1>
        <span>DARKWEB ODDS · 95% ACCURACY</span>
      </div>
      <div class="badge-95">
        <i class="fas fa-shield-hal"></i> 95% ACCURACY GUARANTEED
      </div>
    </header>

    <!-- HERO -->
    <section class="hero">
      <h2><i class="fas fa-bolt"></i> Premium odds · <span class="highlight">Akatafa</span>, <span class="highlight-red">Rollovers</span>, HT/FT</h2>
      <p>Daily 10+ odds, Akatambula weekly 50+, 30+ halftime-fulltime and 2–5 rollovers. Sell odds like the darkweb — ultra‑accurate, fast delivery, max stakes.</p>
      <div class="stats">
        <div class="stat-item"><i class="fas fa-chart-line"></i> 10+ daily odds</div>
        <div class="stat-item"><i class="fas fa-calendar-week"></i> Akatambula 50+</div>
        <div class="stat-item"><i class="fas fa-futbol"></i> HT/FT 30+</div>
        <div class="stat-item"><i class="fas fa-repeat"></i> Rollover 2–5</div>
      </div>
    </section>

    <!-- NEW VISITORS -->
    <section class="hero" style="border:1px dashed #25D366;">
    <h2><i class="fab fa-whatsapp" style="color:#25D366;"></i> New here? Get free tips</h2>
      <p>Join our official WhatsApp channel for <span class="highlight">free odds</span>, daily tips, and updates — no subscription needed.</p>
      <a href="https://whatsapp.com/channel/0029Vb94zrVJZg4ESgk6mx1b" target="_blank" class="channel-link" style="margin-top:1rem;">
        <i class="fab fa-whatsapp"></i> Join Free WhatsApp Channel
      </a>
    </section>

    <!-- AGE & SAFETY -->
    <section class="hero">
      <h2><i class="fas fa-shield-alt"></i> Safe & Responsible Betting</h2>
      <p><span class="highlight-red">Strictly for people above 25 years.</span> Our odds are safe and well-researched.</p>
      <div class="stats" style="margin-top: 1.2rem;">
        <div class="stat-item"><i class="fas fa-user-check"></i> 25+ only</div>
        <div class="stat-item"><i class="fas fa-lock"></i> Safe odds</div>
        <div class="stat-item"><i class="fas fa-coins"></i> Stake smart</div>
      </div>
    </section>

    <!-- STAKING GUIDE -->
    <div class="section-title"><i class="fas fa-money-bill-wave"></i> Recommended staking guide</div>
    <section class="hero" style="margin-bottom: 2.5rem;">
      <p style="font-size:1.05rem; margin-bottom:1rem;"><span class="highlight">Odd 10 and below:</span> stake <span class="highlight-red">UGX 100,000+</span></p>
      <p style="font-size:1.05rem; margin-bottom:1rem;"><span class="highlight">Odds 20 – 50+:</span> stake <span class="highlight-red">UGX 20,000 – 60,000</span></p>
      <p style="font-size:1.05rem; margin-bottom:1rem;"><span class="highlight">Halftime / Fulltime VIP games:</span> double stake <span class="highlight-red">UGX 10,000 on odd 100+</span></p>
      <p style="font-size:1.05rem;"><span class="highlight">Then single them</span> for safer returns.</p>
    </section>

    <!-- PLANS -->
    <div class="section-title"><i class="fas fa-tags"></i> Subscription plans</div>
    <div class="pricing-grid">
      <div class="card">
        <div class="card-icon"><i class="fas fa-sun"></i></div>
        <h3>Daily 10+</h3>
        <div class="odds-badge">ODD 10+ · 2 tickets daily</div>
        <div class="price-tag">UGX 20,000 <small>/ daily</small></div>
        <ul class="features">
          <li><i class="fas fa-check-circle"></i> Monday to Sunday</li>
          <li><i class="fas fa-check-circle"></i> 2 high‑stake tickets</li>
          <li><i class="fas fa-check-circle"></i> 95% accuracy</li>
          <li><i class="fas fa-check-circle"></i> Instant delivery</li>
        </ul>
        <a href="https://wa.me/message/GZGY2MD5UFBPJ1" target="_blank" class="btn"><i class="fas fa-cart-plus"></i> Subscribe daily — UGX 20,000</a>
      </div>

      <div class="card">
        <div class="card-icon"><i class="fas fa-calendar-alt"></i></div>
        <h3>Weekly 10+</h3>
        <div class="odds-badge">ODD 10+ · 7 days</div>
        <div class="price-tag">UGX 100,000 <small>/ week</small></div>
        <ul class="features">
          <li><i class="fas fa-check-circle"></i> Full week coverage</li>
          <li><i class="fas fa-check-circle"></i> High stake tickets</li>
          <li><i class="fas fa-check-circle"></i> 2 tickets daily</li>
          <li><i class="fas fa-check-circle"></i> Priority support</li>
        </ul>
        <a href="https://wa.me/message/GZGY2MD5UFBPJ1" target="_blank" class="btn"><i class="fas fa-cart-plus"></i> Subscribe weekly — UGX 100,000</a>
      </div>

      <div class="card">
        <div class="card-icon"><i class="fas fa-walking"></i></div>
        <h3>Akatambula</h3>
        <div class="odds-badge">WEEKLY ODD 50+</div>
        <div class="price-tag">UGX 15,000 <small>/ week</small></div>
        <ul class="features">
          <li><i class="fas fa-check-circle"></i> Weekly akatambula 50+</li>
          <li><i class="fas fa-check-circle"></i> 1 ticket per week</li>
          <li><i class="fas fa-check-circle"></i> High accuracy</li>
          <li><i class="fas fa-check-circle"></i> Telegram / WhatsApp</li>
        </ul>
        <a href="https://wa.me/message/GZGY2MD5UFBPJ1" target="_blank" class="btn"><i class="fas fa-cart-plus"></i> Get Akatambula — UGX 15,000</a>
      </div>

      <div class="card">
        <div class="card-icon"><i class="fas fa-futbol"></i></div>
        <h3>HT/FT 30+</h3>
        <div class="odds-badge">HALFTIME–FULLTIME · 30+</div>
        <div class="price-tag">UGX 40,000 <small>/ week</small></div>
        <ul class="features">
          <li><i class="fas fa-check-circle"></i> Max 5 tickets</li>
          <li><i class="fas fa-check-circle"></i> Monday to Sunday</li>
          <li><i class="fas fa-check-circle"></i> 30+ odds guarantee</li>
          <li><i class="fas fa-check-circle"></i> Daily HT/FT picks</li>
        </ul>
        <a href="https://wa.me/message/GZGY2MD5UFBPJ1" target="_blank" class="btn"><i class="fas fa-cart-plus"></i> Buy HT/FT plan — UGX 40,000</a>
      </div>

      <div class="card">
        <div class="card-icon"><i class="fas fa-sync-alt"></i></div>
        <h3>Rollover 2–5</h3>
        <div class="odds-badge">3 GAMES DAILY · ODD 2–5</div>
        <div class="price-tag">UGX 10,000 <small>/ daily</small></div>
        <ul class="features">
          <li><i class="fas fa-check-circle"></i> 3 games provided daily</li>
          <li><i class="fas fa-check-circle"></i> Rollover odds 2.0 – 5.0</li>
          <li><i class="fas fa-check-circle"></i> Perfect for bankroll</li>
          <li><i class="fas fa-check-circle"></i> Daily Monday–Sunday</li>
        </ul>
        <a href="https://wa.me/message/GZGY2MD5UFBPJ1" target="_blank" class="btn"><i class="fas fa-sync-alt"></i> Rollover Odd 2–5 — UGX 10,000</a>
      </div>
    </div>

    <!-- SUBSCRIBED USERS -->
    <section class="hero" style="border:1px solid #25D366; box-shadow: 0 0 25px rgba(37,211,102,0.2);">
      <h2><i class="fas fa-check-circle" style="color:#25D366;"></i> Already subscribed?</h2>
      <p>After you finish your subscription with the numbers provided, click below to <span class="highlight">join our WhatsApp channel</span> and follow for more free tips and updates.</p>
      <p class="small-note" style="margin-top:0.8rem;">
        <i class="fas fa-info-circle"></i> Booking codes are sent by admin on WhatsApp after payment. Copy the code exactly as sent — do not edit any selection.
      </p>
      <a href="https://whatsapp.com/channel/0029Vb94zrVJZg4ESgk6mx1b" target="_blank" class="channel-link" style="margin-top:1rem;">
        <i class="fab fa-whatsapp"></i> Join Channel for Free Tips
      </a>
    </section>

    <!-- CONTACT -->
    <div class="section-title" id="contact"><i class="fas fa-address-card"></i> Payment & contact</div>
    <div class="contact-section">
      <div class="contact-info">
        <h3><i class="fas fa-phone-alt"></i> Direct contact</h3>
        <div class="contact-methods">
          <a href="https://wa.me/message/GZGY2MD5UFBPJ1" target="_blank" class="contact-item">
            <i class="fab fa-whatsapp"></i> WhatsApp Admin: Subscribe here
          </a>
          <a href="https://t.me/+16673474078" target="_blank" class="contact-item">
            <i class="fab fa-telegram-plane"></i> Telegram: +1 667 347 4078
          </a>
          <a href="https://whatsapp.com/channel/0029Vb94zrVJZg4ESgk6mx1b" target="_blank" class="contact-item">
            <i class="fab fa-whatsapp"></i> Free odds channel
          </a>
        </div>
        <p class="small-note" style="margin-top:1.2rem;">
          <i class="fas fa-lock"></i> Pay via website or inbox admin. Instant activation.
        </p>
        <p class="small-note">
          <i class="fas fa-exclamation-triangle" style="color:var(--red-bright);"></i>
          Betting is strictly for persons above 25 years. Bet responsibly.
        </p>
      </div>
    </div>
    <!-- FOOTER -->
    <footer class="footer">
      <div><i class="fas fa-shield-alt"></i> 25+ only · Bet responsibly</div>
      <div><i class="fas fa-info-circle"></i> 18+ strictly prohibited · No underage betting</div>
      <div><i class="fas fa-copyright"></i> BRAZ TIPS UG</div>
    </footer>
  </div>
</body>
</html>
