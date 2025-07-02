---
layout: page
title: UPSC Digital Garden
id: home
permalink: /
---

# UPSC Digital Garden

A connected collection of notes for comprehensive UPSC preparation. Each note links to related concepts, building a network of knowledge that mirrors how topics actually connect in the exam.

## Core Subjects

### Geography
- [[Earths Interior]] - Foundation of physical geography
- Climate and environmental connections
- Links to disaster management and policy

### Polity & Governance  
- [[Constitution of India]] - Complete constitutional framework
- [[Judiciary]] - Judicial system and governance
- [[Emergency Provisions]] - Constitutional crisis management
- [[Preamble]] - Constitutional philosophy

### Strategy & Planning
- [[STRATEGY FOR MAINS 2026]] - Comprehensive preparation approach
- Subject integration and timeline planning
- Answer writing and revision strategies

## How It Works

This digital garden uses `[[double brackets]]` to create connections between notes. When you link to a note, it automatically appears in that note's "Linked Notes" section, creating a web of bidirectional connections.

**Example connections:**
- [[Constitution of India]] → [[Judiciary]] → [[Emergency Provisions]]
- [[Earths Interior]] → Environmental policies → Constitutional provisions

## Recent Updates

{% assign recent_notes = site.notes | sort: "last_modified_at_timestamp" | reverse %}
{% for note in recent_notes limit: 6 %}
- {{ note.last_modified_at | date: "%Y-%m-%d" }} — [[{{ note.title }}]]
{% endfor %}

## Quick Start

1. **Explore connections**: Follow the `[[links]]` between related topics
2. **Build your network**: Add new connections as you study  
3. **Use for revision**: Follow backlinks to review related concepts
4. **Start anywhere**: [[Your first note]] explains how to navigate

---

*This garden grows as you add connections. Start with any topic and follow the links to build comprehensive understanding.*
