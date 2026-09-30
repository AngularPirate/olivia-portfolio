# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Stack

Static HTML/CSS, no framework and no build step, hosted on GitHub Pages at https://oliviakoeppen.com (repo AngularPirate/olivia-portfolio, branch `main`). Every push to `main` deploys.

## Users

Primary: the hiring committee for the Instructional Designer role at the College of Western Idaho (CWI), a community college. Olivia already passed the screening call; the committee reviews the site around a second-round interview. Likely readers: an instructional design or eLearning manager, faculty members, and HR. They are busy, skim on a laptop (sometimes a phone), and open the site from a link in an email. Some may be skeptical of AI and of flashy design.

Their job: decide whether Olivia can do the design side of instructional design, not just build Canvas courses, and gather evidence to argue for her in the committee debrief.

Secondary (later): hiring teams for future instructional design roles. The site should grow beyond this one application.

## Product Purpose

A personal portfolio that shows Olivia Koeppen is ready for an instructional designer role. Success: the committee finishes convinced she already does much of the job, sees real work samples, and has concrete evidence to cite. Near-term scope is the portfolio (projects) and her resume; an About section will be added later.

## Positioning

Olivia combines three things most candidates have only one or two of: classroom teaching (sophomore English, 130+ students, standards-aligned units and assessments), hands-on Canvas course building and faculty consultation in higher education (Boise State School of Nursing, 100+ courses per term), and strong writing (B.A. English; M.Ed. Educational Leadership). Her work is real, program-scale, and measured, not hypothetical side projects.

## Operating Context

Reviewed around a job interview. The committee is academic, works in Canvas daily, and knows instructional design vocabulary: learning outcomes, alignment, Quality Matters, accessibility (ADA/Section 508, WCAG), faculty as subject matter experts. Case studies follow an academic structure: Context, Problem, Approach, Outcome, Reflection.

## Capabilities and Constraints

- Near-term sections: header/intro, career path, four project case studies with artifacts, skills, education, contact, resume.
- Each project gets its own detail view that shows the artifact, not just a link.
- Content source of truth: `content/SITE-CONTENT.md` (Olivia's own wording, 2026-09-30). Do not rewrite her facts; wording changes need her approval.
- Public site: no student information, no confidential Boise State course content, no phone number, no home address.
- Hidden from search engines (`robots.txt` + `noindex`) until Olivia decides otherwise.
- Must work at phone width and in light and dark system themes.
- Open: "Currently learning" certifications are not yet provided; leave out rather than fake.

## Brand Commitments

- Name as shown: Olivia Koeppen. Location: Boise, Idaho. Email: Oliviahkoeppen@gmail.com. LinkedIn: https://www.linkedin.com/in/oliviakoeppen.
- Voice: first person, plain, specific, academic, modest and checkable. Confident and prepared, never overconfident or salesy. No hype words, no AI-flavored phrasing.
- Constraints the user made binding: academic rather than creative; no muted, washed-out palettes; do not use Boise State (blue/orange) or CWI brand colors.
- Reference the user liked for page structure: a case-study layout with project title, one-line subtitle, short description, Audience / Responsibilities / Tools facts, an artifact image beside the text, and a single "view the project" action, followed by Problem / Solution / Process sections with artifacts shown inline.

## Evidence on Hand

- Four real projects with outcomes (see `content/SITE-CONTENT.md`):
  1. Course Readiness for the School of Nursing: artifact `assets/canvas-launch-checklist-sample.docx` (in repo).
  2. Accessibility in Nursing Canvas Courses: 74% → 92% average accessibility score across 100+ courses; artifact Accessibility Process Flow (pending upload).
  3. BS-DNP Online Course Template Redesign: 17 courses migrated, 10 built new, 2 launching Spring 2027; artifact template redesign examples (pending upload).
  4. Standardizing AI Use Expectations: 6 of 10 first-semester PreLicensure courses adopted the icon system; artifact AI Icon Faculty Guide PDF (pending upload).
- Resume PDF: pending upload.
- No testimonials, headshot, or certifications on hand. Do not invent any.

## Product Principles

1. Evidence over claims: every project shows a real artifact and a real outcome.
2. Faculty and students first: frame work around who it helped, not the tool.
3. Plain and academic: the site itself should read like well-designed course material.
4. Nothing unfinished in public: sections without content are omitted, never placeholders.
5. Built to grow: new projects and an About section can be added without redesign.

## Accessibility & Inclusion

WCAG 2.1 AA at minimum. The site is a live demonstration of her accessibility practice: semantic headings, alt text for every artifact image, sufficient contrast in both themes, keyboard focus states, readable text sizes, and reduced-motion support.
