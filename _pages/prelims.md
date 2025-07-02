---
layout: page
title: Prelims Preparation
permalink: /prelims/
---

# 📚 UPSC Prelims Preparation

Your comprehensive collection of Prelims notes, organized by papers and subjects. Each note is interconnected to help you understand relationships between different topics.

## 📖 General Studies Paper 1

<div class="category-section">
  <div class="category-title">🌍 Geography</div>
  <div class="note-grid">
    <div class="note-card">
      <h4>Physical Geography</h4>
      <ul>
        <li>[[Earths Interior]] - Foundation of physical geography</li>
        <li>Geological processes and landforms</li>
        <li>Climate and weather patterns</li>
      </ul>
      <span class="badge prelims">Core Topic</span>
    </div>
    
    <div class="note-card">
      <h4>[[Strategy]] - Geography</h4>
      <p>Comprehensive approach to geography preparation, connecting physical and human geography concepts.</p>
      <span class="badge strategy">Strategy</span>
    </div>
  </div>
</div>

## 📖 General Studies Paper 2

<div class="category-section">
  <div class="category-title">🏛️ Polity & Governance</div>
  <div class="note-grid">
    <div class="note-card">
      <h4>Constitutional Framework</h4>
      <ul>
        <li>[[Constitution of India]] - Complete constitutional text</li>
        <li>[[Preamble]] - Constitutional philosophy</li>
        <li>Fundamental Rights and Duties</li>
        <li>Directive Principles of State Policy</li>
      </ul>
      <span class="badge prelims">High Weightage</span>
    </div>
    
    <div class="note-card">
      <h4>Governmental Structure</h4>
      <ul>
        <li>[[Judiciary]] - Complete judicial system</li>
        <li>[[Emergency Provisions]] - Constitutional crises</li>
        <li>Federal structure and Centre-State relations</li>
        <li>Local governance (Panchayati Raj & Urban)</li>
      </ul>
      <span class="badge prelims">Core Topic</span>
    </div>
    
    <div class="note-card">
      <h4>Important Documents</h4>
      <ul>
        <li>[[Constitutional Amendment]] - Major amendments</li>
        <li>[[7th CAA, 1956]] - States reorganization</li>
        <li>[[Polity Definitions]] - Key terminology</li>
        <li>[[POLITY]] - Mnemonics and tricks</li>
      </ul>
      <span class="badge prelims">Reference</span>
    </div>
  </div>
</div>

## 🔗 Interconnected Learning

<div class="category-section">
  <h3>How Topics Connect</h3>
  <div class="note-grid">
    <div class="note-card">
      <h4>🌍 Geography ↔️ 🏛️ Polity</h4>
      <p>Geographic features influence federal structure, disaster management connects to [[Emergency Provisions]], and environmental issues link to constitutional provisions.</p>
    </div>
    
    <div class="note-card">
      <h4>📚 Theory ↔️ 🌍 Current Affairs</h4>
      <p>Constitutional principles apply to current events, recent amendments connect to political developments, and judicial decisions shape governance.</p>
    </div>
    
    <div class="note-card">
      <h4>📝 Strategy ↔️ 📖 Content</h4>
      <p>Your [[STRATEGY FOR MAINS 2026]] connects to specific content areas, helping prioritize topics and build integrated understanding.</p>
    </div>
  </div>
</div>

## 🎯 Quick Access

### By Subject
- **Geography**: [[Earths Interior]] • [[Strategy]]
- **Polity**: [[Constitution of India]] • [[Judiciary]] • [[Emergency Provisions]]
- **Strategy**: [[STRATEGY FOR MAINS 2026]] • [[POLITY]] mnemonics

### By Importance
- **High Priority**: [[Constitution of India]] • [[Judiciary]] • [[Emergency Provisions]]
- **Medium Priority**: [[Earths Interior]] • [[Constitutional Amendment]]
- **Reference Material**: [[Polity Definitions]] • [[POLITY]] tricks

### Recent Updates
{% assign prelims_notes = site.notes | where: "category", "prelims" | sort: "last_modified_at_timestamp" | reverse %}
{% for note in prelims_notes limit: 5 %}
- {{ note.last_modified_at | date: "%Y-%m-%d" }} — [[{{ note.title }}]]
{% endfor %}

---

<div style="background: linear-gradient(135deg, #f0f9ff 0%, #e0f2fe 100%); padding: 2rem; border-radius: 12px; text-align: center;">
  <h3 style="color: #0369a1; margin-top: 0;">🚀 Start Your Prelims Journey</h3>
  <p>Begin with foundational topics and follow the connections. Each link leads to related concepts, building a comprehensive understanding.</p>
  <a href="{{ site.baseurl }}/constitution-of-india" class="internal-link" style="font-weight: 600; margin-right: 1rem;">Start with Constitution →</a>
  <a href="{{ site.baseurl }}/your-first-note" class="internal-link" style="font-weight: 600;">Learn How to Navigate →</a>
</div> 