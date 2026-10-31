<div align="center">

# SkillProof

### Auditable Developer Skill Verification Ledger

*Deterministic skill extraction from PDF resumes cross-referenced against public GitHub repository artifacts, commit history, and automated anti-gaming trust signals — with zero LLM hallucinations.*

<br/>

[![Live Demo](https://img.shields.io/badge/Frontend-Live%20Demo-4ade80?style=for-the-badge&logo=vercel&logoColor=white)](https://skill-proof-silk.vercel.app)
[![API](https://img.shields.io/badge/Backend-API%20Live-3b82f6?style=for-the-badge&logo=render&logoColor=white)](https://skillproof-api-7ebf.onrender.com)
[![GitHub](https://img.shields.io/badge/Source-GitHub-171717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/nairkartik08/SkillProof)

[![Node](https://img.shields.io/badge/Node.js-22.x-339933?style=flat-square&logo=nodedotjs)](https://nodejs.org)
[![React](https://img.shields.io/badge/React-19-61dafb?style=flat-square&logo=react)](https://react.dev)
[![MongoDB](https://img.shields.io/badge/MongoDB-Atlas-47A248?style=flat-square&logo=mongodb)](https://mongodb.com)
[![Tailwind](https://img.shields.io/badge/Tailwind-4.x-06b6d4?style=flat-square&logo=tailwindcss)](https://tailwindcss.com)

</div>

---

## 🌐 Live Deployment

| Service | URL | Platform |
|---|---|---|
| **Frontend App** | [skill-proof-silk.vercel.app](https://skill-proof-silk.vercel.app) | Vercel |
| **Backend API** | [skillproof-api-7ebf.onrender.com](https://skillproof-api-7ebf.onrender.com) | Render |
| **API Health** | [/api/health](https://skillproof-api-7ebf.onrender.com/api/health) | Render |

> **Note:** The Render backend is on a free plan and may take ~30 seconds to wake up on first request.

---

## 👥 Team & Submission

| Field | Details |
|---|---|
| **Team Name** | CodePrefix |
| **Members** | Aman Mishra · Kartik Nair · Ramzan Khan |
| **Problem Statement** | SkillProof — Verification & Validation of Developer Skill Claims in Technical Hiring |
| **Domain** | Edutech |

---

## ⚡ What is SkillProof?

Traditional technical hiring relies on self-reported resume bullets or black-box AI screeners that frequently hallucinate inferences. **SkillProof** replaces both with a **Deterministic Verification Ledger**:

| Pillar | Description |
|---|---|
| 🚫 **Zero LLM Hallucinations** | 100% deterministic ontology matching with recency and depth decay |
| 🔗 **Concrete Artifact Evidence** | Every skill links to real `package.json`, `go.mod`, file trees, and commit SHAs |
| 🛡️ **Anti-Gaming Trust Signals** | Detects tutorial clones, commit dumps, empty forks, and vendored code |
| 🎓 **Student Lab Notebook** | Warm paper-based workspace with readiness summaries and learning roadmaps |
| 🗂️ **Recruiter Case Desk** | High-density evidence desk with candidate share verification and audit sheets |

---

## 📸 Platform Walkthrough

### 1 — Landing Page & Product Overview
> *Warm editorial aesthetic built on Fraunces serif and IBM Plex typography. Clear bifurcation between Student Coach and Recruiter Evidence Desk.*

![SkillProof Hero](docs/screenshots/Screenshot%202026-10-31%20160939.png)

<table width="100%">
  <tr>
    <td width="50%" align="center">
      <b>Dual-Lens Entry Points</b><br/>
      <img src="docs/screenshots/Screenshot%202026-10-31%20161022.png" alt="Dual Lens Selection" />
    </td>
    <td width="50%" align="center">
      <b>Verification Lifecycle & Ethics Guardrails</b><br/>
      <img src="docs/screenshots/Screenshot%202026-10-31%20161035.png" alt="How SkillProof Works" />
    </td>
  </tr>
</table>

---

### 2 — Authentication & Access Control
> *Role-gated JWT auth with HTTP-only cookies, rotating hashed refresh tokens, and CSRF double-submit protection.*

<p align="center">
  <img src="docs/screenshots/Screenshot%202026-10-31%20161049.png" alt="Sign In Page" width="550" />
</p>

---

### 3 — Student Lab Notebook
> *Personalized workspace with deterministic audit summaries, evidence distribution charts, and anti-gaming discrepancy detection.*

<table width="100%">
  <tr>
    <td width="50%" align="center">
      <b>Student Coach Landing</b><br/>
      <img src="docs/screenshots/Screenshot%202026-10-31%20161129.png" alt="Student Welcome" />
    </td>
    <td width="50%" align="center">
      <b>Saved Analysis Dossiers</b><br/>
      <img src="docs/screenshots/Screenshot%202026-10-31%20161141.png" alt="Your Analyses" />
    </td>
  </tr>
  <tr>
    <td width="50%" align="center">
      <b>Candidate Overview & Proven Counts</b><br/>
      <img src="docs/screenshots/Screenshot%202026-10-31%20161241.png" alt="Candidate Overview" />
    </td>
    <td width="50%" align="center">
      <b>Evidence Distribution Chart</b><br/>
      <img src="docs/screenshots/Screenshot%202026-10-31%20161255.png" alt="Evidence Donut Chart" />
    </td>
  </tr>
</table>

#### Skill Ledgers & Discrepancy Findings
> *GitHub Linguist byte counts, package manifest links, recency gaps, and unlisted positive strength discovery.*

![Discrepancy Findings & Unlisted Strengths](docs/screenshots/Screenshot%202026-10-31%20161312.png)

![Verified Skills Breakdown & Scores](docs/screenshots/Screenshot%202026-10-31%20161329.png)

<table width="100%">
  <tr>
    <td width="50%" align="center">
      <b>Inspected Repositories & Sampled Commits</b><br/>
      <img src="docs/screenshots/Screenshot%202026-10-31%20161409.png" alt="Repositories Inspected" />
    </td>
    <td width="50%" align="center">
      <b>Share Link, Badges & Ledger Export</b><br/>
      <img src="docs/screenshots/Screenshot%202026-10-31%20161428.png" alt="Share & Export Modal" />
    </td>
  </tr>
</table>

---

### 4 — Job Role Reconciliation & Micro-Task Roadmaps
> *Map verified evidence against real Job Descriptions to identify qualification gaps and generate deterministic micro-tasks to close them.*

<table width="100%">
  <tr>
    <td width="50%" align="center">
      <b>Job Description Parser & Role Intake</b><br/>
      <img src="docs/screenshots/Screenshot%202026-10-31%20161619.png" alt="Job Description Intake" />
    </td>
    <td width="50%" align="center">
      <b>Verified Match Coverage</b><br/>
      <img src="docs/screenshots/Screenshot%202026-10-31%20161632.png" alt="Role Coverage Score" />
    </td>
  </tr>
</table>

![Qualification Gap Micro-Tasks](docs/screenshots/Screenshot%202026-10-31%20161645.png)

---

### 5 — Recruiter Case Desk
> *High-density, cool-toned Case Desk for talent acquisition. Stateless evaluation, capability-link lookups, and strict non-ranking requirement matrices.*

<table width="100%">
  <tr>
    <td width="50%" align="center">
      <b>Recruiter Case Desk Entry</b><br/>
      <img src="docs/screenshots/Screenshot%202026-10-31%20161815.png" alt="Recruiter Case Desk" />
    </td>
    <td width="50%" align="center">
      <b>Candidate Evidence Sheet & JD Match</b><br/>
      <img src="docs/screenshots/Screenshot%202026-10-31%20161917.png" alt="Candidate Evidence Sheet" />
    </td>
  </tr>
  <tr>
    <td width="50%" align="center">
      <b>Verified Skills Breakdown (Recruiter Lens)</b><br/>
      <img src="docs/screenshots/Screenshot%202026-10-31%20161952.png" alt="Recruiter Skill Breakdown" />
    </td>
    <td width="50%" align="center">
      <b>Discrepancies & Self-Verification Drilldown</b><br/>
      <img src="docs/screenshots/Screenshot%202026-10-31%20162009.png" alt="Discrepancies & Verification" />
    </td>
  </tr>
</table>

#### Multi-Candidate Requirement Matrix
> *Side-by-side comparison respecting input order — no algorithmic ranking, scores, or hire recommendations.*

![Requirement Matrix](docs/screenshots/Screenshot%202026-10-31%20162059.png)

---

## 🏛️ Architecture

```text
                               ┌────────────────────────┐
                               │  Candidate PDF Resume  │
                               └───────────┬────────────┘
                                           │ pdf-parse + section parser
                                           ▼
┌──────────────────────┐       ┌────────────────────────┐
│  Public GitHub API   │       │ Skill Extraction Engine│
│ (Repos, Commits, AST)│       │ (250+ Ontological SKUs)│
└──────────┬───────────┘       └───────────┬────────────┘
           │                               │
           ▼                               ▼
┌───────────────────────────────────────────────────────┐
│              Evidence Collector Engine                │
│  - Manifest Parsers (package.json, go.mod, Cargo.toml)│
│  - Code Tree Scan (Imports, extensions, config files) │
│  - Candidate Commit Attribution & Time-span Analysis  │
└──────────────────────────┬────────────────────────────┘
                           │
                           ▼
┌───────────────────────────────────────────────────────┐
│             Anti-Gaming Trust Signal Engine           │
│  - Fork Detection with commit delta check             │
│  - Commit burst & single-dump flagger                 │
│  - README Jaccard boilerplate matcher                 │
│  - Vendored code detection                            │
└──────────────────────────┬────────────────────────────┘
                           │
                           ▼
┌───────────────────────────────────────────────────────┐
│                  Scoring Engine V2                    │
│    Weights: Manifest (20) + Commit Attribution (20)   │
│             + Recency (15) + Complexity/Breadth (15)  │
│             + Time-span (15) + Graph Implication (15) │
│               Multiplied by Trust Factor [0.0 - 1.0]  │
└──────────────────────────┬────────────────────────────┘
                           │
              ┌────────────┴────────────┐
              ▼                         ▼
   ┌──────────────────────┐  ┌──────────────────────┐
   │ Proven (Score >= 70) │  │ Partial (30 <= S <70)│
   └──────────────────────┘  └──────────────────────┘
              │                         │
              └────────────┬────────────┘
                           ▼
   ┌─────────────────────────────────────────────────┐
   │             Discrepancy Analysis                │
   │  - POSITIVE: Discovered unlisted strengths      │
   │  - YEARS_MISMATCH: Experience vs Commit tenure  │
   │  - NO_ARTIFACT: Claimed skills with zero code   │
   └─────────────────────────────────────────────────┘
```

---

## 🔬 Scoring Methodology

Every skill is evaluated against an auditable rubric out of **100 points**:

| Dimension | Max Points | Verification Criteria |
|---|---|---|
| **Manifest Evidence** | 20 pts | Direct dependency declared in build manifest |
| **Commit Attribution** | 20 pts | Commits authored by the candidate (email/username match) |
| **Recency** | 15 pts | Activity within 6 months (scaled decay up to 2 years) |
| **Breadth / Complexity** | 15 pts | Discovered across multiple distinct repositories |
| **Time-span Depth** | 15 pts | Active commit history spanning > 12 months |
| **Graph Implication** | 15 pts | Transitive implication from parent technologies |

**Classification Verdicts:**

| Verdict | Threshold | Meaning |
|---|---|---|
| ✅ **PROVEN** | ≥ 70 pts | Solid multi-repository artifact trail with candidate commits |
| 🟡 **PARTIAL** | 30–69 pts | Documented presence without extended tenure |
| ❌ **CLAIMED-ONLY** | < 30 pts | Listed on resume with no public repository backing |

---

## 🛡️ Anti-Gaming Trust Signals

| Signal | Trigger |
|---|---|
| `FORK_NO_OWN_COMMITS` | Forked project with 0 candidate-authored commits |
| `TEMPLATE_OR_TUTORIAL` | Matches known educational boilerplate (Jaccard > 0.70) |
| `SINGLE_COMMIT_DUMP` | >90% of lines created in one initial commit |
| `COMMIT_BURST` | >20 commits created in <24 hours |
| `VENDORED_CODE` | Committed `node_modules/`, `vendor/`, or `.venv/` directories |

---

## 💻 Technology Stack

| Layer | Technologies |
|---|---|
| **Frontend** | React 19, Vite, React Router 7, Tailwind CSS 4, Lucide Icons |
| **Typography** | Fraunces (headings), IBM Plex Sans (UI), IBM Plex Mono (data) |
| **Backend** | Node.js 22, Express 5, Mongoose 8, Zod, Helmet, Multer |
| **Storage** | MongoDB Atlas (metadata), Cloudinary (PDF resumes) |
| **Auth & Security** | HttpOnly Cookie JWT, rotating refresh tokens, CSRF double-submit, rate limiting |
| **Testing** | Native Node.js Test Runner — 25+ integration & unit tests |
| **Deployment** | Render (backend), Vercel (frontend) |

---

## 🚀 Local Setup

### Prerequisites
- Node.js `22.x`
- MongoDB Atlas URI (or local MongoDB)
- Cloudinary account
- GitHub personal access token (optional but recommended)

### 1. Clone & Install
```bash
git clone https://github.com/nairkartik08/SkillProof.git
cd SkillProof
npm run setup
```

### 2. Configure Environment
```bash
cp backend/.env.example backend/.env
```

Fill in `backend/.env`:
```env
PORT=8000
CLIENT_ORIGIN=http://localhost:5173
MONGO_URI=mongodb+srv://<username>:<password>@<cluster>.mongodb.net/skillproof
GITHUB_TOKEN=ghp_your_optional_token
CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_key
CLOUDINARY_API_SECRET=your_secret
JWT_SECRET=replace-with-32-char-minimum-secret
REFRESH_SECRET=replace-with-a-different-32-char-secret
COOKIE_SECRET=replace-with-a-random-32-char-secret
COOKIE_SECURE=false
```

### 3. Start Both Servers
```bash
npm run dev
```

| Service | URL |
|---|---|
| Frontend | http://localhost:5173 |
| Backend API | http://localhost:8000/api |

### 4. Run Tests
```bash
npm test --prefix backend
```

---

## 📡 APIs & Data Sources

| Source | Purpose |
|---|---|
| **GitHub REST API v3** | Repository metadata, commit histories, file trees, language stats |
| **Skill Ontology** | Built-in 250+ SKU mapping of technologies, packages, file extensions, and DAG relationships |
| **Cloudinary Storage API** | Secure authenticated PDF resume storage |

---

## 🔮 Limitations & Future Scope

### Current Limitations
- **Public GitHub Only** — Analysis restricted to public repositories for determinism and privacy
- **Deterministic MVP** — No private repo access, OCR, LLM inference, or code execution
- **GitHub Rate Limits** — Unauthenticated: 60 req/hr; resolved by setting `GITHUB_TOKEN`

### Future Scope
- **GitLab & Bitbucket** — Expand evidence collection to other VCS platforms
- **W3C Verifiable Credentials** — Issue cryptographic VCs for proven skill claims
- **Org-Level Recruiter Teams** — Multi-tenant employer accounts with candidate shortlists
