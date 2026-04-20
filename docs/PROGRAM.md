# LifeAtlas Contributor Program — Full Program Guide

## The Principle

This is not a traditional internship with assigned tasks and a supervisor. This is an **agile contributor program** where the work emerges from what LifeAtlas needs NOW, matched to what YOU can do and want to learn.

The structure flexes every 2 weeks. What matters in Sprint 1 might not matter in Sprint 3. Your track might shift. Your team might change. That's by design — we optimize for impact, not for org charts.

**Duration:** 8 weeks (May 4 — June 27, 2026)
**Format:** Remote. Daily standups. Bi-weekly sprints.
**Source of truth:** What you ship (git, docs, designs, reports). Not what you say you did.

---

## How It Works

### Week 0 (Before May 4): The Screening Challenge

Everyone starts here: **https://github.com/Life-Atlas/lpi-developer-kit**

**Level 1** (everyone): Register. Fork, fill in your profile, submit a PR.
**Level 2+**: Track-specific (see below). Do the one that matches your skills and interests.

Your Level 2/3 submission tells us two things: what you can do, and what you're drawn to. We use that to place you — but placement isn't permanent. It's a starting point.

### Weeks 1-2: Sprint 0 — Orientation + First Delivery

- Meet your team. Meet your team lead (assigned from top screening performers).
- Get your first task from the sprint backlog. Small scope. Ship something real by Friday.
- Daily standups. Camera on. Show what you built. Ask for help.
- End of Week 2: **first retrospective.** What worked? What didn't? What should we do differently?

### Weeks 3-8: Sprints 1-3 (2 weeks each)

Each sprint:
1. **Sprint planning** (Monday, Week 1): Team leads + Nicolas prioritize the backlog. You pick tasks.
2. **Daily standups**: Show progress, surface blockers, help each other.
3. **Mid-sprint check** (Friday, Week 1): Are we on track? Pivot if needed.
4. **Sprint demo** (Friday, Week 2): Each team demos what shipped. Nicolas attends.
5. **Retrospective** (Friday, Week 2): What to improve for next sprint.

**The backlog is alive.** New customer needs, new partner requests, new product priorities — they flow into the backlog every sprint. You're not building to a 6-month-old specification. You're building what matters THIS WEEK.

---

## The Tracks

You pick a track based on your skills and interests. Tracks are not cages — you can move between them, contribute to other tracks, and propose new ones. But every person has a HOME track where they do most of their work.

### Track A: Agent Builders (Technical)
**For:** Students with Python, FastAPI, JavaScript, Docker, or AI/ML experience
**What you build:** AI agents, MCP tools, LangGraph workflows, data pipelines, API integrations
**The screening challenge:** Levels 1-3 from the LPI Developer Kit README (run MCP server, build an agent)

**What LifeAtlas needs from this track:**
- Agents that connect wearable data (Strava, Oura, WHOOP) to the SMILE methodology
- Chat improvements — better context awareness, multi-turn memory, document understanding
- Professional dashboard features — client management, analytics, meeting intelligence
- LPI server extensions — new tools, new knowledge domains, A2A protocol support
- Security hardening — prompt injection defense, input validation, rate limiting
- Voice interface — speech-to-text, voice commands, multilingual support
- Notification system, calendar integration, document management
- Performance optimization — bundle size, query speed, caching

**First sprint examples:**
- Build an agent that maps Strava workout data to SMILE health insights
- Extend the LPI with a new knowledge domain (e.g., longevity/biohacking)
- Write integration tests for existing backend endpoints
- Build a Telegram/WhatsApp bot that answers SMILE questions via the LPI

---

### Track B: Content & Research
**For:** Students who are strong writers, researchers, or analysts — even without coding skills
**What you build:** Case studies, course modules, knowledge base entries, competitive analysis, grant applications

**The screening challenge (Level 2-3 for this track):**
- **Level 2:** Read the SMILE methodology using the LPI Developer Kit. Write a 1-page summary of how SMILE applies to an industry you're interested in (healthcare, manufacturing, energy, agriculture, smart cities — your choice).
- **Level 3:** Find 3 real-world digital twin implementations NOT already in the LPI knowledge base. For each: describe the challenge, the approach, the outcome, and which SMILE phases were applied. Submit as a structured document (Google Docs or markdown).

