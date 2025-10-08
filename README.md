<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>iO Beats — Documentation Hub</title>
  <meta name="description" content="IO Beats documentation: whitepapers, transparency packs, governance, and dashboards." />
  <link rel="icon" href="https://raw.githubusercontent.com/iobeatss/iobeats-logo-assets/main/favicon.png" />
  <style>
    :root {
      --bg: #0b0b0f; --card: #111218; --text: #f6f6f7; --muted:#b8bcc7; --accent:#ff7a00; --link:#ffd4ad; --border:#20222b;
      --radius: 16px; --pad: 22px; --max: 980px;
    }
    * { box-sizing: border-box; }
    html, body { height: 100%; }
    body {
      margin: 0; font: 16px/1.6 system-ui, -apple-system, Segoe UI, Roboto, Ubuntu, Cantarell, "Helvetica Neue", Arial, Noto Sans, sans-serif;
      color: var(--text); background: radial-gradient(1000px 600px at 50% -10%, #171824, var(--bg));
    }
    .wrap { max-width: var(--max); margin: 0 auto 64px; padding: 20px; }
    .hero {
      border: 1px solid var(--border); border-radius: var(--radius); overflow: hidden; background: var(--card);
      box-shadow: 0 10px 35px rgba(0,0,0,.35);
    }
    .hero img { width: 100%; display: block; }
    h1 { font-size: 34px; margin: 18px 0 4px; }
    h2 { font-size: 22px; margin: 28px 0 12px; }
    p.lead { color: var(--muted); margin: 0 0 14px; }
    .grid { display: grid; gap: 14px; grid-template-columns: repeat(auto-fit, minmax(260px, 1fr)); }
    .card { background: var(--card); border: 1px solid var(--border); border-radius: var(--radius); padding: var(--pad); }
    .muted { color: var(--muted); }
    a { color: var(--link); text-decoration: none; }
    a:hover { text-decoration: underline; }
    .badge { display: inline-block; padding: 6px 10px; border: 1px solid var(--border); border-radius: 999px; background: #14151c; color: var(--muted); font-size: 12px; }
    .list { margin: 10px 0 0; padding-left: 18px; }
  </style>
</head>
<body>
  <div class="wrap">
    <div class="hero">
      <img src="https://raw.githubusercontent.com/iobeatss/iobeats-logo-assets/main/hero1.gif" alt="IO Beats Banner" />
    </div>

    <h1>iO Beats — Documentation Hub</h1>
    <p class="lead">Own the Music. Earn the Future. Whitepapers, transparency packs, governance docs, and live dashboards.</p>

    <div class="grid" style="margin:22px 0 28px">
      <div class="card">
        <h2>Quick Menu</h2>
        <ul class="list">
          <li><strong>Repos:</strong>
            <a href="https://github.com/iobeatss/IOB-Smart-contract">Smart Contracts</a> ·
            <a href="https://github.com/iobeatss/treasury">Treasury</a> ·
            <a href="https://github.com/iobeatss/iobeats-player">Player</a> ·
            <a href="https://github.com/iobeatss/BeatsApe">BeatsApe</a> ·
            <a href="https://github.com/iobeatss/iobeats-docs">Docs</a> ·
            <a href="https://github.com/iobeatss/iobeats-logo-assets">Logo Assets</a>
          </li>
          <li><strong>Governance:</strong> <a href="https://snapshot.box/#/s:iobdao.eth">Snapshot — iobdao.eth</a></li>
          <li><strong>Dashboards:</strong> <a href="https://dune.com/iobeats_dao">Dune — IO Beats DAO</a></li>
        </ul>
      </div>

      <div class="card">
        <h2>Transparency Packs</h2>
        <div class="muted">Curated, investor-ready PDF bundles with on-chain references.</div>
        <ul class="list">
          <li><strong>Global v1.0:</strong> Overview · Terms · Proofs</li>
          <li><strong>Per-Chain v1.0:</strong> ETH · BNB · Base · Polygon · Arbitrum</li>
          <li class="muted">Update v1.2 planned: NFT Yield · Sablier Vesting · Payroll & Academy</li>
        </ul>
      </div>

      <div class="card">
        <h2>Governance Docs</h2>
        <ul class="list">
          <li>DAO Intro & Rules</li>
          <li>Genesis Proposal #001 — The Birth of IO Beats DAO</li>
          <li>Treasury Transparency v1.0</li>
          <li>Governance Expansion v1.1</li>
        </ul>
      </div>

      <div class="card">
        <h2>Security & License</h2>
        <p class="muted">Report responsibly to <a href="mailto:security@iobeats.com">security@iobeats.com</a>.</p>
        <p><span class="badge">Audit</span> <a href="https://raw.githubusercontent.com/cyberscope-io/audits/main/iob/audit.pdf">Cyberscope</a></p>
        <p><span class="badge">License</span> <a href="https://github.com/iobeatss/IOB-Smart-contract/blob/main/LICENSE">MIT</a></p>
      </div>
    </div>
  </div>
</body>
</html>
