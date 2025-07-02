---
layout: page
title: Prelims Preparation
permalink: /prelims/
---

# Prelims Preparation

Comprehensive notes for UPSC Prelims, organized by papers and interconnected for holistic understanding.

## General Studies Paper 1

### Geography
- [[Earths Interior]] - Physical geography foundation
- [[Strategy]] - Geographic approach and methodology
- Climate, landforms, and environmental geography

### History & Culture
- Ancient, medieval, and modern Indian history
- Art, culture, and heritage topics
- Freedom struggle and constitutional development

## General Studies Paper 2

### Polity & Governance
- [[Constitution of India]] - Complete constitutional framework
- [[Judiciary]] - Judicial system and recent developments  
- [[Emergency Provisions]] - Constitutional emergency mechanisms
- [[Preamble]] - Constitutional philosophy and values

### Current Affairs Integration
- [[Constitutional Amendment]] - Recent amendments and implications
- [[7th CAA, 1956]] - Historical reorganization precedents
- [[Polity Definitions]] - Key terminology and concepts

## Reference Materials

### Quick Access
- [[POLITY]] - Mnemonics and memory techniques
- [[FINOLOGY]] - Economic concepts and tricks
- [[G-20 and all]] - International relations updates

### Strategy Notes
- [[STRATEGY FOR MAINS 2026]] - Integrated preparation approach
- Subject-wise time allocation and priority areas
- Current affairs integration strategies

## Interconnected Learning

The beauty of this digital garden lies in how topics connect:

- **Geography ↔ Polity**: Natural disasters → [[Emergency Provisions]] → Constitutional crisis management
- **History ↔ Current Affairs**: Constitutional development → Modern amendments → Contemporary governance
- **Theory ↔ Application**: [[Judiciary]] structure → Recent judgments → Current legal developments

## Recent Updates

{% assign prelims_notes = site.notes | where: "category", "prelims" | sort: "last_modified_at_timestamp" | reverse %}
{% for note in prelims_notes limit: 8 %}
- {{ note.last_modified_at | date: "%Y-%m-%d" }} — [[{{ note.title }}]]
{% endfor %}

---

**Navigation tip**: Start with foundational topics like [[Constitution of India]] and follow the connections. Each note's sidebar shows related notes to explore. 