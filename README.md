<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Jiawen Zheng | Marketing, BI & Communication</title>
  <style>
    :root {
      --bg: #f7f9fc;
      --card: #ffffff;
      --primary: #1f3a5f; /* navy */
      --accent: #4a6fa5; /* muted blue */
      --text: #1f2933;
      --subtext: #6b7280;
    }
    * { box-sizing: border-box; }
    body {
      margin: 0;
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Arial, sans-serif;
      background: var(--bg);
      color: var(--text);
      line-height: 1.6;
    }
    a { color: var(--accent); text-decoration: none; }
    header {
      background: linear-gradient(135deg, var(--primary), #0f172a);
      color: white;
      padding: 72px 24px;
    }
    .container {
      max-width: 1100px;
      margin: auto;
    }
    header h1 {
      font-size: 42px;
      margin-bottom: 12px;
    }
    header p {
      max-width: 720px;
      font-size: 18px;
      opacity: 0.95;
    }
    section {
      padding: 64px 24px;
    }
    h2 {
      font-size: 28px;
      margin-bottom: 24px;
      color: var(--primary);
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 24px;
    }
    .card {
      background: var(--card);
      border-radius: 16px;
      padding: 24px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.06);
      transition: transform 0.2s ease, box-shadow 0.2s ease;
    }
    .card:hover {
      transform: translateY(-4px);
      box-shadow: 0 16px 40px rgba(0,0,0,0.1);
    }
    .card h3 {
      margin-top: 0;
      margin-bottom: 8px;
      color: var(--primary);
    }
    .meta {
      font-size: 14px;
      color: var(--subtext);
      margin-bottom: 12px;
    }
    .tags span {
      display: inline-block;
      background: #eef2f7;
      color: #334155;
      font-size: 12px;
      padding: 6px 12px;
      border-radius: 999px;
      margin: 4px 6px 0 0;
    }
    footer {
      background: #0f172a;
      color: #cbd5e1;
      padding: 48px 24px;
      text-align: center;
    }
    footer a { color: #93c5fd; }
  </style>
</head>
<body>

<header>
  <div class="container">
    <h1>Jiawen Zheng</h1>
    <p>
      Marketing, Business Intelligence & Communication Professional specializing in
      data-driven media strategy, audience insights, and clear storytelling across
      analytics and creative teams.
    </p>
  </div>
</header>

<section>
  <div class="container">
    <h2>Selected Work</h2>
    <div class="grid">

      <a href="absolut.html" class="card">
        <h3>Absolut RTD Media Strategy</h3>
        <div class="meta">Media Analytics · BI · Mindshare</div>
        <p>
          Data-driven, full-funnel media recommendation designed to grow top-of-mind
          awareness for Absolut RTD among underserved audiences.
        </p>
        <div class="tags">
          <span>SQL</span><span>Tableau</span><span>MRI Simmons</span><span>Media Strategy</span>
        </div>
      </a>

      <a href="team-adsolut.html" class="card">
        <h3>Team Adsolut Culture Concept</h3>
        <div class="meta">Creative Strategy · Visual Communication</div>
        <p>
          A culture-led branding and design concept translating globalization,
          sustainability, and Gen Z identity into a unified visual system.
        </p>
        <div class="tags">
          <span>Brand Storytelling</span><span>Creative Strategy</span><span>Design</span>
        </div>
      </a>

      <a href="gamco.html" class="card">
        <h3>GAMCO Strategy & Marketing</h3>
        <div class="meta">Marketing · Operations · Digital Strategy</div>
        <p>
          Marketing and operations projects focused on campaign execution,
          website development, and process improvement in a B2B environment.
        </p>
        <div class="tags">
          <span>Digital Marketing</span><span>Web Design</span><span>Process Optimization</span>
        </div>
      </a>

      <a href="art.html" class="card">
        <h3>Art & Community Engagement</h3>
        <div class="meta">Communication · Culture · Volunteering</div>
        <p>
          Community-based art and event support projects emphasizing communication,
          cultural storytelling, and nonprofit engagement.
        </p>
        <div class="tags">
          <span>Communication</span><span>Community</span><span>Creative Practice</span>
        </div>
      </a>

    </div>
        <p>
          End-to-end media recommendation focused on increasing top-of-mind awareness
          for Absolut RTD among underserved women aged 22–34, supported by MRI Simmons
          insights and cross-channel planning.
        </p>
        <div class="tags">
          <span>Media Strategy</span><span>BI</span><span>MRI Simmons</span><span>Audience Insights</span>
        </div>
      </div>

      <div class="card">
        <h3>Team Adsolut Culture Concept</h3>
        <div class="meta">Creative Strategy · Brand Storytelling</div>
        <p>
          Visual and conceptual identity project translating globalization, sustainability,
          technology, and Gen Z culture into a cohesive design system for GroupM interns.
        </p>
        <div class="tags">
          <span>Creative Strategy</span><span>Branding</span><span>Visual Communication</span>
        </div>
      </div>

      <div class="card">
        <h3>GAMCO Strategy & Operations</h3>
        <div class="meta">Process Improvement · Corporate Strategy</div>
        <p>
          Strategy and operations work supporting automation, documentation, and
          data-driven decision-making within manufacturing and R&D teams.
        </p>
        <div class="tags">
          <span>Operations</span><span>Process Optimization</span><span>Strategy</span>
        </div>
      </div>

      <div class="card">
        <h3>Red Envelope Art Training</h3>
        <div class="meta">Art · Culture · Community Engagement</div>
        <p>
          Community-based art project creating Lunar New Year installations that
          combined cultural heritage, craftsmanship, and nonprofit fundraising.
        </p>
        <div class="tags">
          <span>Art & Culture</span><span>Community</span><span>Creative Practice</span>
        </div>
      </div>

    </div>
  </div>
</section>

<footer>
  <p>
    <a href="mailto:jiawenzheng52@gmail.com">jiawenzheng52@gmail.com</a> ·
    <a href="https://www.linkedin.com/in/jiawen-zheng1" target="_blank">LinkedIn</a>
    <br />
    © Jiawen Zheng
  </p>
</footer>

</body>
</html>
