---
layout: page
title: "⚡ About"
permalink: /about/
hide_title: true
---

<div style="display: flex; gap: 2rem; align-items: center;">
  <!-- Text LEFT -->
  <div style="flex: 1;">
    <p>
      Hi 👋, I'm Adri, a multidisciplinary technologist building systems to navigate complexity. This site 🧭 shares battle-tested templates, automation scripts, and concise guides from my workflow—focused 🤖 on practical tool integrations 🔌, process frameworks 🧩, and systems thinking ⚡ for technical work across domains. Expect actionable solutions, not theory. Curated toolkit, not prescribed path.
    </p>
  </div>
  
  <!-- Photo RIGHT -->
  <div>
    <img src="/assets/portrait-2.png" alt="Adri's Photo" class="hero-photo" style="width: 180px; height: 180px; border-radius: 50%; object-fit: cover;">
  </div>
</div>


<!-- How to Engage Section -->
<section class="section">
  <h2><span class="emoji">🚀</span> How to Engage</h2>
  
  <div class="engage-cards">
    <a href="/guides" class="engage-card">
      <div class="engage-icon">⚙️</div>
      <div class="engage-content">
        <h3>Browse Guides (Coming Soon)</h3>
        <p>Concise tutorials and walkthroughs</p>
        <span class="engage-link">Explore →</span>
      </div>
    </a>
    
    <a href="https://github.com/adriscircuit-arch" class="engage-card">
      <div class="engage-icon">💻</div>
      <div class="engage-content">
        <h3>GitHub (Coming Soon)</h3>
        <p>Open templates and source code</p>
        <span class="engage-link">View Repos →</span>
      </div>
    </a>
    
    <a href="/updates" class="engage-card">
      <div class="engage-icon">📬</div>
      <div class="engage-content">
        <h3>Stay Updated</h3>
        <p>Occasional announcements</p>
        <span class="engage-link">Subscribe →</span>
      </div>
    </a>
    
    <a href="https://youtube.com/@adriscircuit" class="engage-card">
      <div class="engage-icon">🎥</div>
      <div class="engage-content">
        <h3>YouTube (Coming Soon)</h3>
        <p>Video tutorials and demos</p>
        <span class="engage-link">Watch →</span>
      </div>
    </a>
  </div>
</section>

<!-- Transparency Section -->
<section class="transparency-section">
  <div class="transparency-header">
    <span class="emoji">⚖️</span>
    <h2>Transparency Note</h2>
  </div>
  
  <div class="transparency-content">
    <div class="transparency-item">
      <div class="transparency-icon">🔒</div>
      <div>
        <h3>Independent Project</h3>
        <p>All content represents independent work and opinions. Not affiliated with any employer.</p>
      </div>
    </div>
    
    
    <div class="transparency-item">
      <div class="transparency-icon">🔗</div>
      <div>
        <h3>Transparent Affiliates</h3>
        <p>Some links may be affiliate links (always marked). Supports the project at no extra cost to you.</p>
      </div>
    </div>
    
  </div>
</section>

<style>

.about-hero {
  display: flex;
  flex-direction: column;
  gap: 2rem;
  padding: 4rem 0;
}

.logo-container {
  display: flex;
  align-items: center;
  gap: 2rem;  /* Space between logo and photo */
  justify-content: center;
}

.site-logo {
  height: 80px;  /* Adjust as needed */
  width: auto;
}

.hero-photo {
  height: 150px;  /* Your photo size */
  width: 150px;
  border-radius: 50%;  /* Circular photo */
  object-fit: cover;
  border: 4px solid rgba(255,255,255,0.3);
  box-shadow: 0 4px 14px rgba(0,0,0,0.2);
}

@media (max-width: 768px) {
  .logo-container {
    flex-direction: column;
    gap: 1rem;
  }
}


/* ===== CONTAINER ===== */
.about-container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 2rem 1rem;
}

/* ===== HERO SECTION ===== */
.about-hero {
  text-align: center;
  padding: 3rem 1rem;
  margin-bottom: 4rem;
/*  background: linear-gradient(135deg, #f8fafc 0%, #f1f5f9 100%);
  border-radius: 16px;
  border: 1px solid #e2e8f0;*/
}

.logo-container {
  margin-bottom: 2rem;
}

.site-logo {
  height: 80px;
  width: auto;
  margin: 0 auto;
}

.logo-fallback {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 1rem;
}

.logo-ac {
  font-size: 3.5rem;
}

.logo-fallback h1 {
  font-size: 3rem;
  margin: 0;
  color: #1e293b;
}

.hero-tagline {
  font-size: 1.5rem;
  color: #475569;
  margin-bottom: 1rem;
  font-weight: 400;
}

.hero-description {
  font-size: 1.1rem;
  color: #64748b;
  max-width: 700px;
  margin: 0 auto 2.5rem;
  line-height: 1.6;
}

