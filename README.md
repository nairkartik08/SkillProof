# SkillProof

> **Auditable Developer Skill Verification Ledger**  
> *Deterministic skill extraction from PDF resumes cross-referenced against public GitHub repository artifacts, commit history, and automated anti-gaming trust signals.*

---

## 👥 Team & Submission Information

### 1. Team Details
- **Team Name**: CodePrefix
- **Team Members**: Aman Mishra, Kartik Nair, Ramzan Khan

### 2. Problem Statement
- **Problem Statement Name**: SkillProof - Verification & Validation of Developer Skill Claims in Technical Hiring
- **Selected Domain**: Edutech
  
### 3. Project Details
- **Project Title**: SkillProof - Auditable Developer Skill Verification Ledger
- **Short Description**: SkillProof is a deterministic skill verification platform that eliminates resume inflation and opaque AI screener hallucinations by matching PDF resume claims directly against public GitHub repository artifacts, build manifests, and commit history. It generates an auditable, score-backed evidence ledger classified as `Proven`, `Partial`, or `Claimed-only` with automated anti-gaming trust checks. The platform empowers candidates with actionable learning roadmaps while providing recruiters with tamper-evident evidence sheets and job-matching matrices.

---

## ⚡ Project Overview

Traditional technical hiring relies heavily on self-reported resume bullets or black-box AI resume screeners that frequently hallucinate inferences. **SkillProof** replaces both with a **Deterministic Verification Ledger**:

- **Zero LLM Hallucinations**: 100% deterministic ontology matching and graph expansion with recency and depth decay.
- **Concrete Artifact Evidence**: Every verified skill links to real GitHub build manifests (`package.json`, `go.mod`, `Cargo.toml`), file AST trees, and candidate commit hashes.
- **Anti-Gaming Trust Signals**: Automated algorithms detect and penalize tutorial clones, commit dumping bursts, empty forks, and vendored code (`node_modules` committed directly).
- **Dual Lens Design**: 
  - **Student Lab Notebook**: Warm paper-based workspace with readiness summaries, DAG learning roadmaps, resume bullet fixes, and micro-task verification.
  - **Recruiter Case Desk**: High-density cool steel desk for talent acquisition with candidate share verification, requirement matrices, and audit evidence sheets.

---

## 📸 Platform Walkthrough & Interface Preview

### 1. Landing Page & Product Overview
> *Warm editorial aesthetic built on Fraunces serif and IBM Plex typography. Introduces the deterministic verification paradigm and clear bifurcation between Student Coach and Recruiter Evidence Desk.*

![SkillProof Hero](docs/screenshots/Screenshot%202026-10-31%20160939.png)

<table width="100%">
  <tr>
    <td width="50%" align="center">
      <b>Dual-Lens Intake & Entry Points</b><br/>
      <img src="docs/screenshots/Screenshot%202026-10-31%20161022.png" alt="Dual Lens Selection" />
    </td>
    <td width="50%" align="center">
      <b>Verification Lifecycle & Ethics Guardrails</b><br/>
      <img src="docs/screenshots/Screenshot%202026-10-31%20161035.png" alt="How SkillProof Works" />
    </td>
  </tr>
</table>

---

### 2. Authentication & Access Control
> *Role-gated JWT authentication with HTTP-only cookies, rotating hashed refresh tokens, and CSRF double-submit protection.*

<p align="center">
  <img src="docs/screenshots/Screenshot%202026-10-31%20161049.png" alt="Sign In Page" width="550" />
</p>

---

### 3. Student Lab Notebook — Audit & Coach Dashboard
> *Personalized workspace providing deterministic audit summaries, evidence distribution donuts, and anti-gaming discrepancy detections.*

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
      <b>The Evidence Picture (Score Breakdown)</b><br/>
      <img src="docs/screenshots/Screenshot%202026-10-31%20161255.png" alt="Evidence Donut Chart" />
    </td>
  </tr>
</table>

#### Skill Ledgers & Discrepancy Findings
> *Direct GitHub Linguist byte counts, package manifest links, recency gaps, and unlisted positive strength discovery.*

![Discrepancy Findings & Unlisted Strengths](docs/screenshots/Screenshot%202026-10-31%20161312.png)

