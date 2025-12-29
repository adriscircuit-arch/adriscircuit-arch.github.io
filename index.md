---
layout: home
title: ""
---

<div class="hero-circuit">
  <div class="hero-content">
  <div class="logo-container">
    <img src="/assets/logo.svg" alt="Adri's Circuit Logo" class="site-logo">
    <!-- Or use text if no logo yet -->
    <div class="logo-fallback">
    </div>
  </div>

    <p class="hero-tagline">Systems for Multidisciplinary Technologists</p>
    <p class="hero-description">Battle-tested templates, automation scripts, and concise guides for managing technical complexity.</p>
    
    <!--div class="hero-cta">
      <a href="/circuits" class="cta-primary">
        <span>🚀 Browse Circuits</span>
      </a>
      <a href="/updates" class="cta-secondary">
        <span>📬 Stay Updated</span>
      </a>
    </div-->
  </div>

<hr> 
 
<style>
.hero-circuit {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0rem 1rem;
}
.hero-content {
  text-align: center;
  margin-bottom: 1rem;
}
.hero-content h1 {
  font-size: 4rem;
  margin-bottom: 0.5rem;
  letter-spacing: -1.5px;
}
.hero-tagline {
  font-size: 1.5rem;
  color: #666;
  margin-bottom: 1.5rem;
  font-weight: 300;
}
.hero-description {
  font-size: 1.1rem;
  color: #555;
  max-width: 600px;
  margin: 0 auto 0.5rem;
  line-height: 1.6;
}
.hero-cta {
  display: flex;
  gap: 1rem;
  justify-content: center;
  flex-wrap: wrap;
}
.cta-primary, .cta-secondary {
  padding: 1rem 2rem;
  border-radius: 8px;
  text-decoration: none;
  font-weight: 500;
  display: inline-flex;
  align-items: center;
  gap: 0.5rem;
  transition: all 0.2s;
}
.cta-primary {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white;
  box-shadow: 0 4px 14px rgba(102, 126, 234, 0.3);
}
.cta-primary:hover {
  transform: translateY(-2px);
  box-shadow: 0 6px 20px rgba(102, 126, 234, 0.4);
}
.cta-secondary {
  background: white;
  color: #333;
  border: 2px solid #e2e8f0;
}
.cta-secondary:hover {
  border-color: #667eea;
  transform: translateY(-2px);
}
.hero-preview {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 2rem;
  margin-top: 3rem;
}
.preview-card {
  padding: 2rem;
  border-radius: 12px;
  background: white;
  border: 1px solid #e2e8f0;
  text-align: center;
  transition: transform 0.3s, box-shadow 0.3s;
}
.preview-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 10px 30px rgba(0,0,0,0.08);
}
.preview-emoji {
  font-size: 3rem;
  display: block;
  margin-bottom: 1rem;
}
.preview-card h3 {
  margin: 0.5rem 0;
  color: #333;
}
.preview-card p {
  color: #666;
  margin: 0;
  font-size: 0.95rem;
}

@media (max-width: 768px) {
  .hero-content h1 { font-size: 2.8rem; }
  .hero-tagline { font-size: 1.2rem; }
  .hero-cta { flex-direction: column; }
  .cta-primary, .cta-secondary { width: 100%; justify-content: center; }
}
</style>
