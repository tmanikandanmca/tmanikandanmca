<style>{`
  @keyframes fadeSlideUp {
    from { opacity: 0; transform: translateY(20px); }
    to   { opacity: 1; transform: translateY(0); }
  }
  @keyframes shimmer {
    0%   { background-position: -200% center; }
    100% { background-position:  200% center; }
  }
  .profile-card {
    animation: fadeSlideUp 0.5s ease both;
  }
  .profile-card:nth-child(2) { animation-delay: 0.08s; }
  .profile-card:nth-child(3) { animation-delay: 0.16s; }
  .profile-card:nth-child(4) { animation-delay: 0.24s; }
  .profile-card:nth-child(5) { animation-delay: 0.32s; }
  .skill-pill {
    display: inline-flex;
    align-items: center;
    gap: 5px;
    padding: 4px 12px;
    border-radius: 999px;
    font-size: 12.5px;
    font-weight: 600;
    border: 1px solid rgba(255,255,255,0.12);
    background: rgba(255,255,255,0.06);
    color: inherit;
    transition: transform 0.18s, box-shadow 0.18s, background 0.18s;
    cursor: default;
  }
  .skill-pill:hover {
    transform: translateY(-2px) scale(1.05);
    box-shadow: 0 4px 16px rgba(0,0,0,0.25);
    background: rgba(255,255,255,0.12);
  }
  .cert-badge {
    display: flex;
    align-items: center;
    gap: 10px;
    padding: 10px 16px;
    border-radius: 12px;
    border: 1px solid rgba(0,120,212,0.35);
    background: linear-gradient(135deg, rgba(0,120,212,0.12), rgba(0,80,160,0.06));
    transition: transform 0.2s, box-shadow 0.2s;
    text-decoration: none !important;
    color: inherit !important;
  }
  .cert-badge:hover {
    transform: translateY(-3px);
    box-shadow: 0 8px 24px rgba(0,120,212,0.22);
  }
  .connect-link {
    display: inline-flex;
    align-items: center;
    gap: 8px;
    padding: 8px 18px;
    border-radius: 10px;
    font-weight: 600;
    font-size: 14px;
    transition: transform 0.18s, box-shadow 0.18s;
    text-decoration: none !important;
  }
  .connect-link:hover {
    transform: translateY(-2px);
    box-shadow: 0 6px 20px rgba(0,0,0,0.25);
  }
`}</style>

{/* ── Hero ── */}
<div class="profile-card not-prose" style="text-align:center;padding:40px 24px 32px;border-radius:20px;background:linear-gradient(135deg,rgba(0,120,212,0.12) 0%,rgba(80,0,180,0.10) 50%,rgba(0,180,120,0.08) 100%);border:1px solid rgba(255,255,255,0.10);margin-bottom:20px;position:relative;overflow:hidden;">
  <div style="position:absolute;inset:0;background:radial-gradient(ellipse at 50% -20%,rgba(0,120,212,0.18),transparent 60%);pointer-events:none;"></div>

  <div style="font-size:56px;margin-bottom:12px;filter:drop-shadow(0 4px 12px rgba(0,120,212,0.4))">👋</div>
  <h1 style="margin:0 0 6px;font-size:clamp(1.6rem,4vw,2.4rem);font-weight:800;background:linear-gradient(135deg,#60a5fa,#a78bfa,#34d399);background-size:200% auto;-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;animation:shimmer 3s linear infinite;">
    Hi, I'm Manikandan Thi
  </h1>
  <p style="margin:0 0 20px;font-size:15px;opacity:0.7;font-style:italic;">Software Professional · Problem Solver · Continuous Learner</p>

  <div style="display:flex;gap:10px;justify-content:center;flex-wrap:wrap;">
    <a href="https://www.linkedin.com/in/manikandan-thi/" class="connect-link" style="background:rgba(0,119,181,0.85);color:#fff;">
      <svg width="16" height="16" viewBox="0 0 24 24" fill="currentColor"><path d="M19 0h-14c-2.76 0-5 2.24-5 5v14c0 2.76 2.24 5 5 5h14c2.76 0 5-2.24 5-5v-14c0-2.76-2.24-5-5-5zm-11 19h-3v-10h3v10zm-1.5-11.27c-.97 0-1.75-.79-1.75-1.76s.78-1.76 1.75-1.76 1.75.79 1.75 1.76-.78 1.76-1.75 1.76zm13.5 11.27h-3v-5.5c0-1.31-.47-2.2-1.64-2.2-.9 0-1.43.6-1.66 1.18-.09.21-.11.5-.11.79v5.73h-3v-10h3v1.37c.4-.61 1.11-1.48 2.7-1.48 1.97 0 3.44 1.29 3.44 4.06v6.05z"/></svg>
      LinkedIn
    </a>
    <a href="https://github.com/tmanikandanmca" class="connect-link" style="background:rgba(30,30,30,0.85);color:#fff;border:1px solid rgba(255,255,255,0.15);">
      <svg width="16" height="16" viewBox="0 0 16 16" fill="currentColor"><path d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.5-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82a7.65 7.65 0 0 1 4 0c1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"/></svg>
      GitHub
    </a>
  </div>
