---
name: xiaohongshu-creator-workflow
description: "Turn a user's experience, notes, or source materials into a polished Xiaohongshu post, create or prepare supporting visuals, and assist with uploading a reviewable draft or publishing when explicitly requested."
---

# Xiaohongshu Creator Workflow

Use this skill when the user wants help planning, writing, illustrating, uploading, or publishing a Xiaohongshu post. The result should sound like the user's real experience, be easy to scan on a phone, and be ready for the user to review.

## 1. Establish the source of truth

- Gather the user's stated facts and any supplied notes, screenshots, documents, or photos. Inspect provided sources when the requested content depends on them; do not claim to have read a file that was not accessible.
- Separate confirmed facts, the user's opinions, and suggestions or inferences. Do not invent dates, costs, outcomes, dialogue, services, or other people's actions to make a story more compelling.
- If sources conflict, flag the discrepancy and prefer the primary record the user designates. For travel, visa, medical, legal, financial, or other consequential topics, avoid turning one person's experience into a universal rule; distinguish personal experience from official requirements and verify current rules when needed.
- Keep private identifiers out of public copy and image assets by default: document numbers, application IDs, barcodes, email addresses, phone numbers, home/work addresses, faces, QR codes, receipts with identifying details, and private correspondence. Redact source images before using them. Do not upload source files to third-party services unless the user requested that workflow.

## 2. Shape the post

- Match the user's requested voice and audience; keep first-person claims in first person and do not overstate expertise.
- Build a clear opening hook, short scannable sections, practical details, and a modest closing. Prefer concrete sequence and lessons learned over generic clickbait.
- Before drafting, define the scope the user asked to tell (for example, the whole renewal journey versus only the latest interview outcome). Reconstruct the chronology from the earliest relevant step through the requested endpoint using available source material; do not let the newest or most dramatic event crowd out earlier decisions, failed attempts, delays, costs, or changed plans that materially explain what happened.
- When the user refers to emails, inspect the connected/local mail source only if it is actually available. If it is not, say so plainly and use only messages or facts already supplied in the conversation; do not imply an inbox search succeeded.
- Prepare a concise title, body, relevant topic tags/hashtags, and an optional longer source draft. Check the current creator UI's title/body limits instead of assuming limits are fixed.
- When the topic is procedural, organize around what happened, what the user actually did, what was required by a notice or official source, and what remains uncertain. Label unofficial services and personal fees as such.
- Prepare an upload checklist or publication note only when it helps the user; don't create redundant files by default.

## 3. Prepare visuals

- Choose a visual format that serves the content: a cover plus a small sequence of cards for step-by-step stories, or a few clean photos for experience-based posts. Avoid decorative images that could be mistaken for documentary evidence.
- Use the image-generation skill for a genuinely new bitmap illustration or image edit; use document/design tools suited to the requested artifact otherwise. Keep card text brief, legible at phone size, consistent, and faithful to the source.
- Proofread every rendered card and check order, crop, contrast, spelling, and identifiers. Provide a cover/preview and final files in an easy-to-find location. Do not claim visual review unless the assets were actually inspected.

## 4. Upload and publish

- Prefer the official creator interface or an available purpose-built integration. If interacting with the site UI, follow the available browser skill and use the user's existing signed-in session; never request or expose their password, inspect browser storage, or bypass access controls.
- Upload the assets in intended order, then confirm the visible count and preview. Fill title, body, and topics/tags, and check that line breaks, emoji, and hashtags survived entry. Keep a local copy of the final caption and assets when practical.
- Before publication, review the exact title, body, tags, image order, audience/visibility, and any disclosure or location settings. Publish only when the user explicitly requested publishing and the final content matches the reviewed draft. A request to prepare or upload a draft is not permission to publish.
- If a UI control fails, a confirmation step is unclear, or the page may have already submitted, stop. Do not invoke hidden endpoints, inject page scripts, or retry blindly. Report whether anything was published and leave the user a clear next step.
- After a successful publish action, confirm the resulting post/status in the UI if possible. Never report success based only on clicking a button or seeing a spinner.

## 5. Handoff

Summarize what was prepared, where the files are, and whether the post is a draft, published, or blocked. State any remaining user action plainly. Keep the handoff concise and don't repeat the full post unless the user asks for it.