**What LifeAtlas needs from this track:**
- 12 course modules for "The Future of People: Digital Twins for Life" course
- Transcription and structuring of Nicolas's presentations and recordings
- Exercise design: practical activities, rubrics, and assessments per module
- Deep-dive case studies across industries (buildings, automotive, healthcare, equestrian, energy, maritime)
- Competitor analysis: who else teaches digital twins? What are they missing?
- Grant research: scan Vinnova, Horizon EU, Energimyndigheten, Swedfund for opportunities
- LinkedIn content: draft posts, design graphics, manage content calendar
- Industry vertical reports: one per vertical, publishable quality

**First sprint examples:**
- Transcribe and structure 3 of Nicolas's existing presentation recordings
- Write a case study on a real digital twin implementation in Indian manufacturing
- Draft 5 LinkedIn posts about SMILE methodology for Nicolas's profile
- Research 10 grant opportunities relevant to LifeAtlas in EU/India

---

### Track C: Design & UX
**For:** Students with Figma, Canva, UI/UX, or visual design skills
**What you build:** UI designs, infographics, presentation decks, course visuals, brand materials

**The screening challenge (Level 2-3 for this track):**
- **Level 2:** Run the LPI Developer Kit and read the SMILE methodology output. Sketch (paper, Figma, or Canva) a visual representation of the 6 SMILE phases that a non-technical person could understand in 30 seconds.
- **Level 3:** Design a dashboard mockup for ONE of: (a) a personal health digital twin showing sleep, nutrition, exercise, and stress data, (b) a professional's client management view with health timelines and meeting history, (c) a course platform landing page for "The Future of People: Digital Twins for Life."

**What LifeAtlas needs from this track:**
- Course visuals: infographics, diagrams, architecture illustrations for all 12 modules
- Slide deck templates for investor presentations, customer demos, and conference talks
- UI/UX improvements to the existing LifeAtlas frontend (React — collaboration with Track A)
- Brand assets: social media templates, email templates, document templates
- Data visualization designs for health dashboards, timeline views, knowledge graphs

**First sprint examples:**
- Redesign the SMILE 6-phase diagram as a modern infographic
- Design a mobile-first view of the health timeline
- Create a slide template for Nicolas's investor pitch
- Design the course landing page

---

### Track D: 3D & Visualization
**For:** Students with Unity, Unreal Engine, Godot, Blender, Three.js, or AR/VR experience
**What you build:** 3D digital twin visualizations, spatial interfaces, interactive demos

**The screening challenge (Level 2-3 for this track):**
- **Level 2:** Run the LPI Developer Kit and read about Reality Emulation (Phase 1). Write a short description of what a 3D "Reality Canvas" would look like for one of: a hospital, a horse stable, a smart building, or a human body.
- **Level 3:** Build a simple 3D scene (Unity, Unreal, Godot, Three.js, or Blender render) showing a digital twin concept. Minimal: a 3D model with at least one data overlay (temperature, heart rate, occupancy — whatever fits your concept). Export a video walkthrough or a playable web build.

**What LifeAtlas needs from this track:**
- Interactive 3D visualization of the SMILE phases (for the course)
- A 3D human body model with health data overlays (for the personal view)
- Spatial data visualization (Three.js integration with the existing React frontend)
- AR proof-of-concept: point phone at a building, see its digital twin data overlay
- Demo scenes for investor presentations and conference talks
- EquestRai: 3D horse model with training data visualization

**First sprint examples:**
- Build a Three.js widget showing a 3D building with sensor data hotspots
- Create an Unreal Engine scene of a hospital ward with real-time patient flow visualization
- Design a 3D human body model with clickable organ systems showing health metrics
- Build a Blender animation showing the 6 SMILE phases as a spatial journey

---

### Track E: QA, Security & Testing
**For:** Students interested in cybersecurity, testing, quality assurance, or anyone who likes breaking things
**What you build:** Security audits, test suites, bug reports, vulnerability assessments, documentation fixes

**The screening challenge (Level 2-3 for this track):**
- **Level 2:** Run the LPI Developer Kit. Try to make it fail. Send unexpected inputs. Try queries designed to break the search. Document everything that happens (including things that don't break — that's useful too). Submit a bug report.
- **Level 3:** Write a security audit report (OWASP-style) for the LPI sandbox server. Check for: injection vectors, information disclosure, denial of service, authentication bypass, error handling leaks. Submit as a structured PDF or markdown document. Even finding nothing is valuable if your methodology is sound.

**What LifeAtlas needs from this track:**
- Security audit of the full backend (FastAPI, Supabase, Neo4j connections)
- Penetration testing of the frontend (XSS, CSRF, auth bypass)
- Test suite expansion (currently 1,125 tests — need more edge cases)
- Prompt injection testing against the AI chat system
- GDPR compliance audit (data export, deletion, consent management)
- Accessibility testing (WCAG 2.2 AA compliance)
- Performance testing (load tests, stress tests, latency profiling)
- Documentation QA — find and fix errors in all READMEs, guides, and docs

