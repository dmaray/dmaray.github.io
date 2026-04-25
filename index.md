layout: default
title: Dylan Ranieri | Data Analytics Professional
<style>
  body { font-family: Georgia, serif; background: #0d1b2a; color: #f4f1eb; margin: 0; }

  .site-header {
    text-align: center;
    padding: 3rem 1.5rem 1.5rem;
    border-bottom: 1px solid rgba(201,168,76,.25);
  }

  .site-header h1 {
    font-size: 2.4rem;
    color: #f4f1eb;
    margin: 0 0 .4rem;
  }

  .site-header p {
    color: #c9a84c;
    font-style: italic;
    font-size: 1.05rem;
    margin: 0;
  }

  /* ── TABS ── */
  .tab-bar {
    display: flex;
    justify-content: center;
    gap: 0;
    border-bottom: 1px solid rgba(201,168,76,.2);
    background: #152336;
    flex-wrap: wrap;
  }

  .tab-btn {
    padding: .85rem 1.6rem;
    background: none;
    border: none;
    border-bottom: 3px solid transparent;
    color: #8a9bb0;
    font-family: Georgia, serif;
    font-size: .9rem;
    cursor: pointer;
    letter-spacing: .05em;
    transition: color .2s, border-color .2s;
  }

  .tab-btn:hover { color: #e0c47a; }

  .tab-btn.active {
    color: #c9a84c;
    border-bottom-color: #c9a84c;
  }

  /* ── PANELS ── */
  .tab-panel { display: none; max-width: 820px; margin: 0 auto; padding: 2.8rem 1.5rem; }
  .tab-panel.active { display: block; }

  .tab-panel h2 {
    font-size: 1.7rem;
    color: #c9a84c;
    border-bottom: 1px solid rgba(201,168,76,.2);
    padding-bottom: .5rem;
    margin-bottom: 1.4rem;
  }

  .tab-panel h3 { font-size: 1.15rem; color: #e0c47a; margin: 1.4rem 0 .4rem; }

  .tab-panel p, .tab-panel li {
    color: #b8c8da;
    font-size: .95rem;
    line-height: 1.8;
  }

  .tab-panel ul { padding-left: 1.3rem; margin: .5rem 0 1rem; }

  /* skill tags */
  .tags { display: flex; flex-wrap: wrap; gap: .45rem; margin-top: .6rem; }
  .tag {
    padding: .2rem .7rem;
    font-size: .75rem;
    background: rgba(201,168,76,.1);
    border: 1px solid rgba(201,168,76,.25);
    border-radius: 2px;
    color: #e0c47a;
    font-family: monospace;
  }

  /* project cards */
  .card {
    background: #152336;
    border: 1px solid rgba(201,168,76,.18);
    border-radius: 4px;
    padding: 1.4rem;
    margin-bottom: 1.2rem;
  }

  .card h3 { margin-top: 0; }

  /* contact links */
  .contact-link {
    display: inline-block;
    margin: .4rem .5rem .4rem 0;
    padding: .55rem 1.3rem;
    border: 1px solid rgba(201,168,76,.35);
    border-radius: 2px;
    color: #c9a84c;
    text-decoration: none;
    font-size: .88rem;
    transition: background .2s;
  }

  .contact-link:hover { background: rgba(201,168,76,.1); }
</style>
<!-- HEADER -->
<div class="site-header">
  <h1>Dylan Ranieri</h1>
  <p>Data Analytics Professional &nbsp;·&nbsp; Long Island, NY</p>
</div>
<!-- TAB BAR -->
<div class="tab-bar">
  <button class="tab-btn active" onclick="showTab('about')">About</button>
  <button class="tab-btn" onclick="showTab('skills')">Skills</button>
  <button class="tab-btn" onclick="showTab('education')">Education</button>

