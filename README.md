# Hi, I'm Geek Gelasia 👋
code · curiosity · cosmic wonder · humanity · humor

>**The universe is incomprehensibly large. Also, let's configure our CSP correctly.**

Pronounced: `/gi:k/` ` /dʒɛˈleɪziə/`  
Pronouns: she/her

*Geek Gelasia* is a poetic, ironic combination of modern intellectual enthusiasm and classical, lighthearted joy.

I'm an academic artist, emerging developer, and digital sanctuary creator, blending systems logic with human-centered accessibility. Part walking encyclopedia, part hardware tinkerer, and entirely driven by intentional, cross-disciplinary curiosity.

I build small digital things for large questions: digital sanctuaries, interactive art, and thoughtful web experiences exploring the intersections of cosmology, neuroscience, biomechanics, electromagnetism, and philosophical wisdom.

I'm still learning the craft of software development. But questioning defaults, thinking about failure modes, and asking what could go wrong are habits I brought with me.

Around here, you'll find experiments, practical tools, security-conscious web development, philosophical explorations, and occasional excursions into the delightfully strange.

**The work is a work in progress. So am I.**

If something here sparks your curiosity, explore it, challenge it, improve it, or build on it.

![Profile Views](https://komarev.com/ghpvc/?username=gi-k-glacier-0705&color=brightgreen)

---

## About Me

- 🧠 **My practice:** Creative technology, philosophical inquiry, and interdisciplinary research
- 🌌 **My curiosity:** Cosmology, neuroscience, biomechanics, electromagnetism, and the nature of human experience
- 🔐 **My approach:** Security-conscious, systems-minded, and skeptical of assumptions
- ♿ **My values:** Accessibility, human agency, intellectual integrity, and non-coercive exploration
- 🏗️ **My craft:** Dependency-light builds, thoughtful frontends, and meaningful digital experiences
- 🛠️ **My learning:** Building, experimenting, troubleshooting, and learning in public
- 📧 **Email:** [cosmicwonder@duck.com](mailto:cosmicwonder@duck.com)
- 🌐 **Portfolio:** [GeekGelasia.dev](https://geekgelasia.dev/)
- 🧵 **GitLab:** [GiikGelasia](https://gitlab.com/GiikGelasia)

## My Mission

I create digital spaces where wonder meets craft.

I believe the web can be more than utility. It can be a sanctuary for reflection, a tool for inquiry, and a medium for awe.

Technology should make room for curiosity, humanity, and agency—not crowd them out. I’m interested in what becomes possible when accessibility, security, and intellectual honesty are treated as foundational design decisions rather than afterthoughts.

The goal isn't to build the loudest thing on the internet. It's to build things worth spending time with.

## Featured Work

### [cosmic-wonder](https://github.com/gi-k-glacier-0705/cosmic-wonder)

A living experiment in cosmic curiosity, designed as a digital sanctuary for thought, play, and exploration.

### [Orrery Chord](https://keplers-chord.geekgelasia.dev/)

A visual exploration of scale, motion, and perspective inspired by Kepler’s Laws of Planetary Motion.

### Interactive Artifacts

Digital experiments exploring classical philosophy—including Epictetus's *Enchiridion*—alongside modern web architecture, scientific ideas, and expressive interaction design.

More experiments are taking shape. Curiosity tends to generate its own backlog.

## Toolkit

### Frontend

- HTML
- CSS
- JavaScript
- React
- Tailwind CSS

### Infrastructure & Security

- Cloudflare Pages
- GitHub and GitLab
- Zero Trust access patterns
- Web Application Firewall (WAF) configuration
- Security-conscious deployment and configuration

### Creative Practice

- Zenga-inspired abstract aesthetics
- Sumi-e ink wash illustration
- Interactive audiovisual experimentation
- Minimal, contemplative design systems
- Human-centered and accessible interface design

## What I Build

- Small, thoughtful digital experiences
- Interactive explorations of science and philosophy
- Experiments in aesthetics, attention, and meaning
- Digital sanctuaries designed for reflection and discovery
- Web interfaces that feel calm, poetic, and intelligent
- Practical tools built with curiosity and care

## Current Focus

- Building contemplative digital experiences
- Exploring the interface between science, myth, and cognition
- Developing security-conscious, accessible web projects
- Designing minimal but evocative digital artifacts
- Learning deeper ways to blend artistry, systems thinking, and human meaning
- Exploring how technology can support curiosity without compromising human agency

## The Digital Philosophy

Curiosity deserves room to breathe.

Good tools should help people explore, understand, and create—not manipulate them into staying.

I'm interested in building a web that respects the people who use it: accessible by design, thoughtful about privacy, honest about its limitations, and open to intellectual play.

Sometimes that means contemplating the cosmos. Sometimes it means checking the Content Security Policy.

Often, it's both.

## Connect

- 🌐 **Portfolio:** [GeekGelasia.dev](https://geekgelasia.dev/)
- 🐙 **GitHub:** [@gi-k-glacier-0705](https://github.com/gi-k-glacier-0705)
- 🧵 **GitLab:** [GiikGelasia](https://gitlab.com/GiikGelasia)
- ✉️ **Email:** [cosmicwonder@duck.com](mailto:cosmicwonder@duck.com)

---

## A Little Infrastructure, Because Security Matters

```mermaid
%%{init: {'themeVariables': { 'fontSize': '16px', 'fontFamily': 'sans-serif'}}}%%
graph LR
    %% Define Custom Colors
    classDef visitor fill:#9b59b6,color:#fff,stroke:#fff,stroke-width:2px
    classDef cloudflare fill:#f38020,color:#fff,stroke:#fff,stroke-width:2px
    classDef secure fill:#2ecc71,color:#fff,stroke:#fff,stroke-width:2px
    classDef blocked fill:#e74c3c,color:#fff,stroke:#fff,stroke-width:2px
    classDef git fill:#34495e,color:#fff,stroke:#fff,stroke-width:2px

    %% Flowchart Nodes
    Visitor([Web Visitor]):::visitor --> DNS["DNS Routing"]:::cloudflare
    
    DNS --> WAF{"WAF Rule"}:::cloudflare
    WAF -->|Blocked| Drop((Dropped)):::blocked
    WAF -->|Clean| Router{"Subdomain"}:::cloudflare
    
    Router -->|Main| MainSite["Pages: Prod"]:::secure
    Router -->|Custom| ZT{"Zero Trust"}:::cloudflare
    
    ZT -->|Failed| Deny((Denied)):::blocked
    ZT -->|Auth'd| ProtectedApp["Pages: Restricted"]:::secure
    
    Dev([Local Dev]):::git --> Git["Git Repo"]:::git
    Git -->|Commit| CI["Build Pipeline"]:::cloudflare
    CI -.->|Deploy| MainSite
    CI -.->|Deploy| ProtectedApp
```
![Cloudflare Pages](https://img.shields.io/badge/Hosted_on-Cloudflare_Pages-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)
![Zero Trust](https://img.shields.io/badge/Security-Zero_Trust-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)

---

*If any of this confused you → go read* [*The Creative Act*](https://www.penguinrandomhouse.com/books/717409/the-creative-act-by-rick-rubin/) *by Rick Rubin.*