**First sprint examples:**
- Run OWASP ZAP against the LifeAtlas staging environment
- Write 50 edge-case tests for the backend chat endpoint
- Audit the Supabase RLS policies for data leakage
- Test the LPI server with adversarial inputs and document findings

---

## How Tasks Get Assigned

**We don't assign tasks. We maintain a backlog. You pick from it.**

The backlog is a GitHub Project board (or a shared document — whatever works). It contains:

1. **Product needs** — features, fixes, and improvements the platform needs right now
2. **Customer needs** — specific things partners and customers have asked for
3. **Research needs** — knowledge gaps, competitive intelligence, market analysis
4. **Content needs** — course modules, blog posts, social media, presentations
5. **Quality needs** — bugs to fix, tests to write, security holes to close

Each task has:
- A clear description of WHAT is needed (not HOW to do it — that's your job)
- A priority: Must / Should / Could
- An estimated size: Small (hours) / Medium (days) / Large (sprint)
- Which track it belongs to (some tasks span tracks)

**You pick tasks based on:**
1. What the team needs most (priority)
2. What matches your skills
3. What you want to learn

**Nobody waits to be told what to do.** If the backlog is empty for your track (it won't be), find something to improve and propose it.

---

## The Agile Cadence

```
Every day:      Standup (15 min, camera on, show your work)
Every Friday:   Demo (what shipped this week) + Learning (industry updates)
Every 2 weeks:  Sprint planning → Sprint → Demo → Retrospective
Every month:    Nicolas reviews progress, adjusts priorities, recognizes top performers
```

**What changes between sprints:**
- Priorities shift based on customer conversations, partner requests, and product decisions
- People move between tracks if needed (a designer might help with content; a coder might help with security)
- New tasks appear that nobody predicted (a new partnership, a new grant deadline, a customer request)
- Old tasks get deprioritized (something we thought mattered turns out not to)

**This is normal. This is how software companies work.** The ability to adapt to changing priorities is a skill you'll use your entire career.

---

## IP and Ownership

**Code contributed to LifeAtlas repos (PRs merged into our repositories):** Owned by WINNIIO AB. Licensed MIT — open source, but we control the repo.

**Code in your personal repos (Level 3 agents, tools, experiments):** Yours. MIT licensed. We can use it, you can use it, anyone can use it. It's on YOUR GitHub, YOUR portfolio.

**Content, research, and designs produced during the program:** Work product of the internship, owned by WINNIIO AB. You retain the right to reference it in your portfolio and use it for academic credit.

**Knowledge base contributions merged into the LPI:** Part of the open-source LPI ecosystem. MIT licensed. You're credited as a contributor.

**This follows the Linux model:** Linus doesn't own your code. The Linux Foundation maintains the project. Contributors are credited. The code is free for everyone. But the project direction is controlled by the maintainers.

---

## What You Get

- Published open-source contributions on your GitHub
- Real product development experience (not toy projects)
- Skills in MCP, AI agents, LangGraph, explainable AI, edge computing, security — whatever your track covers
- Weekly exposure to industry-current developments
- A letter of recommendation based on your actual contributions (not attendance)
- Internship completion certificate for academic credit
- A network: your cohort of 100 contributors + the LifeAtlas team + our partners

## What We Expect

- Show up. Camera on. Daily standups. On time.
- Ship something every sprint. Small is fine. Nothing is not.
- Ask for help when stuck. Help others when you can.
- Own your work. Your name on every commit, every document, every design.
- Adapt. Priorities change. That's the job.

---

## Team Leads

After Week 1, the top performers from the screening challenge become **team leads**. Team leads:
- Run their team's daily standup
- Help team members get unblocked
- Review work before it goes to the sprint demo
- Write a weekly 1-paragraph update for Nicolas
- Are the first point of contact for their team (not Nicolas, not Christalyn)

Team leads are selected based on screening performance + communication quality. They can be rotated if someone else emerges as a stronger leader. This is earned, not permanent.

---

## For Amity University / Academic Supervisors

This program produces:
- Weekly documented deliverables per student (visible in GitHub/shared docs)
- Bi-weekly sprint demos (recorded)
- Individual contribution reports at program end
- Completion certificates signed by WINNIIO AB CEO
- Letters of recommendation for top performers

Students work on a real product used by real customers. Their contributions are visible, versioned, and attributable. Academic supervisors can track progress via the public leaderboard and the private contribution reports.
