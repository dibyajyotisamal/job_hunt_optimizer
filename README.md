# Job Hunt Optimizer (AWS PartyRock)
[![Built on AWS](https://img.shields.io/badge/Built%20on-AWS-orange?style=flat-square)](https://aws.amazon.com)  [![GenAI Powered](https://img.shields.io/badge/GenAI-Amazon%20Bedrock-lightgrey?style=flat-square)](https://aws.amazon.com/bedrock)  [![PartyRock Demo](https://img.shields.io/badge/Demo-PartyRock-blue?style=flat-square)](https://partyrock.aws/u/dibyajyotisamal/mHu1JEpj1/Job-Hunt-Optimizer-Upload-Resume-and-Job-Description)  [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](LICENSE)  

[![Live on PartyRock](https://img.shields.io/badge/Live%20on%20PartyRock-blue?style=flat-square)](https://partyrock.aws/u/dibyajyotisamal/mHu1JEpj1/Job-Hunt-Optimizer-Upload-Resume-and-Job-Description)


Paste any Job Description (JD) and your resume, click run, and get **everything you need to tailor your application fast**:

- A **JD skill/KPI matrix** (JSON + human-readable snapshot)
- A **prioritized gap list** (what you’re missing & why it matters)
- A **fully rewritten resume** in Markdown with `[NEED METRIC]` / `[NEED DETAIL]` placeholders (no fabrication)
- **KPI & evidence ideas** (what to measure, where to pull data)
- A **14‑day action checklist** (Day 1…Day 14, each with a proof artifact)

**Live app:** [Job Hunt Optimizer on PartyRock](https://partyrock.aws/u/dibyajyotisamal/mHu1JEpj1/Job-Hunt-Optimizer-(Upload-Resume-and-Job-Description))

---

## 1. Why this exists

Most "resume optimizers" spit out fluffy bullets and hallucinated numbers. Recruiters skim. JDs are dense. Candidates guess. This tool forces **truthful, structured, and actionable** outputs so you can update your resume and portfolio with evidence, not BS.

---

## 2. What you get (Outputs)

1. **JD Required Skills Snapshot** – Hard/soft skills, KPIs, verbs, summarized from the JD.
2. **Gap Analysis** – Top 5 gaps, redundant bullets to trim, missing metrics, and priority order.
3. **Resume Rewriter** – Complete resume in Markdown, aligned to the JD. Missing data is clearly tagged (`[NEED METRIC]`, `[NEED DETAIL]`).
4. **KPI & Evidence Ideas** – Which metrics to show, how to calculate them, and where to pull proof.
5. **14‑Day Action Checklist** – Concrete tasks with Day labels and proof artifacts.
6. **(Optional) JSON Export** – One bundle containing all sections for future automation.

---

## 3. How to use

1. **Paste JD** into *Job Description*.
2. **Paste your current resume** (full text or bullets) into *Your Resume*.
3. Choose **Tone** (and Role Level if shown). Toggle **Return JSON Too?** if you want machine-readable output.
4. Click **Run All** (or run blocks top → bottom).
5. Read outputs in this order:
   1. **JD Required Skills (Snapshot)**
   2. **Gap Analysis**
   3. **Resume Rewriter** (replace placeholders with real numbers/details)
   4. **KPI & Evidence Ideas**
   5. **14‑Day Checklist**
   6. **JSON Export** (only if toggle is ON)

> **Truth rule:** Never invent achievements. Either supply the real number or cut the claim.

---

## 4. Tech stack / How it’s built

- **AWS PartyRock** (on top of Amazon Bedrock foundation models)
- Prompt engineering with strict schemas (JSON / Markdown)
- Modular block design: JD parse → gap analysis → resume rewrite → KPI ideas → checklist
- Optional JSON export for future programmatic use

---

## 5. Demo/Screenshots

<!-- All panels sized to 800×450 for consistency -->
<img src="media/jd-skills.gif" width="800" height="450" alt="JD Required Skills Snapshot" />

<img src="media/gap-analysis.gif" width="800" height="450" alt="Gap Analysis" />

<img src="media/resume-rewriter.gif" width="800" height="450" alt="Resume Rewriter" />

<div style="display: grid; grid-template-columns: 1fr 1fr; gap: 20px; align-items: start;">
  <img src="media/kpi-and-evidence-ideas.gif" width="500" alt="KPI & Evidence Ideas" />
  <img src="media/14-day-checklist.gif" width="500" alt="14‑Day Checklist" />
</div>

---

## 6. Roadmap

- ATS keyword density scoring
- Multi-JD comparer (find common denominators across roles)
- Interview question generator from JD gaps
- Export to Markdown/PDF directly
- API hook / script to auto-update a resume template


---

## 7. Truth & ethics

This tool deliberately uses `{NEED METRIC}` / `{NEED DETAIL}` tags to prevent fabricated numbers. Replace them with real data or remove the claim. Lying on resumes is grounds for rejection.

---

## 8. License

MIT License – see `LICENSE`.

---

