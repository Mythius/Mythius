# Matthias Southwick — Portfolio Brief for Claude Code
> This is the complete content + architecture spec. Build msouthwick.com from this.

---

## Identity

**Name:** Matthias Southwick  
**Title:** Full-Stack Software Engineer  
**Tagline:** *"Build once. Deploy everywhere. Keep it simple."*  
**Location:** Provo, Utah  
**Email:** southwickmatthias@gmail.com  
**Phone:** (801) 615-4831  
**GitHub:** https://github.com/Mythius  
**Resume:** https://msouthwick.com/Matthias-Southwick-Resume.pdf  

---

## Core Values — Display Prominently (Not Buried in About)

These should appear as a dedicated "Philosophy" or "How I Build" section with icons, not filler text.

| # | Value | One-liner |
|---|---|---|
| 1 | **Free & Open Source First** | Prefer free APIs and self-hostable tools over paid lock-in |
| 2 | **Self-Host When It Makes Sense** | Own your stack, own your data |
| 3 | **Code Once, Reuse Everywhere** | Boilerplates, libs, and pipelines — write it right the first time |
| 4 | **Simplicity Is the UX** | If you need training, the design failed |
| 5 | **Security Without Friction** | OAuth over passwords, public/private endpoint separation always |
| 6 | **High-Quality Data** | Clean schemas, clean migrations, accessible but never messy |
| 7 | **AI as a Multiplier** | Claude Code to iterate fast; AI amplifies craft, doesn't replace it |
| 8 | **Data-Informed, Not Data-Driven** | Data surfaces truth — people make decisions. Dashboards should empower judgment, not replace it |

---

## Projects Data

Each project card must display: title, description, tags (chips), GitHub link, live link, and category badge.

---

### CATEGORY: Platforms & SaaS

---

**Admishn — Admissions CRM**
- **Description:** Web platform for schools to manage student applications end-to-end, with real-time student progress tracking, built-in mail merge, and automated email workflows. Sold to Davis School District.
- **Live:** https://admishn.com
- **GitHub:** (private — note as "Commercial")
- **Tags:** `SaaS` `CRM` `Mail Merge` `Automated Emails` `PostgreSQL` `Node.js` `React` `Co-Founded`
- **Highlight badge:** ⭐ Sold to Davis School District

---

**MatthiasTV — Self-Hosted Video Streaming**
- **Description:** Full self-hosted media streaming platform with browser playback, a native Roku TV app (BrightScript), and a cross-platform Electron desktop app. Uses FFmpeg for video transcoding. No subscription fees, no third-party services.
- **GitHub:** https://github.com/Mythius/videostream
- **Tags:** `Self-Hosted` `Open Source` `FFmpeg` `Roku` `BrightScript` `Electron` `Node.js` `Video Streaming` `Cross-Platform` `Docker`
- **Repo stats:** 2 ⭐ · 1 fork · 144 commits · v1.0 released Nov 2025

---

**Mentors Global Reports Dashboard**
- **Description:** Professional reporting and data visibility platform with a Google Docs–style editing experience and role-based permissions. Used across departments in multiple countries at Mentors International.
- **Live:** https://reports.mentorsglobal.org
- **GitHub:** (private — Mentors International)
- **Tags:** `Professional` `Dashboards` `Permissions` `React` `Node.js` `PostgreSQL` `AWS` `Docker` `NGINX`
- **Highlight badge:** ⭐ Production system · Multi-country deployment

---

**PixelAI — Image Processing & AI Studio**
- **Description:** Unified platform for image processing, AI model training, and AI image generation. Demonstrates the complete pipeline from raw input through model training to generated output.
- **Live:** https://pixelai.msouthwick.com
- **Tags:** `AI` `Image Processing` `Model Training` `Image Generation` `Canvas API` `JavaScript` `Self-Hosted`

---

### CATEGORY: Developer Tools & Infrastructure

---

**api-lib — Express API Boilerplate**
- **Description:** Opinionated Express boilerplate that enforces separation of public vs. private endpoints with Google and Microsoft OAuth baked in from the start. Every API built on top of it is secure by default — no password management, no account complexity.
- **GitHub:** https://github.com/Mythius/api-lib
- **Tags:** `Open Source` `Boilerplate` `Express` `OAuth` `Google Auth` `Microsoft Auth` `Node.js` `TypeScript` `Security` `Reusable`
- **Repo stats:** 1 ⭐ · 1 fork · Active (updated today)
- **Philosophy badge:** "Code Once, Reuse Everywhere"

---

**Online Explorer — Self-Hosted File Manager**
- **Description:** Self-hosted file explorer web app. Browse, preview (images, video, audio, PDFs, code), and download files from any server directory. Google/Microsoft OAuth with per-user access control, email-based access requests, and optional auth bypass for internal networks.
- **GitHub:** https://github.com/Mythius/online-explorer
- **Tags:** `Self-Hosted` `Open Source` `File Sharing` `Google Auth` `Microsoft Auth` `OAuth` `Node.js` `Access Control` `ZIP Download` `Mobile-Friendly`
- **Auth modes:** No auth / Google+Microsoft direct OAuth / CAS server delegation