</div>

{/* ── About ── */}
<div class="profile-card not-prose" style="padding:24px 28px;border-radius:16px;border:1px solid rgba(255,255,255,0.09);background:rgba(255,255,255,0.03);margin-bottom:16px;">
  <h2 style="margin:0 0 12px;font-size:1.1rem;font-weight:700;display:flex;align-items:center;gap:8px;">🚀 About Me</h2>
  <p style="margin:0 0 14px;line-height:1.7;opacity:0.88;">I'm a passionate software professional focused on building <strong>reliable, scalable, and user-friendly</strong> solutions. I enjoy solving real-world problems through technology and continuously improving my craft.</p>
  <div style="display:flex;flex-wrap:wrap;gap:8px;">
    <span style="padding:4px 12px;border-radius:8px;font-size:13px;background:rgba(96,165,250,0.12);border:1px solid rgba(96,165,250,0.25);color:#93c5fd;">💼 Open to collaborating</span>
    <span style="padding:4px 12px;border-radius:8px;font-size:13px;background:rgba(52,211,153,0.12);border:1px solid rgba(52,211,153,0.25);color:#6ee7b7;">🌱 Always learning</span>
    <span style="padding:4px 12px;border-radius:8px;font-size:13px;background:rgba(167,139,250,0.12);border:1px solid rgba(167,139,250,0.25);color:#c4b5fd;">🤝 Team-first mindset</span>
    <span style="padding:4px 12px;border-radius:8px;font-size:13px;background:rgba(251,191,36,0.10);border:1px solid rgba(251,191,36,0.22);color:#fcd34d;">⚡ Clean engineering</span>
  </div>
</div>

{/* ── Azure Certifications ── */}
<div class="profile-card not-prose" style="padding:24px 28px;border-radius:16px;border:1px solid rgba(0,120,212,0.2);background:linear-gradient(135deg,rgba(0,120,212,0.06),rgba(0,80,160,0.03));margin-bottom:16px;">
  <h2 style="margin:0 0 16px;font-size:1.1rem;font-weight:700;display:flex;align-items:center;gap:8px;">
    <svg width="20" height="20" viewBox="0 0 24 24" fill="#0078D4"><path d="M13.05 4.24L7.07 17.19l5.97.69 4.69-9.75z"/><path d="M22.85 18.03l-4.5-13.6L14.66 14l5.03 5.75zM1.15 18.03l9.47 1.72L4.35 4.43z"/></svg>
    Azure Certifications
  </h2>
  <div style="display:flex;flex-wrap:wrap;gap:10px;">
    <a href="https://learn.microsoft.com/en-us/certifications/azure-fundamentals/" target="_blank" rel="noopener" class="cert-badge">
      <div style="width:36px;height:36px;border-radius:8px;background:linear-gradient(135deg,#0078D4,#00BCF2);display:flex;align-items:center;justify-content:center;flex-shrink:0;">
        <svg width="20" height="20" viewBox="0 0 24 24" fill="white"><path d="M13.05 4.24L7.07 17.19l5.97.69 4.69-9.75z"/><path d="M22.85 18.03l-4.5-13.6L14.66 14l5.03 5.75zM1.15 18.03l9.47 1.72L4.35 4.43z"/></svg>
      </div>
      <div>
        <div style="font-size:13px;font-weight:700;color:#60a5fa;">AZ-900</div>
        <div style="font-size:11px;opacity:0.7;">Azure Fundamentals</div>
      </div>
    </a>
    <a href="https://learn.microsoft.com/en-us/certifications/azure-developer/" target="_blank" rel="noopener" class="cert-badge">
      <div style="width:36px;height:36px;border-radius:8px;background:linear-gradient(135deg,#0078D4,#7719AA);display:flex;align-items:center;justify-content:center;flex-shrink:0;">
        <svg width="20" height="20" viewBox="0 0 24 24" fill="white"><path d="M13.05 4.24L7.07 17.19l5.97.69 4.69-9.75z"/><path d="M22.85 18.03l-4.5-13.6L14.66 14l5.03 5.75zM1.15 18.03l9.47 1.72L4.35 4.43z"/></svg>
      </div>
      <div>
        <div style="font-size:13px;font-weight:700;color:#a78bfa;">AZ-204</div>
        <div style="font-size:11px;opacity:0.7;">Azure Developer Associate</div>
      </div>
    </a>
    <a href="https://learn.microsoft.com/en-us/certifications/azure-solutions-architect/" target="_blank" rel="noopener" class="cert-badge">
      <div style="width:36px;height:36px;border-radius:8px;background:linear-gradient(135deg,#00BCF2,#0078D4);display:flex;align-items:center;justify-content:center;flex-shrink:0;">
        <svg width="20" height="20" viewBox="0 0 24 24" fill="white"><path d="M13.05 4.24L7.07 17.19l5.97.69 4.69-9.75z"/><path d="M22.85 18.03l-4.5-13.6L14.66 14l5.03 5.75zM1.15 18.03l9.47 1.72L4.35 4.43z"/></svg>
      </div>
      <div>
        <div style="font-size:13px;font-weight:700;color:#38bdf8;">AZ-305</div>
        <div style="font-size:11px;opacity:0.7;">Azure Solutions Architect Expert</div>
      </div>
    </a>
  </div>
