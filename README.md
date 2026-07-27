# Awesome-Abstract-Conference-Management

![Banner](assets/banner.svg)

<div align="center">
<a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a><a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
<a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</div>

**Abstract & Conference Management** platforms are essential for organizing academic and professional events. They handle call for papers (CfP), abstract/paper submissions, peer review processes, reviewer assignment & bidding, acceptance decisions, scheduling, registration, and often proceedings publishing. Finding the best conference management software is crucial for event success. Popular commercial tools include Ex Ordo, OpenWater, Oxford Abstracts, ConfTool, EasyChair, Whova, Cadmium, Fourwaves, ExhibitDay, and Sessionize.

Below is a **curated list** of notable platforms and their open-source equivalents. The focus is on **open-source** solutions that can be self-hosted for full data ownership and zero licensing fees.

## 🏢 SaaS / Hosted Platforms ☁️

| Platform | Description | Pricing | Free Tier Limit |
| :--- | :--- | :--- | :--- |
| **[Ex Ordo](https://www.exordo.com/)** | Comprehensive academic conference platform with strong abstract management, multi-track support, peer review, registration, and virtual/hybrid features. | Quote-based pricing | N/A |
| **[OpenWater](https://www.getopenwater.com/)** | Abstract management, awards, grants, and conference workflows with customizable forms and review processes. | Quote-based pricing | N/A |
| **[Oxford Abstracts](https://www.oxfordabstracts.com/)** | Dedicated academic abstract and conference management with strong peer-review tools, and website builder. | Transparent per-event pricing | Free tier for small events |
| **[ConfTool](https://www.conftool.net/)** | Highly configurable European conference system supporting abstract submission, review, registration, and program creation. | Pro version is paid | Free Standard edition for non-commercial, small events (up to 150 participants) |
| **[EasyChair](https://easychair.org/)** | Widely used (especially in computer science) for paper submission, bidding, assignment, and review. | Per-submission pricing | Free tier available for small events |
| **[Whova](https://whova.com/)** | All-in-one conference app with abstract management, attendee engagement, agenda builder, and networking features. | Quote-based pricing | N/A |
| **[CadmiumCD / X-CD](https://www.x-cd.com/)** | Abstract collection, peer review, program scheduling, and speaker management used by hundreds of conferences. | Quote-based pricing | N/A |
| **[Fourwaves](https://fourwaves.com/)** | Modern platform for scientific events with abstract submission, peer review, registration, and poster sessions. | Paid tiers | Free plan available (up to 100 participants) |
| **[ExhibitDay](https://www.exhibitday.com/)** | Focused on exhibition and conference scheduling with abstract and session management. | Paid tiers | Free Lite tier available |
| **[Sessionize](https://sessionize.com/)** | Speaker and session management platform popular for tech conferences; handles Call for Speakers, reviews, and agenda building. | Free for community events | Free for community/non-commercial events |
| **[OpenConf](https://www.openconf.com/)** | Mature peer-review and abstract management system (self-hosted or hosted). Proprietary but installable on your own server. | Paid editions | N/A |
| **[Microsoft CMT](https://cmt3.research.microsoft.com/)** | Conference Management Toolkit by Microsoft Research. Excellent for large CS conferences; submission + review focused. | Free for academic use | Free for academic use |

## 🔓 Open-Source Software 💻

### 🌟 Full-Featured Conference Management
- **[Indico](https://github.com/indico/indico)** [![Stars](https://img.shields.io/github/stars/indico/indico?style=social&color=white)](https://github.com/indico/indico/stargazers) — Feature-rich event management system developed at CERN. Supports Call for Abstracts, abstract reviewing, paper reviewing, registration, payments, drag-and-drop timetable, room booking, badges, and more. MIT license. Extremely mature and used worldwide.
- **[pretalx](https://github.com/pretalx/pretalx)** [![Stars](https://img.shields.io/github/stars/pretalx/pretalx?style=social&color=white)](https://github.com/pretalx/pretalx/stargazers) — Modern, web-based tool focused on Call for Papers, reviewing, speaker communication, and scheduling. Highly customizable via plugins. Apache-2.0. Popular with FOSS and tech conferences (PyCon, FOSDEM, JuliaCon, etc.).
- **[frab](https://github.com/frab/frab)** [![Stars](https://img.shields.io/github/stars/frab/frab?style=social&color=white)](https://github.com/frab/frab/stargazers) — Web-based conference planning system originally built for FrOSCon. Handles submissions, speaker management, review/rating, conflict-aware drag-and-drop scheduling, and multi-format exports. Used by Chaos Communication Congress and many others.
- **[OSEM](https://github.com/openSUSE/osem)** [![Stars](https://img.shields.io/github/stars/openSUSE/osem?style=social&color=white)](https://github.com/openSUSE/osem/stargazers) — Event management tailored to free/open-source software conferences. Includes CfP, registration, scheduling, and more. MIT license. Ruby on Rails.
- **[Leconfe](https://github.com/leconfe/leconfe)** [![Stars](https://img.shields.io/github/stars/leconfe/leconfe?style=social&color=white)](https://github.com/leconfe/leconfe/stargazers) — Integrated academic conference platform covering registration, abstract/paper submission, peer review, payments, and proceedings publishing. Inspired by Open Journal Systems. GPL-3.0. Actively maintained with Docker support.

### 📝 CfP, Review & Peer-Review Focused
- **[OpenReview](https://github.com/openreview)** [![Stars](https://img.shields.io/github/stars/openreview/openreview?style=social&color=white)](https://github.com/openreview/openreview/stargazers) — Platform promoting open peer review (used by many ML/AI conferences). Core components (web interface, Python client, matcher, etc.) are open source. Supports configurable openness policies.
- **[Conference Hall](https://github.com/conference-hall/conference-hall)** [![Stars](https://img.shields.io/github/stars/conference-hall/conference-hall?style=social&color=white)](https://github.com/conference-hall/conference-hall/stargazers) — Open SaaS-style platform for managing Calls for Papers. Speakers can write talks once and submit to multiple events. Review workflows, team management, and speaker notifications.
- **[SlickChair](https://github.com/SlickChair/SlickChair)** [![Stars](https://img.shields.io/github/stars/SlickChair/SlickChair?style=social&color=white)](https://github.com/SlickChair/SlickChair/stargazers) — Flexible peer-review system written in Scala (Play + Slick). Supports customizable multi-phase workflows (submission → bidding → assignment → review → notification). Full data ownership when self-hosted.

### 🏛️ Legacy / Specialized
- **[Open Conference Systems (OCS)](https://github.com/pkp/ocs)** [![Stars](https://img.shields.io/github/stars/pkp/ocs?style=social&color=white)](https://github.com/pkp/ocs/stargazers) — Classic full-lifecycle conference system from the Public Knowledge Project (same team as OJS). Includes submissions, multi-stage review, scheduling, and proceedings. **No longer actively maintained** — use at your own risk or as a starting point.
- **[pulipulichen/ocs](https://github.com/pulipulichen/ocs)** [![Stars](https://img.shields.io/github/stars/pulipulichen/ocs?style=social&color=white)](https://github.com/pulipulichen/ocs/stargazers) — Community fork/modernization of OCS with registration, paper submission, and review features (PHP + Bootstrap).

### 🔍 Smaller / Niche Projects
- **[insum-labs/conference-manager](https://github.com/insum-labs/conference-manager)** [![Stars](https://img.shields.io/github/stars/insum-labs/conference-manager?style=social&color=white)](https://github.com/insum-labs/conference-manager/stargazers) — Oracle APEX-based abstract voting and content selection apps (Admin/Review + Voting).
- **[chstem/Boa](https://github.com/chstem/Boa)** [![Stars](https://img.shields.io/github/stars/chstem/Boa?style=social&color=white)](https://github.com/chstem/Boa/stargazers) — Lightweight Python tool for conference registration + abstract submission that generates Book of Abstracts (PDF + HTML).
- **[daniaki/ABACBSAbsSS](https://github.com/daniaki/ABACBSAbsSS)** [![Stars](https://img.shields.io/github/stars/daniaki/ABACBSAbsSS?style=social&color=white)](https://github.com/daniaki/ABACBSAbsSS/stargazers) — Django-based abstract submission and review web application with role-based access (author, reviewer, assigner, chair).

---

**How to contribute**  
Fork this repository, add a new project (with link + short description + category), and open a pull request.  
Prefer actively maintained open-source projects that support abstract submission and peer review.

**License**  
This list is public domain / CC0. Feel free to copy into your own awesome list or README.

Star the projects you find useful — the open-source conference tooling ecosystem continues to grow! 🎓


##  Star History
<div align="center">
<a href="https://www.star-history.com/?repos=ishandutta2007%2FAwesome-Abstract-Conference-Management&type=date&legend=bottom-right">
<picture>
<source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-Abstract-Conference-Management&type=date&theme=dark&legend=bottom-right" />
<source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-Abstract-Conference-Management&type=date&legend=bottom-right" />
<img alt="Star History Chart" src="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-Abstract-Conference-Management&type=date&legend=bottom-right" />
</picture>
</a>
</div>