---

**TemplateWebsites — Google Sheets CMS**
- **Description:** Deploy and manage live websites entirely from a Google Sheet. A shell script provisions a new NGINX site, and content syncs automatically from Google Drive. Currently powers four live sites — all content-managed without touching code.
- **GitHub:** https://github.com/Mythius/TemplateWebsites
- **Live examples:** https://profile.msouthwick.com · https://rocks.msouthwick.com · https://zack.msouthwick.com · https://art.msouthwick.com
- **Tags:** `Google Sheets` `Google Drive` `Apps Script` `CMS` `NGINX` `Shell` `Raspberry Pi` `Self-Hosted` `No-Code Frontend` `Server-Side Rendering`
- **Philosophy badge:** "Simplicity Is the UX" + "Free APIs First"

---

**CI/CD Pipeline Templates**
- **Description:** GitHub Actions pipelines for deploying containerized apps to AWS Fargate, ECS, and local Linux servers. Reusable across projects, battle-tested in production.
- **Tags:** `GitHub Actions` `AWS Fargate` `ECS` `Docker` `NGINX` `Linux` `DevOps` `CI/CD` `Reusable`
- **Philosophy badge:** "Code Once, Reuse Everywhere"

---

**Google Slides PDF Certificate Generator** *(Mentors International)*
- **Description:** Uses the Google Slides API to programmatically generate and export personalized PDF certificates at scale. Zero manual design work per certificate.
- **Tags:** `Google Slides API` `PDF Generation` `Automation` `JavaScript` `Google APIs`

---

**Database Design & Migration** *(Mentors International)*
- **Description:** Designed the schema for a major production system overhaul and led migration from a legacy database. Emphasis on clean data architecture and zero data loss.
- **Tags:** `PostgreSQL` `Database Design` `Data Migration` `SQL` `AWS`
- **Philosophy badge:** "High-Quality Data"

---

### CATEGORY: Web Apps & Utilities

---

**Family Registry**
- **Description:** Private family app where any family member signs in with Google to access a shared family tree and contact book. Designed to need zero explanation — you log in, it works.
- **Live:** https://family.msouthwick.com
- **Tags:** `Google Auth` `Family Tree` `Contact Book` `Private App` `Node.js` `Self-Hosted`
- **Philosophy badge:** "Simplicity Is the UX"

---

### CATEGORY: Games & Creative

---

**Chess + Minimax Bot**
- **Description:** Fully playable chess in the browser with complete rules, checkmate puzzles, and a bot built from scratch using the minimax algorithm searching 4 moves deep. The engine is written in C++ and served via Node.js.
- **Live:** https://www.msouthwick.com/chess/
- **GitHub:** https://github.com/Mythius/Chess
- **Tags:** `Chess` `C++` `Minimax Algorithm` `Game AI` `Node.js` `JavaScript` `HTML5` `Puzzles`
- **Tech breakdown:** JavaScript 67.3% · C++ 29.2% · HTML 3.1%
- **Highlight badge:** ⭐ Hand-rolled AI engine in C++ — rare for a web developer

---

**Multiplayer Game Suite**
- **Description:** Real-time multiplayer games using WebSockets for game state sync and room management. All playable on msouthwick.com.
- **Live:** https://msouthwick.com (Games section)
- **Includes:** Enchanted Forest · Bananagrams · Checkers · Blokus · Asteroids
- **GitHub repos:** https://github.com/Mythius/Enchanted-Forest · https://github.com/Mythius/bananagrams · https://github.com/Mythias/checkers · https://github.com/Mythius/Blockus · https://github.com/Mythius/Asteroids
- **Live:** https://www.msouthwick.com/ef/
- **Tags:** `WebSockets` `Multiplayer` `Real-Time` `Game Dev` `JavaScript` `Node.js` `Room Management`

---

**ASCII Camera**
- **Description:** Live webcam feed rendered as real-time ASCII art in the browser via canvas pixel manipulation.
- **GitHub:** https://github.com/Mythius/asciicamera
- **Tags:** `Canvas API` `Image Processing` `JavaScript` `HTML5` `Creative`

---

**JS Animation Engine**
- **Description:** Lightweight animation-making software for HTML5 Canvas. Reusable library used across game and creative projects.
- **GitHub:** https://github.com/Mythius/Animations
- **Tags:** `Canvas API` `Animation` `Library` `JavaScript` `Reusable`

---

### CATEGORY: Hardware & IoT

---

**Raspberry Pi Robotics**
- **Description:** Integrated web software with Raspberry Pi hardware for robotics projects. Bridges server-side code with physical computing.
- **Tags:** `Raspberry Pi` `Robotics` `IoT` `Hardware` `Python` `Self-Hosted`