![Verified Skills Breakdown & Scores](docs/screenshots/Screenshot%202026-10-31%20161329.png)

<table width="100%">
  <tr>
    <td width="50%" align="center">
      <b>Inspected Repositories & Sampled Commits</b><br/>
      <img src="docs/screenshots/Screenshot%202026-10-31%20161409.png" alt="Repositories Inspected" />
    </td>
    <td width="50%" align="center">
      <b>Public Share Link, Badges & Ledger Export</b><br/>
      <img src="docs/screenshots/Screenshot%202026-10-31%20161428.png" alt="Share & Export Modal" />
    </td>
  </tr>
</table>

---

### 4. Job Role Reconciliation & Micro-Task Roadmaps
> *Map verified evidence against real Job Descriptions (JDs) to identify qualification gaps and generate deterministic micro-tasks to close them.*

<table width="100%">
  <tr>
    <td width="50%" align="center">
      <b>Job Description Parser & Role Intake</b><br/>
      <img src="docs/screenshots/Screenshot%202026-10-31%20161619.png" alt="Job Description Intake" />
    </td>
    <td width="50%" align="center">
      <b>Verified Match Coverage (83% Match)</b><br/>
      <img src="docs/screenshots/Screenshot%202026-10-31%20161632.png" alt="Role Coverage Score" />
    </td>
  </tr>
</table>

![Qualification Gap Micro-Tasks](docs/screenshots/Screenshot%202026-10-31%20161645.png)

---

### 5. Recruiter Case Desk — High-Density Evidence Ledger
> *Dedicated cool-toned Case Desk for talent acquisition teams. Offers stateless evaluation, capability-link lookups, and strict non-ranking requirement matrices.*

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

#### Multi-Candidate Requirement Matrix (Side-by-Side Invariant Comparison)
> *Side-by-side comparison respecting input order without algorithmic candidate ranking, scores, or hire recommendations.*

![Requirement Matrix](docs/screenshots/Screenshot%202026-10-31%20162059.png)

---

## 🏛️ Architecture & Workflow

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

## 🔬 Scoring Methodology V2

Every skill is evaluated against an objective, auditable rubric out of 100 possible points:

| Dimension | Max Points | Verification Criteria |
|---|---|---|
| **Manifest Evidence** | 20 pts | Direct dependency or devDependency declared in build manifest |
| **Commit Attribution** | 20 pts | Commits authored by the candidate matching email/username |
| **Recency** | 15 pts | Activity within the last 6 months (scaled decay up to 2 years) |
| **Breadth / Complexity** | 15 pts | Discovered across multiple distinct repositories or subsystems |
| **Time-span Depth** | 15 pts | Active commit history spanning > 12 months on repositories |
| **Graph Implication** | 15 pts | Transitive implication from parent technologies (e.g. Next.js implies React) |

**Classification Verdicts:**
- **PROVEN** (`≥ 70 pts`): Solid multi-repository or multi-file artifact trail with candidate commits.
- **PARTIAL** (`30 - 69 pts`): Documented presence in dependencies or single commits without extended tenure.
- **CLAIMED-ONLY** (`< 30 pts`): Listed on resume with no public repository artifact backing.

---

## 🛡️ Anti-Gaming Trust Signals

Candidate repositories are automatically screened through trust heuristics:

1. **`FORK_NO_OWN_COMMITS`**: Candidate forked an active open-source project but authored 0 commits.
2. **`TEMPLATE_OR_TUTORIAL`**: Matches known educational boilerplate names (`freecodecamp`, `react-tutorial`, `100-days-of-code`) or CRA default README text (Jaccard similarity `> 0.70`).
3. **`SINGLE_COMMIT_DUMP`**: >90% of repository lines created in a single initial commit with no subsequent iterative history.
4. **`COMMIT_BURST`**: Artificial bursts (>20 commits created in <24 hours before submission).
5. **`VENDORED_CODE`**: Committed `node_modules/`, `vendor/`, or `.venv/` inflating language metrics.

---

## 🚀 Key Features

