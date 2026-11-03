<html lang="de">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Joshua-Liam Kiesch</title>
  <meta name="description" content="Alle Links von Joshua-Liam Kiesch an einem Ort.">
  <meta name="theme-color" content="#0f1115">
  <style>
    :root {
      --bg: #f3f4f8;
      --text: #16181d;
      --muted: #6b7280;
      --card: #ffffff;
      --border: #e5e7eb;
      --accent: #4f46e5;
      --accent-text: #ffffff;
      --shadow: 0 1px 2px rgba(16, 24, 40, .06), 0 4px 14px rgba(16, 24, 40, .06);
    }
    @media (prefers-color-scheme: dark) {
      :root {
        --bg: #0f1115;
        --text: #f3f4f6;
        --muted: #9ca3af;
        --card: #1a1d24;
        --border: #2a2e37;
        --accent: #6366f1;
        --shadow: 0 1px 2px rgba(0, 0, 0, .4), 0 4px 14px rgba(0, 0, 0, .3);
      }
    }

    * { box-sizing: border-box; margin: 0; padding: 0; }

    body {
      min-height: 100vh;
      background: var(--bg);
      color: var(--text);
      font-family: system-ui, -apple-system, "Segoe UI", Roboto, sans-serif;
      -webkit-font-smoothing: antialiased;
      display: flex;
      justify-content: center;
      padding: 48px 16px;
    }

    main { width: 100%; max-width: 420px; text-align: center; }

    .avatar {
      width: 132px;
      height: 132px;
      margin: 0 auto 20px;
      border-radius: 50%;
      background: linear-gradient(135deg, #6366f1, #ec4899);
      display: grid;
      place-items: center;
      color: #fff;
      font-size: 2.4rem;
      font-weight: 700;
      letter-spacing: .02em;
      overflow: hidden;
      border: 4px solid var(--card);
      box-shadow: var(--shadow);
    }
    .avatar > * { grid-area: 1 / 1; }
    .avatar img { width: 100%; height: 100%; object-fit: cover; object-position: center 25%; display: block; transform: scale(1.2) translateY(-10px); }

    h1 { font-size: 1.6rem; font-weight: 700; letter-spacing: -.01em; }
    .tagline { margin-top: 6px; color: var(--muted); font-size: 1rem; }

    .links { margin-top: 32px; display: flex; flex-direction: column; gap: 12px; }

    .link {
      display: flex;
      align-items: center;
      gap: 14px;
      padding: 16px 18px;
      border-radius: 14px;
      background: var(--card);
      border: 1px solid var(--border);
      box-shadow: var(--shadow);
      color: var(--text);
      text-decoration: none;
      font-size: 1rem;
      font-weight: 600;
      text-align: left;
      transition: transform .15s ease, border-color .15s ease;
    }
    .link:hover, .link:focus-visible { transform: translateY(-2px); border-color: var(--accent); outline: none; }
    .link:active { transform: translateY(0); }

    .link svg { width: 24px; height: 24px; flex: none; }
    .link span { flex: 1; }
    .link .chevron { width: 18px; height: 18px; opacity: .4; }

    .link.primary {
      background: var(--accent);
      border-color: var(--accent);
      color: var(--accent-text);
      margin-top: 8px;
    }
    .link.primary .chevron { opacity: .7; }

    footer { margin-top: 36px; color: var(--muted); font-size: .8rem; }
  </style>
</head>
<body>
  <main>
    <!-- Profilbild: Datei "foto.jpg" in denselben Ordner legen.
         Ohne Bild werden die Initialen angezeigt. -->
    <div class="avatar">
      <span>JK</span>
      <img src="test3.jpg" alt="Joshua-Liam Kiesch" onerror="this.remove()">
    </div>

    <h1>Joshua-Liam Kiesch</h1>
    <p class="tagline">Meine Links an einem Ort</p>

    <nav class="links">
      <a class="link" href="https://www.instagram.com/joshslebenmitsma/" target="_blank" rel="noopener">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="3" width="18" height="18" rx="5"/><circle cx="12" cy="12" r="4"/><circle cx="17.5" cy="6.5" r="1" fill="currentColor" stroke="none"/></svg>
        <span>Instagram</span>
        <svg class="chevron" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><path d="M9 6l6 6-6 6"/></svg>
      </a>

      <a class="link" href="https://www.tiktok.com/@joshua_kiesch" target="_blank" rel="noopener">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M14 3v11.5a3.5 3.5 0 1 1-3.5-3.5"/><path d="M14 3c.4 2.6 2.1 4.3 5 4.5"/></svg>
        <span>TikTok</span>
        <svg class="chevron" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><path d="M9 6l6 6-6 6"/></svg>
      </a>

      <a class="link" href="https://www.facebook.com/joshualiam.kiesch" target="_blank" rel="noopener">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="9"/><path d="M13.5 21v-7.5h2.5l.5-3h-3V9c0-.9.4-1.5 1.600-1.500H16.500V4.900C16 4.800 15.300 4.700 14.600 4.700c-2.200 0-3.600 1.300-3.600 3.700v2.100H8.500v3H11V21"/></svg>
        <span>Facebook</span>
        <svg class="chevron" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><path d="M9 6l6 6-6 6"/></svg>
      </a>

      <a class="link" href="https://www.linkedin.com/in/joshua-liam-kiesch-833611426" target="_blank" rel="noopener">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="3" width="18" height="18" rx="3"/><path d="M8 10.500V16M8 7.500v.01M12 16v-5.500M12 13c0-1.700 1-2.500 2.300-2.500S16.500 11.300 16.500 13v3"/></svg>
        <span>LinkedIn</span>
        <svg class="chevron" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><path d="M9 6l6 6-6 6"/></svg>
      </a>

      <a class="link" href="https://joshs-leben.de" target="_blank" rel="noopener">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="9"/><path d="M3 12h18M12 3c2.5 2.7 3.8 5.7 3.8 9s-1.3 6.3-3.8 9c-2.5-2.7-3.8-5.7-3.8-9S9.5 5.7 12 3z"/></svg>
        <span>Webseite</span>
        <svg class="chevron" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><path d="M9 6l6 6-6 6"/></svg>
      </a>
    </nav>

    <footer>&copy; Joshua-Liam Kiesch</footer>
  </main>
</body>
</html>
