<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Manish Verma — Senior Product Manager (R&D) · AI Platforms & LLM Orchestration</title>
<meta name="description" content="Manish Verma — AI-focused Senior Product Manager taking LLM-powered products from experimentation to production. Inventor on two filed patents, author of two arXiv pre-prints." />
<meta name="author" content="Manish Verma" />
<meta property="og:title" content="Manish Verma — Senior Product Manager (R&D), AI Platforms" />
<meta property="og:description" content="LLM orchestration, agentic workflows & RAG. Inventor on two filed patents, author of two arXiv pre-prints." />
<meta property="og:type" content="profile" />
<link rel="preconnect" href="https://fonts.googleapis.com" />
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=Fraunces:opsz,wght@9..144,500;9..144,600&display=swap" rel="stylesheet" />
<style>
  :root{
    /* warm neutral palette tuned to the portrait: off-white, grey, soft black */
    --ink:#232220;          /* soft/light black text */
    --charcoal:#2b2a27;     /* headings, dark surfaces */
    --charcoal-2:#413f3b;   /* secondary dark */
    --accent:#57534d;       /* warm graphite accent */
    --accent-soft:#ecebe6;  /* soft grey fill */
    --muted:#6f6b64;        /* muted grey text */
    --line:#e3e0d9;         /* hairlines */
    --bg:#faf9f6;           /* off-white page */
    --bg-alt:#f2f0ea;       /* light grey band */
    --shadow:0 10px 30px rgba(35,34,32,.10);
    --shadow-sm:0 4px 14px rgba(35,34,32,.06);
    --radius:16px;
  }
  *{box-sizing:border-box;margin:0;padding:0}
  html{scroll-behavior:smooth}
  body{
    font-family:'Inter',system-ui,-apple-system,Segoe UI,Roboto,sans-serif;
    color:var(--ink);background:var(--bg);line-height:1.6;
    -webkit-font-smoothing:antialiased;
  }
  a{color:var(--accent);text-decoration:none}
  a:hover{text-decoration:underline}
  .wrap{max-width:1080px;margin:0 auto;padding:0 24px}
  h1,h2,h3{line-height:1.2;color:var(--charcoal)}
  .serif{font-family:'Fraunces',Georgia,serif}
  section{padding:76px 0;border-bottom:1px solid var(--line)}
  .eyebrow{
    text-transform:uppercase;letter-spacing:.14em;font-size:.78rem;
    font-weight:700;color:var(--accent);margin-bottom:12px;
  }
  h2.section-title{font-size:2rem;margin-bottom:8px}
  .section-sub{color:var(--muted);max-width:640px;margin-bottom:36px}

  /* NAV */
  header.nav{
    position:sticky;top:0;z-index:50;background:rgba(250,249,246,.86);
    backdrop-filter:saturate(180%) blur(12px);border-bottom:1px solid var(--line);
  }
  .nav-in{display:flex;align-items:center;justify-content:space-between;height:64px}
  .brand{font-weight:800;color:var(--charcoal);letter-spacing:-.01em;font-size:1.05rem}
  .brand span{color:var(--accent)}
  .nav-links{display:flex;gap:26px}
  .nav-links a{color:var(--muted);font-weight:500;font-size:.93rem}
  .nav-links a:hover{color:var(--charcoal);text-decoration:none}
  .nav-cta{background:var(--charcoal);color:#fff!important;padding:9px 18px;border-radius:999px;font-weight:600;font-size:.9rem}
  .nav-cta:hover{background:var(--charcoal-2);text-decoration:none}
  @media(max-width:860px){ .nav-links{display:none} }

  /* HERO */
  .hero{
    background:
      radial-gradient(1100px 500px at 80% -10%,var(--accent-soft),transparent 60%),
      linear-gradient(180deg,#fbfaf7,#faf9f6);
    border-bottom:1px solid var(--line);
  }
  .hero-grid{display:grid;grid-template-columns:1.4fr .9fr;gap:48px;align-items:center;padding:70px 0 78px}
  .hero .avail{
    display:inline-flex;align-items:center;gap:8px;background:var(--accent-soft);color:var(--charcoal-2);
    font-weight:600;font-size:.82rem;padding:6px 14px;border-radius:999px;margin-bottom:22px;
  }
  .hero .avail .dot{width:8px;height:8px;border-radius:50%;background:var(--accent);box-shadow:0 0 0 4px rgba(87,83,77,.16)}
  .hero h1{font-size:3rem;letter-spacing:-.02em;margin-bottom:10px}
  .hero .role{font-size:1.28rem;color:var(--charcoal-2);font-weight:600;margin-bottom:18px}
  .hero p.lead{color:var(--muted);font-size:1.06rem;max-width:560px;margin-bottom:28px}
  .hero-cta{display:flex;flex-wrap:wrap;gap:12px}
  .btn{display:inline-flex;align-items:center;gap:9px;padding:12px 22px;border-radius:999px;font-weight:600;font-size:.95rem;transition:.18s}
  .btn-primary{background:var(--charcoal);color:#fff}
  .btn-primary:hover{background:var(--charcoal-2);text-decoration:none;transform:translateY(-1px)}
  .btn-ghost{background:#fff;color:var(--charcoal);border:1px solid var(--line);box-shadow:var(--shadow-sm)}
  .btn-ghost:hover{border-color:var(--accent);color:var(--accent);text-decoration:none}
  .photo-wrap{justify-self:center;position:relative}
  .photo{
    width:290px;height:290px;border-radius:24px;object-fit:cover;object-position:center top;
    box-shadow:var(--shadow);border:6px solid #fff;background:var(--accent-soft);
  }
  .photo-fallback{
    width:290px;height:290px;border-radius:24px;display:flex;align-items:center;justify-content:center;
    font-family:'Fraunces',serif;font-size:5rem;font-weight:600;color:#fff;
    background:linear-gradient(135deg,var(--charcoal),var(--accent));box-shadow:var(--shadow);border:6px solid #fff;
  }
  .badge-float{
    position:absolute;bottom:-16px;left:-16px;background:#fff;border-radius:14px;padding:12px 16px;
    box-shadow:var(--shadow);border:1px solid var(--line);font-size:.82rem;font-weight:600;color:var(--charcoal);
  }
  .badge-float b{color:var(--accent)}

  /* METRIC STRIP */
  .metrics{display:grid;grid-template-columns:repeat(4,1fr);gap:20px;padding:0}
  .metric{background:var(--bg-alt);border:1px solid var(--line);border-radius:var(--radius);padding:22px}
  .metric .n{font-family:'Fraunces',serif;font-size:2rem;color:var(--charcoal);font-weight:600}
  .metric .l{color:var(--muted);font-size:.9rem;margin-top:2px}

  /* ABOUT */
  .about-grid{display:grid;grid-template-columns:1.5fr 1fr;gap:40px}
  .about p{color:var(--muted);margin-bottom:16px;font-size:1.03rem}
  .about p strong{color:var(--ink)}
  .quick-card{background:var(--bg-alt);border:1px solid var(--line);border-radius:var(--radius);padding:24px;height:fit-content}
  .quick-card h3{font-size:1rem;margin-bottom:14px}
  .quick-row{display:flex;justify-content:space-between;gap:12px;padding:9px 0;border-bottom:1px dashed var(--line);font-size:.92rem}
  .quick-row:last-child{border-bottom:0}
  .quick-row span:first-child{color:var(--muted)}
  .quick-row span:last-child{color:var(--charcoal);font-weight:600;text-align:right}

  /* EXPERIENCE TIMELINE */
  .timeline{position:relative;margin-left:6px}
  .timeline::before{content:"";position:absolute;left:9px;top:6px;bottom:6px;width:2px;background:var(--line)}
  .job{position:relative;padding:0 0 34px 40px}
  .job:last-child{padding-bottom:0}
  .job .dot{position:absolute;left:2px;top:4px;width:16px;height:16px;border-radius:50%;background:#fff;border:3px solid var(--accent)}
  .job.cur .dot{background:var(--accent)}
  .job .when{font-size:.82rem;font-weight:600;color:var(--accent);text-transform:uppercase;letter-spacing:.05em}
  .job h3{font-size:1.15rem;margin:3px 0 2px}
  .job .co{color:var(--charcoal-2);font-weight:600;font-size:.96rem;margin-bottom:10px}
  .job ul{list-style:none;display:flex;flex-direction:column;gap:7px}
  .job ul li{position:relative;padding-left:20px;color:var(--muted);font-size:.96rem}
  .job ul li::before{content:"";position:absolute;left:2px;top:10px;width:6px;height:6px;border-radius:50%;background:var(--accent)}

  /* EXPERTISE CHIPS */
  .chips{display:flex;flex-wrap:wrap;gap:10px}
  .chip{background:var(--accent-soft);color:var(--charcoal-2);font-weight:600;font-size:.9rem;padding:9px 16px;border-radius:999px;border:1px solid var(--line)}

  /* CARD GRIDS */
  .grid-2{display:grid;grid-template-columns:1fr 1fr;gap:22px}
  .grid-3{display:grid;grid-template-columns:repeat(3,1fr);gap:22px}
  .card{background:#fff;border:1px solid var(--line);border-radius:var(--radius);padding:26px;box-shadow:var(--shadow-sm);transition:.18s;display:flex;flex-direction:column}
  .card:hover{transform:translateY(-3px);box-shadow:var(--shadow);border-color:#d8d4cc}
  .card .tag{display:inline-flex;align-items:center;gap:6px;align-self:flex-start;background:var(--accent-soft);color:var(--accent);font-weight:700;font-size:.72rem;text-transform:uppercase;letter-spacing:.08em;padding:5px 11px;border-radius:999px;margin-bottom:14px}
  .card h3{font-size:1.12rem;margin-bottom:8px}
  .card p{color:var(--muted);font-size:.95rem;margin-bottom:16px;flex-grow:1}
  .card .meta{font-size:.85rem;color:var(--muted);margin-bottom:14px}
  .card .link{font-weight:600;font-size:.92rem;display:inline-flex;align-items:center;gap:6px}
  .patent-id{font-family:'Fraunces',serif;font-size:.9rem;color:var(--charcoal);background:var(--bg-alt);border:1px solid var(--line);border-radius:8px;padding:4px 10px;display:inline-block;margin-bottom:12px}

  /* SAMPLES */
  .samples{display:grid;grid-template-columns:repeat(3,1fr);gap:18px}
  .sample{display:flex;gap:14px;align-items:flex-start;background:#fff;border:1px solid var(--line);border-radius:14px;padding:18px;box-shadow:var(--shadow-sm);transition:.18s}
  .sample:hover{border-color:#d8d4cc;transform:translateY(-2px);box-shadow:var(--shadow);text-decoration:none}
  .sample .ico{flex-shrink:0;width:42px;height:42px;border-radius:10px;background:var(--accent-soft);display:flex;align-items:center;justify-content:center;font-size:.7rem;font-weight:800;color:var(--accent);letter-spacing:.02em}
  .sample h4{font-size:.98rem;color:var(--charcoal);margin-bottom:3px}
  .sample p{font-size:.84rem;color:var(--muted)}

  /* AWARDS */
  .awards{display:flex;flex-wrap:wrap;gap:12px}
  .award{background:var(--bg-alt);border:1px solid var(--line);border-radius:12px;padding:14px 18px;font-size:.92rem;color:var(--charcoal);font-weight:600;display:flex;align-items:center;gap:10px}
  .award .star{color:var(--accent)}

  /* CONTACT */
  .contact{background:linear-gradient(135deg,var(--charcoal),#1f1e1b);color:#fff;border-bottom:0}
  .contact h2{color:#fff}
  .contact .section-sub{color:#cfccc5}
  .contact-cta{display:flex;flex-wrap:wrap;gap:14px;margin-top:8px}
  .contact .btn-primary{background:#fff;color:var(--charcoal)}
  .contact .btn-primary:hover{background:var(--accent-soft)}
  .contact .btn-ghost{background:transparent;color:#fff;border-color:rgba(255,255,255,.35);box-shadow:none}
  .contact .btn-ghost:hover{border-color:#fff;color:#fff}

  footer{background:var(--charcoal);color:#b7b3aa;text-align:center;padding:26px 0;font-size:.86rem}
  footer a{color:#e3e0d9}

  @media(max-width:860px){
    .hero-grid,.about-grid{grid-template-columns:1fr}
    .hero .photo-wrap{grid-row:1;justify-self:start}
    .metrics{grid-template-columns:1fr 1fr}
    .grid-2,.grid-3,.samples{grid-template-columns:1fr}
    .hero h1{font-size:2.3rem}
    section{padding:56px 0}
  }
</style>
</head>
<body>

<!-- NAV -->
<header class="nav">
  <div class="wrap nav-in">
    <div class="brand">Manish<span>Verma</span></div>
    <nav class="nav-links">
      <a href="#about">About</a>
      <a href="#experience">Experience</a>
      <a href="#patents">Patents</a>
      <a href="#research">Research</a>
      <a href="#work">Work</a>
      <a href="#contact">Contact</a>
    </nav>
    <a class="nav-cta" href="#contact">Get in touch</a>
  </div>
</header>

<!-- HERO -->
<div class="hero">
  <div class="wrap hero-grid">
    <div>
      <span class="avail"><span class="dot"></span>Senior Product Manager (R&D) · AI Platforms</span>
      <h1 class="serif">Manish Verma</h1>
      <div class="role">Generative AI Product Leader — LLM Orchestration, Agentic Workflows &amp; RAG</div>
      <p class="lead">I take LLM-powered products from experimentation to production at scale — owning the end-to-end lifecycle of Generative AI tools built on complex backend and data services. Inventor on two filed patents and author of two arXiv pre-prints on applied AI for technology and market intelligence.</p>
      <div class="hero-cta">
        <a class="btn btn-primary" href="#contact">Contact me →</a>
        <a class="btn btn-ghost" href="assets/Manish_Verma_Resume.pdf" target="_blank" rel="noopener">Download résumé</a>
        <a class="btn btn-ghost" href="https://www.linkedin.com/in/manish-verma-13346811a/" target="_blank" rel="noopener">LinkedIn</a>
      </div>
    </div>
    <div class="photo-wrap">
      <img class="photo" src="assets/profile.jpg" alt="Manish Verma"
           onerror="this.outerHTML='&lt;div class=&quot;photo-fallback&quot;&gt;MV&lt;/div&gt;'" />
      <div class="badge-float">6+ yrs · <b>AI &amp; IP R&amp;D</b></div>
    </div>
  </div>
</div>

<!-- METRICS -->
<section style="padding:44px 0">
  <div class="wrap metrics">
    <div class="metric"><div class="n">$1.3M → $2.6M</div><div class="l">Portfolio ARR growth (~2×)</div></div>
    <div class="metric"><div class="n">2</div><div class="l">Filed patent applications</div></div>
    <div class="metric"><div class="n">2</div><div class="l">arXiv pre-prints</div></div>
    <div class="metric"><div class="n">6+ yrs</div><div class="l">IP R&amp;D &amp; GenAI PM</div></div>
  </div>
</section>

<!-- ABOUT -->
<section id="about">
  <div class="wrap">
    <div class="eyebrow">About</div>
    <h2 class="section-title serif">Building AI products that reach production</h2>
    <div class="about-grid">
      <div class="about">
        <p>I'm an AI-focused product manager who owns the full lifecycle of Generative AI tools — <strong>LLM orchestration, agentic workflows, RAG-based retrieval, and embedding-model strategy</strong> — built on top of complex backend and data services.</p>
        <p>I work backwards from customer value, lead cross-functional teams across backend, frontend, and research, and translate technical trade-offs into business narratives for leadership. My portfolio spans IP analytics products where I've moved tools from AI experimentation to production-grade automation.</p>
        <p>I bring deep AI-product craft and am actively growing into broader platform and ecosystem scope — designing reusable AI infrastructure that other product teams build on.</p>
      </div>
      <div class="quick-card">
        <h3>At a glance</h3>
        <div class="quick-row"><span>Current role</span><span>Sr. PM, R&amp;D — Xlscout.ai</span></div>
        <div class="quick-row"><span>Focus</span><span>GenAI · LLM · Agentic</span></div>
        <div class="quick-row"><span>Location</span><span>Ontario, Canada</span></div>
        <div class="quick-row"><span>Education</span><span>B.Tech, LPU (2019)</span></div>
        <div class="quick-row"><span>Email</span><span><a href="mailto:mkmanishkumar39@gmail.com">Email me</a></span></div>
      </div>
    </div>
  </div>
</section>

<!-- EXPERIENCE -->
<section id="experience">
  <div class="wrap">
    <div class="eyebrow">Experience</div>
    <h2 class="section-title serif">6+ years across GenAI product &amp; IP R&amp;D</h2>
    <p class="section-sub">From patent research analyst to senior product manager owning an LLM-powered product portfolio.</p>
    <div class="timeline">
      <div class="job cur">
        <div class="dot"></div>
        <div class="when">Jun 2025 — Present</div>
        <h3>Senior Product Manager, R&amp;D</h3>
        <div class="co">Xlscout.ai · Ontario, Canada</div>
        <ul>
          <li>Own the strategy and delivery of a portfolio of LLM-powered IP analytics products built on shared AI infrastructure.</li>
          <li>Drove portfolio ARR from $1.32M to $2.61M (~2×) over two years by leading the production rollout of a GenAI suite — ClaimChart LLM, Standigger LLM, Invalidator LLM, Patdigger, and Product-to-Patent.</li>
          <li>Drive the design of reusable AI infrastructure: multi-model LLM orchestration, agentic/RAG retrieval patterns, and open-source embedding-model training strategy.</li>
          <li>Bridge research, engineering, and leadership — translating technical trade-offs into commercial narratives that shape product strategy.</li>
        </ul>
      </div>
      <div class="job">
        <div class="dot"></div>
        <div class="when">Aug 2023 — May 2025</div>
        <h3>Product Manager, R&amp;D</h3>
        <div class="co">Xlscout.ai · Ontario, Canada</div>
        <ul>
          <li>Shipped customized automation for patent categorization and portfolio ranking, turning manual, expert-heavy workflows into scalable AI-driven processes.</li>
          <li>Championed "B2B as intuitive as B2C" — consistent, user-centric experiences across enterprise tools as a differentiator.</li>
          <li>Delivered technology &amp; competitive benchmark reports, applying GenAI to extract and structure market data.</li>
          <li>Established validation practices for AI tools and managed enterprise client engagements.</li>
        </ul>
      </div>
      <div class="job">
        <div class="dot"></div>
        <div class="when">May 2022 — Jul 2023</div>
        <h3>Senior Patent Research Analyst</h3>
        <div class="co">TT Consultants Pvt. Ltd. · Punjab, India</div>
        <ul>
          <li>Business development support under the AVP Operations — bridging research depth and commercial strategy.</li>
          <li>Prepared approach papers and proposals for pilot studies and client engagements.</li>
          <li>Monitored IP search tools and competitive intelligence, guiding multidisciplinary technology-scouting initiatives.</li>
        </ul>
      </div>
      <div class="job">
        <div class="dot"></div>
        <div class="when">Oct 2020 — Apr 2022</div>
        <h3>Patent Research Analyst</h3>
        <div class="co">TT Consultants Pvt. Ltd. · Punjab, India</div>
        <ul>
          <li>Patent analyst across life-science domains — biomedical engineering, industrial biotechnology, bio-process engineering, and bioinformatics.</li>
          <li>Conducted Patentability, Invalidation, FTO, Landscape, and Infringement analyses supporting clients' strategic IP decisions.</li>
        </ul>
      </div>
      <div class="job">
        <div class="dot"></div>
        <div class="when">Aug 2019 — Sep 2020</div>
        <h3>Junior Patent Research Analyst</h3>
        <div class="co">TT Consultants Pvt. Ltd. · Punjab, India</div>
        <ul>
          <li>Executed Invalidity, FTO, Novelty, and Infringement projects across domain and cross-domain studies.</li>
          <li>Curated technical insights and enhanced workflow models for searches, techniques, and reports.</li>
        </ul>
      </div>
    </div>
  </div>
</section>

<!-- EXPERTISE -->
<section id="expertise" style="background:var(--bg-alt)">
  <div class="wrap">
    <div class="eyebrow">Core expertise</div>
    <h2 class="section-title serif">What I work with</h2>
    <p class="section-sub">The product, AI, and leadership toolkit I bring to the table.</p>
    <div class="chips">
      <span class="chip">Generative AI Product Management</span>
      <span class="chip">LLM Orchestration</span>
      <span class="chip">Agentic Workflows &amp; RAG</span>
      <span class="chip">Embedding-Model Strategy</span>
      <span class="chip">Prompt Engineering</span>
      <span class="chip">MCP</span>
      <span class="chip">LangChain</span>
      <span class="chip">Plugins &amp; Connectors</span>
      <span class="chip">AI Experimentation → Production</span>
      <span class="chip">Cross-Functional Leadership</span>
      <span class="chip">Executive Communication</span>
      <span class="chip">Customer-Backwards Discovery</span>
      <span class="chip">Technology &amp; Competitive Intelligence</span>
      <span class="chip">Patent Portfolio Ranking</span>
      <span class="chip">FTO / Invalidation / Landscape</span>
    </div>
  </div>
</section>

<!-- PATENTS -->
<section id="patents">
  <div class="wrap">
    <div class="eyebrow">Patent applications</div>
    <h2 class="section-title serif">Inventor on two filed patents</h2>
    <p class="section-sub">Filed applications covering LLM-driven methods for entity/product relevance and sustainable-technology solution generation.</p>
    <div class="grid-2">
      <div class="card">
        <span class="tag">◆ Patent · Filed Jul 2024</span>
        <span class="patent-id">US-2026/0030308-A1</span>
        <h3>Determining relevant entities and products using an LLM model</h3>
        <p>System and method that leverages a large language model to identify the entities and products most relevant to a given query or technology context.</p>
        <a class="link" href="https://patents.google.com/patent/US20260030308A1" target="_blank" rel="noopener">View on Google Patents →</a>
      </div>
      <div class="card">
        <span class="tag">◆ Patent · Filed Apr 2024</span>
        <span class="patent-id">US Appl. 18/625,229</span>
        <h3>Generating suggestions to enhance solutions for a seed problem using LLMs</h3>
        <p>Systems and methods that use LLMs together with sustainable technologies to generate enhanced solution suggestions for a given seed problem.</p>
        <a class="link" href="https://patents.google.com/?inventor=Manish+Verma" target="_blank" rel="noopener">Search Google Patents →</a>
      </div>
    </div>
  </div>
</section>

<!-- RESEARCH -->
<section id="research" style="background:var(--bg-alt)">
  <div class="wrap">
    <div class="eyebrow">Research · arXiv</div>
    <h2 class="section-title serif">Pre-prints &amp; publications</h2>
    <p class="section-sub">Peer-shared research on applied AI for patent and market intelligence.</p>
    <div class="grid-2">
      <div class="card">
        <span class="tag">arXiv:2507.20322 · Jul 2025</span>
        <h3>AI in Patent and Market Intelligence: A New Paradigm for Technology Scouting</h3>
        <p>Explores how artificial intelligence reshapes technology scouting across patent and market intelligence workflows.</p>
        <a class="link" href="https://arxiv.org/abs/2507.20322" target="_blank" rel="noopener">Read on arXiv →</a>
      </div>
      <div class="card">
        <span class="tag">arXiv:2509.00958 · Sep 2025</span>
        <h3>A Hybrid AI Framework for Strategic Patent Portfolio Pruning</h3>
        <p>Learning-to-Rank and market-need analysis for technology-transfer optimization — a hybrid framework for strategic portfolio pruning.</p>
        <a class="link" href="https://arxiv.org/abs/2509.00958" target="_blank" rel="noopener">Read on arXiv →</a>
      </div>
    </div>
  </div>
</section>

<!-- WORK: PROJECT + SAMPLES -->
<section id="work">
  <div class="wrap">
    <div class="eyebrow">Selected work</div>
    <h2 class="section-title serif">Projects &amp; work samples</h2>
    <p class="section-sub">A featured build plus downloadable examples of my analysis and product output.</p>

    <div class="grid-3" style="margin-bottom:34px">
      <div class="card">
        <span class="tag">⚙ Open source</span>
        <h3>IP Contact Finder</h3>
        <p>An email / IP-contact extractor tool — automates finding relevant contact details from IP and web sources.</p>
        <div class="meta">Python · Automation · Data extraction</div>
        <a class="link" href="https://github.com/Manish-Verma-sys/ip-contact-finder" target="_blank" rel="noopener">View on GitHub →</a>
      </div>
      <div class="card">
        <span class="tag">◆ Recognition</span>
        <h3>Strategic AI Consultant (2025)</h3>
        <p>Recognized for driving AI product strategy — alongside multiple Employee of the Year awards.</p>
        <div class="meta">Awards &amp; honors</div>
        <a class="link" href="#awards">See all recognition →</a>
      </div>
      <div class="card">
        <span class="tag">🎓 Certification</span>
        <h3>Harvard Medical School — HMX</h3>
        <p>HMX Fundamentals (Genetics), plus certifications from University of Michigan, IBM, ISRO &amp; more.</p>
        <div class="meta">Continuing education</div>
        <a class="link" href="assets/Harvard_Certificate.pdf" target="_blank" rel="noopener">View certificate →</a>
      </div>
    </div>

    <h3 style="font-size:1.15rem;margin-bottom:16px">Downloadable samples</h3>
    <div class="samples">
      <a class="sample" href="assets/Large_Language_Models_Rewriting_Pharma_s_Playbook.pdf" target="_blank" rel="noopener">
        <div class="ico">PDF</div>
        <div><h4>LLMs Are Rewriting Pharma's Playbook</h4><p>A deep report on how LLMs became strategic infrastructure across pharma — market size, key players &amp; workflow-stage impact.</p></div>
      </a>
      <a class="sample" href="assets/Is_Drug_Discovery_Undergoing_a_Revolution_with_Large_Language_Model.pdf" target="_blank" rel="noopener">
        <div class="ico">PDF</div>
        <div><h4>Drug Discovery &amp; LLMs</h4><p>An analysis of how large language models are reshaping the drug-discovery pipeline, from target ID to clinical trials.</p></div>
      </a>
      <a class="sample" href="assets/Injector.pdf" target="_blank" rel="noopener">
        <div class="ico">PDF</div>
        <div><h4>Needle-Free Injector — Landscape Report</h4><p>A technology &amp; competitor landscape report — taxonomy, IP intelligence and whitespace analysis (sample).</p></div>
      </a>
      <a class="sample" href="assets/Tech_Forecast.pdf" target="_blank" rel="noopener">
        <div class="ico">PDF</div>
        <div><h4>Technology Forecast — Hypothesis</h4><p>A pilot-study method for spotting nascent tech by combining IP landscapes, whitespace &amp; LLM idea generation.</p></div>
      </a>
      <a class="sample" href="assets/Slime_Mold.pdf" target="_blank" rel="noopener">
        <div class="ico">PDF</div>
        <div><h4>From Slime Mold to Tech Insights</h4><p>A biomimetic hypothesis — modelling patent + market data on <em>Physarum polycephalum</em> network behaviour.</p></div>
      </a>
      <a class="sample" href="assets/Tech_Insights.pdf" target="_blank" rel="noopener">
        <div class="ico">PDF</div>
        <div><h4>Illustrative Infographics</h4><p>Technical topics — bio-based polymers, sustainable cooling, neurostimulation — turned into visual one-pagers.</p></div>
      </a>
      <a class="sample" href="assets/Manish_Verma_Resume.pdf" target="_blank" rel="noopener">
        <div class="ico">PDF</div>
        <div><h4>Résumé</h4><p>Full professional résumé (PDF).</p></div>
      </a>
      <a class="sample" href="https://www.linkedin.com/in/manish-verma-13346811a/details/certifications/" target="_blank" rel="noopener">
        <div class="ico">↗</div>
        <div><h4>All certifications</h4><p>9+ licenses &amp; certifications on LinkedIn.</p></div>
      </a>
    </div>
  </div>
</section>

<!-- AWARDS + EDUCATION -->
<section id="awards" style="background:var(--bg-alt)">
  <div class="wrap">
    <div class="eyebrow">Recognition &amp; education</div>
    <h2 class="section-title serif">Awards &amp; academics</h2>
    <div class="about-grid">
      <div>
        <div class="awards" style="margin-bottom:26px">
          <div class="award"><span class="star">★</span> Strategic AI Consultant · 2025</div>
          <div class="award"><span class="star">★</span> Employee of the Year · 2020, 2021, 2022, 2024</div>
          <div class="award"><span class="star">★</span> MVP</div>
          <div class="award"><span class="star">★</span> Employee of the Quarter</div>
          <div class="award"><span class="star">★</span> Best Newcomer</div>
        </div>
      </div>
      <div class="quick-card">
        <h3>Education &amp; certifications</h3>
        <div class="quick-row"><span>Degree</span><span><a href="assets/LPU_Degree_B_Tech_Biotechnology.jpg" target="_blank" rel="noopener">B.Tech, Biotechnology ↗</a></span></div>
        <div class="quick-row"><span>University</span><span>Lovely Professional Univ.</span></div>
        <div class="quick-row"><span>Year / CGPA</span><span>2019 · 8.03/10</span></div>
        <div class="quick-row"><span>Certifications</span><span>Harvard HMX · Michigan · IBM · ISRO</span></div>
      </div>
    </div>
  </div>
</section>

<!-- CONTACT -->
<section id="contact" class="contact">
  <div class="wrap">
    <div class="eyebrow" style="color:#cfccc5">Contact</div>
    <h2 class="section-title serif">Let's build something</h2>
    <p class="section-sub">Open to conversations about AI product leadership, LLM platforms, and IP intelligence.</p>
    <div class="contact-cta">
      <a class="btn btn-primary" href="mailto:mkmanishkumar39@gmail.com">Email me →</a>
      <a class="btn btn-ghost" href="https://www.linkedin.com/in/manish-verma-13346811a/" target="_blank" rel="noopener">LinkedIn</a>
      <a class="btn btn-ghost" href="https://github.com/Manish-Verma-sys" target="_blank" rel="noopener">GitHub</a>
      <a class="btn btn-ghost" href="tel:+918847526980">+91 88475 26980</a>
    </div>
  </div>
</section>

<footer>
  <div class="wrap">
    © <span id="yr"></span> Manish Verma · Senior Product Manager (R&amp;D) — AI Platforms ·
    <a href="mailto:mkmanishkumar39@gmail.com">mkmanishkumar39@gmail.com</a>
  </div>
</footer>

<script>
  document.getElementById('yr').textContent = new Date().getFullYear();
  const links = [...document.querySelectorAll('.nav-links a')];
  const map = links.map(a => ({a, sec: document.querySelector(a.getAttribute('href'))})).filter(x=>x.sec);
  const obs = new IntersectionObserver((es)=>{
    es.forEach(e=>{ if(e.isIntersecting){
      map.forEach(m=>m.a.style.color = m.sec===e.target ? 'var(--charcoal)' : '');
    }});
  },{rootMargin:'-45% 0px -50% 0px'});
  map.forEach(m=>obs.observe(m.sec));
</script>
</body>
</html>