### For Candidates (Student Lab Notebook)
- **Proof Readiness Summary**: Instant overview of claimed vs. proven vs. partial skills with custom verdict stamps.
- **Interactive Experience Dumbbell Chart**: Visualizes claimed experience vs. verifiable commit history timeline.
- **DAG Learning Roadmap**: Topologically sorted learning path based on prerequisite dependencies and difficulty.
- **Resume Bullet Fix Generator**: Auto-generated bullet point improvements tailored to verified evidence.
- **Micro-Task Verification Workspace**: Interactive micro-tasks with live GitHub commit checking to upgrade `Partial` or `Claimed` skills to `Proven`.

### For Recruiters (Recruiter Case Desk)
- **Shared Profile Verification**: Access revoked-gated candidate share profiles with strict organisation access audit logging.
- **Requirement Matching Matrix**: Compare candidate evidence directly against job descriptions with percentage match scores and gap breakdowns.
- **Audit Evidence Sheet**: Deep dive into manifest citations, commit SHA links, and anti-gaming flag notes.

---

## 💻 Technology Stack

- **Frontend**: React 19, Vite, React Router 7, Tailwind CSS 4, Lucide Icons, Custom Design Tokens (`Fraunces` & `IBM Plex`).
- **Backend**: Node.js 22, Express 5, Mongoose 8, MongoDB Atlas, Multer, `pdf-parse`, Cloudinary SDK, Zod, Helmet.
- **Authentication & Security**: HttpOnly Cookie Sessions, JWT access tokens, double-submit CSRF protection, rate-limiting, and owner-isolated queries.
- **Test Suite**: Native Node.js Test Runner (`node --test`), 25+ integration & unit test files.

---

## 📡 Dataset & API Information

- **GitHub REST API v3**: Fetches repository metadata, commit histories, trees, and file contents deterministically.
- **Ontology Dataset**: Built-in 250+ technical skills ontology mapping technologies, package names (`package.json`, `PyPI`, `Go`), file extensions, and DAG relationships.
- **Cloudinary Storage API**: Secure authenticated PDF resume storage with metadata indexed in MongoDB Atlas.

---

## 🏃 Setup & Installation Instructions

### Prerequisites
- Node.js `22.x`
- MongoDB Atlas connection URI or local MongoDB instance

### 1. Clone & Install Dependencies
```bash
git clone https://github.com/RamzanKhansLab/TechForge_hackathon.git
cd TechForge_hackathon
npm run setup
```

### 2. Configure Environment
Copy `.env.example` templates in both `backend` and `frontend`:
```bash
cp backend/.env.example backend/.env
cp frontend/.env.example frontend/.env
```

Fill in `backend/.env`:
```env
PORT=8000
CLIENT_ORIGIN=http://localhost:5173
MONGO_URI=mongodb+srv://<username>:<password>@<cluster>.mongodb.net/skillproof?retryWrites=true&w=majority
GITHUB_TOKEN=ghp_your_optional_token
CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_key
CLOUDINARY_API_SECRET=your_secret
JWT_SECRET=replace-with-a-random-32-character-minimum-secret
REFRESH_SECRET=replace-with-a-different-random-32-character-minimum-secret
COOKIE_SECRET=replace-with-a-random-32-character-minimum-secret
COOKIE_SECURE=false
```

### 3. Start Local Servers
```bash
# Start frontend and backend concurrently
npm run dev
```
- **Frontend App**: `http://localhost:5173`
- **REST API**: `http://localhost:8000/api`

### 4. Run Automated Test Suite
```bash
npm test --prefix backend
```

---

## 🔮 Limitations & Future Scope

### Current Limitations
- **Public GitHub Only**: Analysis is intentionally restricted to public GitHub repositories to remain deterministic and non-intrusive.
- **Deterministic MVP**: No private repo code execution, OCR, or LLM-based code generation.
- **GitHub Rate Limits**: Unauthenticated GitHub API calls are capped at 60 requests/hr (resolved by supplying `GITHUB_TOKEN`).

### Future Scope
- **GitLab & Bitbucket Integration**: Expand evidence collection to other public version control platforms.
- **Verifiable Cryptographic Proofs**: Issue W3C Verifiable Credentials (VCs) for proven skill claims.
- **Org-Level Recruiter Teams**: Multi-tenant employer accounts with candidate comparison shortlists.
