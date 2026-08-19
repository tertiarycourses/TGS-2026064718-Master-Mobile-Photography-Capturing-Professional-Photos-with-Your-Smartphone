# Courseware QA Report — v12.0

Course: Master Mobile Photography: Capturing Professional Photos with Your Smartphone  
Course code: TGS-2022015227  
QA date: 19 August 2026

## Outcome

PASS — release-ready, subject to destination-side publication checks.

## Evidence

- Legacy coverage floor: all usable content from the 181-slide v11 deck is mapped in `SOURCE-COVERAGE-v12.0.md`.
- Trainer deck: 140 slides, 16:9, all-white visual system, photorealistic course-specific imagery, no out-of-bounds shapes, one verified GitHub hyperlink, and no detailed step-by-step procedures.
- Learner Guide: 27-page PDF plus DOCX with detailed procedures for all eight activities and a page-numbered source/contents register.
- Lesson Plan: 7-page PDF plus DOCX, aligned to final slide numbers, two days and 16 hours.
- Activities: eight individual real-use-case folders; 41 Markdown files have 41 same-basename PDFs; every activity includes a detailed guide, checklist, cheat sheet, evidence log and sample photo.
- Assessments: four DOCX instruments; WA has eight K1–K8 questions, PP has three A1–A7 tasks, and the two trainer-only answer keys are separate. All four pass the WSQ assessment structural verifier.
- Office validation: final PPTX, LG DOCX, LP DOCX and all four assessment DOCX files pass strict package/XML validation.
- Visual QA: full-deck contact sheets plus representative full-size slide, document, assessment and activity-PDF renders were inspected. A source-slide overlap and PP numbering continuation were found, fixed and re-verified.

## Release notes

- The current course page describes a two-hour assessment block, while the live v4 WA and v3 PP source papers each specify 90 minutes. This release preserves the live-paper durations (180 minutes total) as the assessment source of truth.
- Two legacy Drive files are owned by another account and cannot be moved into `archive/`; they remain in place with clearly older v11/v2 names. Current v12 artifacts are the selected publication targets.
