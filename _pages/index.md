---
layout: page
title: UPSC Digital Garden
id: home
permalink: /
---

# Welcome to Your UPSC Digital Garden! 🌱

<div class="category-section">
  <div class="category-title">🎯 Your Comprehensive UPSC Preparation Hub</div>
  <p>This digital garden contains interconnected notes covering all aspects of UPSC preparation. Each note is linked to related concepts, creating a web of knowledge that mirrors how topics connect in the actual exam.</p>
</div>

## 📚 Main Categories

<div class="note-grid">
  <div class="note-card">
    <h3>🌍 Geography</h3>
    <p>Physical and human geography notes including:</p>
    <ul>
      <li>[[Earths Interior]] - Structure and composition</li>
      <li>Geographic strategies and patterns</li>
      <li>Regional geography concepts</li>
    </ul>
    <span class="badge prelims">Prelims</span>
  </div>

  <div class="note-card">
    <h3>🏛️ Polity & Governance</h3>
    <p>Constitutional framework and governance:</p>
    <ul>
      <li>[[Constitution of India]] - Complete framework</li>
      <li>[[Judiciary]] - Judicial system structure</li>
      <li>[[Emergency Provisions]] - Constitutional emergencies</li>
      <li>[[Preamble]] - Constitutional philosophy</li>
    </ul>
    <span class="badge prelims">Prelims</span> <span class="badge mains">Mains</span>
  </div>

  <div class="note-card">
    <h3>📋 Strategy & Planning</h3>
    <p>Comprehensive preparation strategies:</p>
    <ul>
      <li>[[STRATEGY FOR MAINS 2026]] - Long-term planning</li>
      <li>Subject-wise preparation approaches</li>
      <li>Time management techniques</li>
    </ul>
    <span class="badge strategy">Strategy</span>
  </div>
</div>

## 🎯 Prelims Preparation

<div class="category-section">
  <div class="category-title">📖 GS Paper 1</div>
  <div class="note-grid">
    <div class="note-card">
      <h4>Geography</h4>
      <p>Physical geography fundamentals and current developments</p>
      <a href="{{ site.baseurl }}/prelims-gs1-geography" class="internal-link">Explore Geography Notes →</a>
    </div>
  </div>
</div>

<div class="category-section">
  <div class="category-title">📖 GS Paper 2</div>
  <div class="note-grid">
    <div class="note-card">
      <h4>Polity & Constitution</h4>
      <p>Constitutional provisions, governance structures, and recent developments</p>
      <a href="{{ site.baseurl }}/prelims-gs2-polity" class="internal-link">Explore Polity Notes →</a>
    </div>
  </div>
</div>

## 📝 Recent Updates

<div class="category-section">
  <strong>Recently Updated Notes</strong>
  <ul>
    {% assign recent_notes = site.notes | sort: "last_modified_at_timestamp" | reverse %}
    {% for note in recent_notes limit: 8 %}
      <li>
        <span class="update-date">{{ note.last_modified_at | date: "%Y-%m-%d" }}</span> — 
        <a class="internal-link" href="{{ site.baseurl }}{{ note.url }}">{{ note.title }}</a>
      </li>
    {% endfor %}
  </ul>
</div>

## 🎯 Quick Start Tips

<div class="note-grid">
  <div class="note-card">
    <h4>🔗 Linking Notes</h4>
    <p>Use double brackets like <code>[[Note Name]]</code> to create connections between related topics. This builds a knowledge network!</p>
  </div>
  
  <div class="note-card">
    <h4>🏷️ Organization</h4>
    <p>Notes are organized by subject and topic. Use the navigation to explore different sections of your preparation.</p>
  </div>
  
  <div class="note-card">
    <h4>📊 Visual Learning</h4>
    <p>The note graph shows connections between topics, helping you understand the bigger picture of your preparation.</p>
  </div>
</div>

---

<div style="text-align: center; margin-top: 2rem; padding: 2rem; background: linear-gradient(135deg, #f0f9ff 0%, #e0f2fe 100%); border-radius: 12px;">
  <h3 style="color: #0369a1; margin-bottom: 1rem;">🚀 Start Exploring</h3>
  <p style="margin-bottom: 1.5rem;">Click on any link above to start your learning journey. Each note connects to others, creating a comprehensive web of UPSC knowledge.</p>
  <a href="{{ site.baseurl }}/your-first-note" class="internal-link" style="font-weight: 600; font-size: 1.1rem;">Begin with Your First Note →</a>
</div>
