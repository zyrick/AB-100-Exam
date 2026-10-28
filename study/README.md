# AB-100 Fast Study Guide

## What's ready
- `study/ab100-question-bank.json` — 120 parsed unique questions from the three saved HTML pages (source numbers 1–120).
- 86 multiple-choice, 22 hotspot, 11 drag/drop, and 1 ordering.
- 33 questions and 33 source answer blocks use images. These require visual review; **do not assume an image answer is validated because its file path exists**.
- All supplied answers are **unverified**; treat as practice material, not an official Microsoft answer key.
- Original saved HTML and image folders are left intact.

## Fastest study sequence
1. **First pass: 4 batches of 30 questions.** Read each question, predict your answer before exposing the source answer, and record a result (Correct / Incorrect / Uncertain). For hotspot/drag-drop/image questions, examine the original image and matching answer image.
2. **Explanation, not memorization.** For any incorrect or uncertain item, write a one-sentence rule identifying the deciding requirement and why the closest distractor fails.
3. **Review mistakes only.** Retry missed/uncertain items without seeing the answer; study official Microsoft Learn documentation for contested or confusing answers.
4. **Mixed mock exam.** Shuffle questions across all three topics; target 85%+ on verified, non-ambiguous practice items before considering the bank mastered.
5. **Final revision.** Focus on Microsoft service comparisons, governance/security, knowledge retrieval, orchestration/tools, telemetry/evaluation, deployment and lifecycle.

## Keep your study records
In your chat, use this response format for each question: `Q54: C | certain` or `Q54: B | unsure`. Ask ChatGPT to track correctness, missed concept, and retest due.
When referencing images, use the path in `question_images`/`answer_images` relative to the repo, or refer to the original HTML page.

## Suggested interactive ChatGPT prompt

> Use my GitHub repo `zyrick/AB-100-Exam` and the file `study/ab100-question-bank.json`. Quiz me on questions 1–30, one question at a time. Do not reveal the answer before I respond. Track my response and confidence. After each response, explain the best answer, why alternatives are wrong, and flag unverified or image-dependent answers. Keep my wrong and uncertain answers for spaced repetition. Do not guess at image content; fetch the source image or state that it must be reviewed.

## Coverage notes
- Topic 1 — Plan AI-powered business solutions: 44
- Topic 2 — Design AI-powered business solutions: 30
- Topic 3 — Deploy AI-powered business solutions: 46
- Files 1, 2, 3: questions 1–50, 51–100, 101–120.
