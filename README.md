# Internship Tenure: Musfira Sehar

An interactive, single-file record of my internship as **Trainee IT Programmer Analyst I** on Stewart's AI Team and R&D projects (13 July – 12 October 2026), combining a one-page summary with a searchable log of every daily and biweekly update.

![Format](https://img.shields.io/badge/Format-Single%20HTML%20File-E34F26?logo=html5&logoColor=white)
![Styling](https://img.shields.io/badge/Styling-CSS3%20Custom%20Properties-1572B6?logo=css&logoColor=white)
![Scripting](https://img.shields.io/badge/Scripting-Vanilla%20JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Dependencies](https://img.shields.io/badge/Dependencies-None-brightgreen)
![Themes](https://img.shields.io/badge/Themes-Light%20%2F%20Dark-0f1c42)
![Log](https://img.shields.io/badge/Work%20Log-63%20Entries-c49a2c)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

---

## 🌐 Overview

The page tells the story of a three-month internship in two layers. The **summary** gives the headline view: the Recognition Spotlight for the AI Models Openness Report, the key projects, research and evaluation, skills and impact. The **work log** underneath holds the full record, word for word: 47 daily updates, 4 biweekly updates and 12 research notes and updates, from 15 July to 6 October 2026. Every summary card links down to the log entries that back it up, so a reader can move from a one-line claim to the day-by-day evidence in one click. Everything (styles, scripts and the certificate image) lives in one HTML file, so it opens in any browser with no build step and no install.

---

## 📍 Quick Navigation

* [🌐 Overview](#-overview)
* [📦 Page Architecture](#-page-architecture)
* [✨ Key Features](#-key-features)
* [📑 Page Sections](#-page-sections)
* [📁 Repository Structure](#-repository-structure)
* [🧰 Tech Stack](#-tech-stack)
* [💻 System Requirements](#-system-requirements)
* [🚀 Viewing Guide](#-viewing-guide)
* [🎮 Keyboard Controls](#-keyboard-controls)
* [📊 Interactive Interfaces](#-interactive-interfaces)
* [🧱 Design Highlights](#-design-highlights)
* [📄 License & Terms](#-license--terms)

---

## 📦 Page Architecture

```text
┌────────────────────────────────────────────────────────────────┐
│        HERO · Musfira Sehar · 13 July – 12 October 2026        │
├────────────────────────────────────────────────────────────────┤
│      Role · timeline rail · overview · focus-area filters      │
└────────────────────────────────┬───────────────────────────────┘
                                 ↓
┌────────────────────────────────────────────────────────────────┐
│                        SUMMARY SECTIONS                        │
├────────────┬────────────┬────────────┬────────────┬────────────┤
│ Spotlight  │ Key        │ Research   │ Skills &   │ Impact &   │
│ & cert.    │ projects   │ & eval     │ learning   │ next steps │
└────────────┴────────────┴──────┬─────┴────────────┴────────────┘
                                 ↓
┌────────────────────────────────────────────────────────────────┐
│          WORK LOG · 63 entries · July → October 2026           │
├────────────────────────────────────────────────────────────────┤
│     Search · month & type filters · expand all · log links     │
│     47 daily · 4 biweekly · 12 research notes and updates      │
└────────────────────────────────────────────────────────────────┘
```

| Page Layer | What It Holds | Quick Links / Reference |
| --- | --- | --- |
| **Top: Hero** | Name, role, internship timeline, overview and the four focus-area filters | [Interactive Interfaces](#-interactive-interfaces) |
| **Middle: Summary** | Recognition, key projects, research and evaluation, skills and learning, impact and next steps | [Page Sections](#-page-sections) |
| **Bottom: Work Log** | Every daily update, biweekly update and research note, grouped by month on a timeline | [Keyboard Controls](#-keyboard-controls) |

---

## ✨ Key Features

✅ **Present Mode** - Turns each section into a full-screen slide, so the page can be presented in a meeting with the arrow keys.

✅ **Focus-Area Filters** - Selecting a focus area (Agentic AI and RAG, AI and web application security, AI model evaluation and deployment, frontend development) highlights the related work across the page and dims the rest.

✅ **Skill Links** - Selecting a skill highlights where it was used. Skills that appear in no project stay plain, so nothing is overstated.

✅ **Searchable Work Log** - Searches every entry at once, with comma-separated terms (for example `Handoff, chunking`), matching words highlighted, and month and type filters.

✅ **Evidence Links** - Each summary card shows how many log entries back it up (for example "RAG chunking: 4 log entries") and jumps straight to them.

✅ **Self-Contained** - One HTML file with the certificate embedded, light and dark themes, a print layout that expands the whole log, and no dependencies beyond optional web fonts.

---

## 📑 Page Sections

| Section | What It Covers |
| --- | --- |
| **Overview** | Role, internship dates, a summary of the work and the four focus areas |
| **01 Recognition** | Recognition Spotlight: AI Models Openness Report, reviewed and accepted after two review passes (team award), with the certificate |
| **02 Key Projects** | BreachMirror AI, the AI Security Assistant Chrome Extension, Claude Code skills (Optimize, Handoff and Token Optimizer), the Prompt-a-thon 2026 SharePoint site and R&D support |
| **03 Research and Evaluation** | AI Models Openness Report, RAG chunking, Agentic UI, AI and web security, and NL-to-SQL and internal apps |
| **04 Skills and Learning** | Tools built with and explored, courses, and compliance training |
| **05 Impact and Next Steps** | Three impact statements and the next steps for BreachMirror AI |
| **06 Work Log** | 63 entries, word for word, from 15 July to 6 October 2026 |

---

## 📁 Repository Structure

* **`Internship Tenure – Musfira Sehar.html`** - The complete interactive page: markup, styles, scripts and the embedded certificate image.
* **`README.md`** - This guide.
* **`LICENSE`** - MIT License.

---

## 🧰 Tech Stack

| Component | Technology | Quick Links |
| --- | --- | --- |
| **Markup** | Semantic HTML5 (`<details>`, `<dialog>`, `<time>`, ARIA attributes) | [MDN: HTML](https://developer.mozilla.org/en-US/docs/Web/HTML) |
| **Styling** | CSS3 custom properties, Grid, `color-mix()`, `prefers-color-scheme`, print styles | [MDN: CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) |
| **Scripting** | Vanilla JavaScript (IntersectionObserver, Fullscreen API, TreeWalker search highlighting) | [MDN: JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) |
| **Typography** | Fraunces, IBM Plex Sans and IBM Plex Mono via Google Fonts | [Google Fonts](https://fonts.google.com/) |
| **Media** | Certificate embedded as a base64 WebP image | [MDN: data URLs](https://developer.mozilla.org/en-US/docs/Web/URI/Schemes/data) |

---

## 💻 System Requirements

* **Browser:** Any modern browser (Chrome, Edge, Firefox or Safari).
* **Internet:** Optional. It is only used to load the web fonts; offline, the page falls back to standard fonts and everything still works.
* **Install:** None. There is no build step and no package to install.

---

## 🚀 Viewing Guide

### Step 1: Clone the Repository

```bash
git clone https://github.com/MoNsT3R-code/Internship-tenure-.git
cd Internship-tenure-
```

### Step 2: Open the Page

Double-click `Internship Tenure – Musfira Sehar.html`, or open it from the terminal:

```bash
# Windows
start "" "Internship Tenure – Musfira Sehar.html"

# macOS
open "Internship Tenure – Musfira Sehar.html"
```

### Step 3: Present It (optional)

Press **P** or select **Present** in the top bar, then move between sections with the arrow keys. Press **Esc** to leave.

### Optional: Publish with GitHub Pages

In the repository, open **Settings → Pages**, set the source to **Deploy from a branch**, choose `main` and `/ (root)`, and save. GitHub then serves the page at a public URL.

---

## 🎮 Keyboard Controls

| Keys | Action |
| --- | --- |
| `P` | Enter or leave present mode |
| `→` `↓` `Page Down` `Space` | Next slide (present mode) |
| `←` `↑` `Page Up` | Previous slide (present mode) |
| `Home` / `End` | First or last slide (present mode) |
| `Esc` | Leave present mode, clear the active filter, or clear the log search |

Shortcuts are ignored while typing in the search box.

---

## 📊 Interactive Interfaces

| Interface | Where | How to Use | What It Does |
| --- | --- | --- | --- |
| **Focus filters** | Hero | Select a focus area; select it again to clear | Highlights the related summary items and shows a count in a floating bar |
| **Skill links** | Skills and learning | Select a skill marked with a gold dot | Highlights the summary items that mention it |
| **Evidence links** | Summary cards | Select "*n* log entries" | Searches the work log for that topic and scrolls to it |
| **Log search** | Work log | Type one or more comma-separated terms | Shows matching entries, opens them and highlights the words |
| **Month & type filters** | Work log | Choose Jul–Oct and Daily, Biweekly or Notes & updates | Narrows the timeline |
| **Certificate viewer** | Recognition | Select the certificate thumbnail | Opens the full certificate in an accessible dialog |
| **Theme & print** | Top bar | Use the moon/sun and printer buttons | Switches light and dark themes; prints with every log entry expanded |

---

## 🧱 Design Highlights

### 🎨 Certificate-Inspired Visual Identity

The navy and gold palette and the gold star constellation in the header echo the Recognition Spotlight certificate, so the award and the page read as one piece. Fraunces headings, IBM Plex body text and a mono face for dates and data give it an editorial feel.

### ♿ Accessible and Resilient

Buttons report their state with `aria-pressed`, focus outlines are visible, the certificate opens in a native `<dialog>`, and animations switch off under `prefers-reduced-motion`. Work log entries use native `<details>` elements, so the content stays readable even without JavaScript.

### 🔎 Evidence-Linked Summary

Each summary claim is tied to the log: link counts are computed from the log entries when the page loads, so a card can never point to evidence that is not there.

---

## 📄 License & Terms

Released under the [MIT License](LICENSE) © 2026 Musfira Sehar. The page describes work done during the internship; internal application names have been generalised.