.hero-stats {
  display: flex;
  justify-content: center;
  gap: 3rem;
  margin-top: 2rem;
}

.stat {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.stat-number {
  font-size: 2.5rem;
  font-weight: 700;
  color: #4f46e5;
  line-height: 1;
}

.stat-label {
  font-size: 0.9rem;
  color: #64748b;
  text-transform: uppercase;
  letter-spacing: 1px;
  margin-top: 0.5rem;
}

/* ===== SECTIONS ===== */
.section {
  margin: 4rem 0;
}

.section h2 {
  font-size: 2rem;
  color: #1e293b;
  margin-bottom: 2rem;
  display: flex;
  align-items: center;
  gap: 0.75rem;
}

.emoji {
  font-size: 1.8rem;
}

/* ===== CARDS GRID ===== */
.cards-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 2rem;
  margin-top: 2rem;
}

.card {
  padding: 2rem;
  border-radius: 12px;
  background: white;
  border: 1px solid #e2e8f0;
  transition: all 0.3s ease;
}

.card:hover {
  transform: translateY(-4px);
  box-shadow: 0 12px 24px rgba(0, 0, 0, 0.08);
  border-color: #c7d2fe;
}

.card-icon {
  font-size: 2.5rem;
  margin-bottom: 1rem;
}

.card-title {
  font-size: 1.25rem;
  color: #1e293b;
  margin: 0 0 0.75rem 0;
}

.card-text {
  color: #64748b;
  line-height: 1.6;
  margin: 0;
}

/* ===== ENGAGE CARDS ===== */
.engage-cards {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 1.5rem;
  margin-top: 2rem;
}

.engage-card {
  display: flex;
  align-items: flex-start;
  gap: 1.25rem;
  padding: 1.75rem;
  border-radius: 12px;
  background: white;
  border: 1px solid #e2e8f0;
  text-decoration: none;
  color: inherit;
  transition: all 0.3s ease;
}

.engage-card:hover {
  transform: translateY(-3px);
  box-shadow: 0 8px 20px rgba(0, 0, 0, 0.06);
  border-color: #4f46e5;
  color: #4f46e5;
}

.engage-icon {
  font-size: 2rem;
  flex-shrink: 0;
}

.engage-content {
  flex: 1;
}

.engage-content h3 {
  margin: 0 0 0.5rem 0;
  font-size: 1.1rem;
  color: #1e293b;
}

.engage-content p {
  margin: 0 0 0.75rem 0;
  color: #64748b;
  font-size: 0.95rem;
}

.engage-link {
  color: #4f46e5;
  font-weight: 500;
  font-size: 0.9rem;
  display: inline-flex;
  align-items: center;
  gap: 0.25rem;
}

.engage-card:hover .engage-link {
  transform: translateX(4px);
  transition: transform 0.2s ease;
}

/* ===== TRANSPARENCY SECTION ===== */
.transparency-section {
  margin: 5rem 0 3rem;
  padding: 3rem;
  background: linear-gradient(135deg, #fefce8 0%, #fef3c7 100%);
  border: 1px solid #fde047;
  border-radius: 16px;
}

.transparency-header {
  display: flex;
  align-items: center;
  gap: 1rem;
  margin-bottom: 2.5rem;
}

.transparency-header h2 {
  margin: 0;
  color: #92400e;
}

.transparency-content {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 2rem;
}

.transparency-item {
  display: flex;
  gap: 1.25rem;
  align-items: flex-start;
}

.transparency-icon {
  font-size: 1.5rem;
  flex-shrink: 0;
  color: #92400e;
}

.transparency-item h3 {
  margin: 0 0 0.5rem 0;
  color: #92400e;
  font-size: 1.1rem;
}

.transparency-item p {
  margin: 0;
  color: #92400e;
  opacity: 0.9;
  font-size: 0.95rem;
  line-height: 1.5;
}

/* ===== RESPONSIVE ===== */
@media (max-width: 768px) {
  .about-hero {
    padding: 2rem 1rem;
  }
  
  .logo-fallback h1 {
    font-size: 2.2rem;
  }
  
  .hero-tagline {
    font-size: 1.25rem;
  }
  
  .hero-stats {
    gap: 2rem;
  }
  
  .stat-number {
    font-size: 2rem;
  }
  
  .section {
    margin: 3rem 0;
  }
  
  .section h2 {
    font-size: 1.75rem;
  }
  
  .cards-grid,
  .engage-cards,
  .transparency-content {
    grid-template-columns: 1fr;
  }
  
  .transparency-section {
    padding: 2rem 1.5rem;
  }
}

@media (max-width: 480px) {
  .hero-stats {
    flex-direction: column;
    gap: 1.5rem;
  }
  
  .engage-card {
    flex-direction: column;
    text-align: center;
    align-items: center;
  }
  
  .transparency-item {
    flex-direction: column;
    text-align: center;
    align-items: center;
  }
}
</style>
