What the Content QA Assistant Actually Does (Clarified)

AI-assisted Pre-QA for AEM content that runs before formal QA and before publish.

Core Capabilities

The assistant scans authored pages/components and flags risks early:

📝 Authoring & Content Quality

Missing or placeholder content

Tone/terminology inconsistencies (brand-approved language)

Duplicate content across pages

Excessive reading level (e.g., > Grade 8/10 where not allowed)

Inconsistent headings, CTA formats, references

♿ Accessibility (WCAG-aligned)

Missing alt text

Improper heading hierarchy

Color contrast issues (where detectable)

Missing form labels / ARIA issues

Link text like “click here”

⚠️ Compliance & Pharma-Specific Checks

Missing mandatory disclaimers

Missing safety information / references

Claims without references

Usage of restricted words (configurable dictionary)

Region-specific compliance rules (US vs EU, etc.)

🔗 Technical & Structural

Broken internal/external links

Missing metadata (title, description, tags)

SEO basics (duplicate titles, empty H1s)

-------------------------------------------------------------------PHASES-------------------------------------------------------------

Phase 0 – Python Foundations

Learn Python basics needed to build and reason about a real system.

Phase 1 – Rule-Based Text Content QA

Build a Python engine that scans raw content text and flags compliance and content issues using deterministic rules.

Phase 2 – HTML & Accessibility QA

Parse HTML content and detect accessibility, structural, and content issues (WCAG-style checks).

Phase 3 – Config-Driven QA Rules

Move QA rules, severities, and keywords into config files so rules can change without code changes.

Phase 4 – OOP Refactor & Modular Architecture

Refactor the tool into classes and modules for clean, scalable, enterprise-grade design.

Phase 5 – Error Handling & Resilience

Add exception handling so the tool fails gracefully and never blocks publishing due to runtime errors.

Phase 6 – Link & Metadata Validation

Check broken links, missing metadata, SEO basics, and reference integrity.

Phase 7 – AI-Assisted Content Intelligence

Use AI/NLP to detect claims, tone issues, readability, and potential compliance risks beyond rule-based logic.

Phase 8 – Reporting, Scoring & Publish Gating

Generate structured QA reports, quality scores, and configurable pass/fail thresholds.

Phase 9 – CLI & Automation Readiness

Expose the tool via command line for CI/CD, AEM workflows, or batch content scans.

Phase 10 – AEM Integration Concept

Design how the tool plugs into AEM authoring and pre-publish workflows (conceptual + optional POC).
