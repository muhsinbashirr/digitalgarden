---
layout: page
title: UPSC Digital Garden
id: home
permalink: /
---

# UPSC Digital Garden

A connected collection of notes for comprehensive UPSC preparation. Each note links to related concepts, building a network of knowledge that mirrors how topics actually connect in the exam.

## Prelims Preparation

<div class="note-grid">
  <div class="note-card">
    <h3>Geography</h3>
    <p>Foundation of physical geography with environmental connections</p>
    <ul>
      <li>[[Earths Interior]] - Core geological concepts</li>
      <li>Climate patterns and environmental policy links</li>
      <li>Disaster management connections</li>
    </ul>
  </div>
  
  <div class="note-card">
    <h3>Polity & Governance</h3>
    <p>Complete constitutional framework with governance connections</p>
    <ul>
      <li>[[Constitution of India]] - Fundamental constitutional law</li>
      <li>[[Judiciary]] - Judicial system and processes</li>
      <li>[[Emergency Provisions]] - Crisis management framework</li>
      <li>[[Polity Definitions]] - Key terminology</li>
    </ul>
  </div>
</div>

## Mains Strategy

<div class="category-section">
  <div class="category-title">Comprehensive Preparation Approach</div>
  <div class="note-card">
    <h3>Strategic Planning</h3>
    <p>Integrated approach for Mains 2026 with timeline and subject connections</p>
    <ul>
      <li>[[STRATEGY FOR MAINS 2026]] - Complete preparation roadmap</li>
      <li>Subject integration methodology</li>
      <li>Answer writing techniques</li>
      <li>Revision strategies and timeline</li>
    </ul>
  </div>
</div>

## Learning Resources

<div class="note-grid">
  <div class="note-card">
    <h3>Study Aids</h3>
    <p>Memory techniques and quick reference materials</p>
    <ul>
      <li>[[POLITY]] - Polity mnemonics</li>
      <li>[[FINILOGY TIPS AND TRICKS]] - Study techniques</li>
      <li>[[Constitutional Amendment]] - Amendment summaries</li>
    </ul>
  </div>
  
  <div class="note-card">
    <h3>Key Connections</h3>
    <p>How subjects interconnect in the UPSC ecosystem</p>
    <ul>
      <li>Constitution → Judiciary → Emergency Provisions</li>
      <li>Geography → Environment → Policy</li>
      <li>Current Affairs → Static Knowledge</li>
    </ul>
  </div>
</div>

## How the Digital Garden Works

### Bidirectional Linking System
This garden uses `[[double brackets]]` to create connections between notes. When you link to a note, it automatically appears in that note's "Linked Notes" section, creating a web of bidirectional connections that mirror the interconnected nature of UPSC topics.

### Knowledge Networks
**Constitutional Law Network:**
- [[Constitution of India]] ↔ [[Judiciary]] ↔ [[Emergency Provisions]]

**Geography-Policy Connections:**
- [[Earths Interior]] → Environmental policies → Constitutional environmental provisions

**Strategic Integration:**
- [[STRATEGY FOR MAINS 2026]] connects to all subject areas with timeline planning

### Navigation Features
1. **Explore Dropdown**: Access organized content by subject area
2. **Backlinks**: See which notes reference current topic
3. **Note Connections**: Follow related concepts seamlessly
4. **Category Pages**: Subject-wise organization for systematic study

---

## Recent Activity

{% assign recent_notes = site.notes | sort: "last_modified_at_timestamp" | reverse %}
<div class="backlinks-container">
{% for note in recent_notes limit: 4 %}
  <div class="backlink-box">
    <a href="{{ note.url | prepend: site.baseurl }}" class="internal-link">{{ note.title }}</a>
    <div class="backlink-excerpt">
      Updated: {{ note.last_modified_at | date: "%B %d, %Y" }}
      <span class="badge">{{ note.url | split: '/' | slice: 2 | first | upcase }}</span>
    </div>
  </div>
{% endfor %}
</div>

---

### Getting Started

**New to the garden?** Start with [[your-first-note]] to understand the navigation system, or jump directly into any subject area using the **Explore** dropdown menu above.

**Building connections?** Use `[[Note Name]]` syntax to link related concepts as you study. The system automatically creates bidirectional connections.

**Preparing for exams?** Follow the strategic approach in [[STRATEGY FOR MAINS 2026]] and use subject-specific notes for targeted preparation.

*This digital garden grows stronger with each connection you make. Start anywhere and let the links guide your learning journey.*