---

**Amazon Alexa Integration**
- **Description:** Built Alexa skills for voice-controlled IoT devices and home automation.
- **Tags:** `Alexa` `IoT` `Voice Interface` `AWS Lambda` `AWS`

---

## Professional Experience

| Period | Role | Organization | Notes |
|---|---|---|---|
| Apr 2025–Present | Co-Founder & Software Engineer | Admishn Software | Sold to Davis School District |
| Jan 2024–Present | Software Engineer | Mentors International | 8+ full-stack tools, AWS, production Linux |
| Apr 2023–Jan 2024 | Data Analyst | Weber State University | Advanced SQL, Tableau, open-source data viz |
| Aug 2024–Apr 2026 | B.S. Computer Science | Brigham Young University | Current student |
| Jan 2022–Apr 2024 | A.S. Computer Science | Weber State University | Graduated |

**Key professional callouts:**
- Manages production Linux servers + AWS infrastructure (Fargate, ECS, Docker, NGINX)
- Designed and migrated a production database for a large multi-country system
- Set up SCRUM/Agile on a remote international team (bilingual English/Spanish)
- Sold software commercially as a co-founder

---

## Skills

| Group | Skills |
|---|---|
| **Languages** | JavaScript · TypeScript · SQL · Python · Java · C++ |
| **Frontend** | React · HTML · CSS · Canvas API |
| **Backend** | Node.js · Express · Prisma · FFmpeg |
| **Databases** | PostgreSQL · MySQL · Oracle DB · MongoDB · AWS DynamoDB |
| **Cloud / DevOps** | AWS (Fargate · ECS · Lambda · SQS · API Gateway) · Docker · NGINX · Linux |
| **Integrations** | Google Drive API · Google Slides API · Google Sheets / Apps Script · Microsoft Auth · Amazon Alexa |
| **Tools** | Git · GitHub Actions · Claude Code · Tableau |

---

## Site Architecture for Claude Code

### Page Structure (single page, anchor nav)
1. **Hero** — Name, title, tagline, CTA buttons (View Projects / GitHub / Resume)
2. **Philosophy** — 8 value cards with icons and one-liner descriptions
3. **Projects** — Filterable card grid (filter by category and/or tag)
4. **Experience** — Timeline (professional + education combined)
5. **Skills** — Grouped visual chips by category
6. **Contact** — Email, GitHub, Resume download

### Project Card Design Spec
Each card must include:
- Project title
- One-sentence description
- **Tag chips** — clickable, trigger filter
- GitHub icon link (if public) and Globe icon link (if live URL exists)
- Category badge (top corner): `Platform` / `Dev Tool` / `Web App` / `Game` / `IoT`
- Featured projects (Admishn, MatthiasTV, Chess, api-lib, Online Explorer) get slightly larger or highlighted card treatment

### Tag Filter System
- Top-level category buttons: All · Platforms · Dev Tools · Games · IoT · Web Apps
- Clicking any tag chip on a card also filters the grid to matching projects
- Tags should be clickable anywhere they appear

### Project Data as JSON
Structure all project data as a JSON array at the top of the file for easy editing. Example entry:

```json
{
  "id": "videostream",
  "title": "MatthiasTV",
  "description": "Self-hosted video streaming with browser, Roku TV app, and Electron desktop app.",
  "category": "platform",
  "tags": ["Self-Hosted", "FFmpeg", "Roku", "Electron", "Node.js", "Open Source"],
  "github": "https://github.com/Mythius/videostream",
  "live": null,
  "featured": true,
  "highlight": "2 ⭐ · v1.0 released Nov 2025"
}
```

### Design Direction
- **Dark mode by default** — dark navy/charcoal base, bright teal or electric blue accent, white text
- Monospace font accents for tags, code references, and section labels
- Fast, minimal, no bloat — the site itself demonstrates the values
- No heavy animations — subtle hover states only
- Mobile responsive

### Tech Stack Recommendation
- Single-file HTML/CSS/JS or React — keep it self-hostable with no build pipeline required
- Deploy to existing msouthwick.com NGINX server on Linux
- Project data as an editable JSON block — easy to later wire up to the Google Sheets CMS

---

## Notes for Claude Code

- Surface "Sold to Davis School District" early — it's the single strongest credibility signal (it is pending right now though)
- The Chess C++ bot deserves a "wait, C++?" moment — most web devs never go near it
- The Online Explorer is a great quiet flex: built because he wanted it, not for a class
- The TemplateWebsites / Google Sheets CMS is a meta-story worth a callout: "I manage my own sites with my own tools"
- The data-informed value pairs directly with the dashboard and analytics work — mention it in that context
- Consider a subtle footer line: "Built and self-hosted by its owner" — nod to the philosophy
- The philosophy section should feel like genuine convictions, not a buzzword list
