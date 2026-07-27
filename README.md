# Awesome-Abstract-Conference-Management

**Abstract & Conference Management** platforms handle call for papers (CfP), abstract/paper submissions, peer review, reviewer assignment & bidding, acceptance decisions, scheduling, registration, and often proceedings publishing. Popular commercial tools include Ex Ordo, OpenWater, Oxford Abstracts, ConfTool, EasyChair, Whova, Cadmium, Fourwaves, ExhibitDay, and Sessionize.

Below is a **curated list** of notable platforms and their open-source equivalents. The focus is on **open-source** solutions that can be self-hosted for full data ownership and zero licensing fees.

## 🏢 SaaS / Hosted Platforms

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

## 🔓 Open-Source Software

### Full-Featured Conference Management
- **[Indico](https://github.com/indico/indico)** — Feature-rich event management system developed at CERN. Supports Call for Abstracts, abstract reviewing, paper reviewing, registration, payments, drag-and-drop timetable, room booking, badges, and more. MIT license. Extremely mature and used worldwide.
- **[pretalx](https://github.com/pretalx/pretalx)** — Modern, web-based tool focused on Call for Papers, reviewing, speaker communication, and scheduling. Highly customizable via plugins. Apache-2.0. Popular with FOSS and tech conferences (PyCon, FOSDEM, JuliaCon, etc.).
- **[OSEM](https://github.com/openSUSE/osem)** — Event management tailored to free/open-source software conferences. Includes CfP, registration, scheduling, and more. MIT license. Ruby on Rails.
- **[frab](https://github.com/frab/frab)** — Web-based conference planning system originally built for FrOSCon. Handles submissions, speaker management, review/rating, conflict-aware drag-and-drop scheduling, and multi-format exports. Used by Chaos Communication Congress and many others.
- **[Leconfe](https://github.com/leconfe/leconfe)** — Integrated academic conference platform covering registration, abstract/paper submission, peer review, payments, and proceedings publishing. Inspired by Open Journal Systems. GPL-3.0. Actively maintained with Docker support.

### CfP, Review & Peer-Review Focused
- **[Conference Hall](https://github.com/conference-hall/conference-hall)** — Open SaaS-style platform for managing Calls for Papers. Speakers can write talks once and submit to multiple events. Review workflows, team management, and speaker notifications.
- **[SlickChair](https://github.com/SlickChair/SlickChair)** — Flexible peer-review system written in Scala (Play + Slick). Supports customizable multi-phase workflows (submission → bidding → assignment → review → notification). Full data ownership when self-hosted.
- **[OpenReview](https://github.com/openreview)** — Platform promoting open peer review (used by many ML/AI conferences). Core components (web interface, Python client, matcher, etc.) are open source. Supports configurable openness policies.

### Legacy / Specialized
- **[Open Conference Systems (OCS)](https://github.com/pkp/ocs)** — Classic full-lifecycle conference system from the Public Knowledge Project (same team as OJS). Includes submissions, multi-stage review, scheduling, and proceedings. **No longer actively maintained** — use at your own risk or as a starting point.
- **[pulipulichen/ocs](https://github.com/pulipulichen/ocs)** — Community fork/modernization of OCS with registration, paper submission, and review features (PHP + Bootstrap).

### Smaller / Niche Projects
- **[insum-labs/conference-manager](https://github.com/insum-labs/conference-manager)** — Oracle APEX-based abstract voting and content selection apps (Admin/Review + Voting).
- **[chstem/Boa](https://github.com/chstem/Boa)** — Lightweight Python tool for conference registration + abstract submission that generates Book of Abstracts (PDF + HTML).
- **[daniaki/ABACBSAbsSS](https://github.com/daniaki/ABACBSAbsSS)** — Django-based abstract submission and review web application with role-based access (author, reviewer, assigner, chair).

---

**How to contribute**  
Fork this repository, add a new project (with link + short description + category), and open a pull request.  
Prefer actively maintained open-source projects that support abstract submission and peer review.

**License**  
This list is public domain / CC0. Feel free to copy into your own awesome list or README.

Star the projects you find useful — the open-source conference tooling ecosystem continues to grow! 🎓