</div>

{/* ── Skills ── */}
<div class="profile-card not-prose" style="padding:24px 28px;border-radius:16px;border:1px solid rgba(255,255,255,0.09);background:rgba(255,255,255,0.03);margin-bottom:16px;">
  <h2 style="margin:0 0 14px;font-size:1.1rem;font-weight:700;">🛠️ Skills &amp; Tools</h2>
  <div style="display:flex;flex-wrap:wrap;gap:8px;">
    <span class="skill-pill">🟣 C#</span>
    <span class="skill-pill">🔷 .NET / .NET Core</span>
    <span class="skill-pill">🔴 Angular</span>
    <span class="skill-pill">🔵 TypeScript</span>
    <span class="skill-pill">🗄️ SQL Server</span>
    <span class="skill-pill">🐘 PostgreSQL</span>
    <span class="skill-pill">☁️ Azure</span>
    <span class="skill-pill">🐙 Git / GitHub</span>
    <span class="skill-pill">🧩 REST APIs</span>
    <span class="skill-pill">📐 Design Patterns</span>
  </div>
</div>

{/* ── What I Do ── */}
<div class="profile-card not-prose" style="padding:24px 28px;border-radius:16px;border:1px solid rgba(255,255,255,0.09);background:rgba(255,255,255,0.03);margin-bottom:16px;">
  <h2 style="margin:0 0 14px;font-size:1.1rem;font-weight:700;">📌 What I Do</h2>
  <div style="display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:10px;">
    {[
      { icon:'🏗️', text:'Design & build software solutions' },
      { icon:'⚙️', text:'Backend, web & database-driven apps' },
      { icon:'📚', text:'Learn & adapt to new tech quickly' },
      { icon:'✨', text:'Quality, readability & maintainability' },
    ].map(item => (
      <div style="display:flex;align-items:flex-start;gap:10px;padding:12px;border-radius:10px;background:rgba(255,255,255,0.04);border:1px solid rgba(255,255,255,0.07);">
        <span style="font-size:20px;flex-shrink:0;">{item.icon}</span>
        <span style="font-size:13.5px;line-height:1.5;opacity:0.88;">{item.text}</span>
      </div>
    ))}
  </div>
</div>

{/* ── GitHub Stats ── */}
<div class="profile-card not-prose" style="padding:24px 28px;border-radius:16px;border:1px solid rgba(255,255,255,0.09);background:rgba(255,255,255,0.03);margin-bottom:16px;">
  <h2 style="margin:0 0 16px;font-size:1.1rem;font-weight:700;">📈 GitHub Snapshot</h2>
  <div style="display:flex;flex-wrap:wrap;gap:12px;justify-content:center;">
    <img src="https://github-readme-stats.vercel.app/api?username=tmanikandanmca&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=60a5fa&text_color=94a3b8&icon_color=a78bfa" alt="GitHub Stats" style="border-radius:12px;max-width:100%;" />
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=tmanikandanmca&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=60a5fa&text_color=94a3b8" alt="Top Languages" style="border-radius:12px;max-width:100%;" />
  </div>
</div>

{/* ── Motto ── */}
<div class="profile-card not-prose" style="padding:24px 28px;border-radius:16px;text-align:center;background:linear-gradient(135deg,rgba(96,165,250,0.10),rgba(167,139,250,0.10),rgba(52,211,153,0.08));border:1px solid rgba(255,255,255,0.10);">
  <div style="font-size:28px;margin-bottom:8px;">✨</div>
  <blockquote style="margin:0;font-size:1.1rem;font-style:italic;font-weight:500;background:linear-gradient(135deg,#60a5fa,#a78bfa,#34d399);-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;">
    "Keep learning, keep building, and keep growing."
  </blockquote>
</div>
