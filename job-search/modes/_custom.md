# Custom Instructions -- career-ops

<!-- ============================================================
     THIS FILE IS YOURS. It will NEVER be auto-updated.

     Put your own house rules, custom workflows, and automations
     here -- anything you want the agent to ALWAYS do (or never do).

     This is for PROCEDURAL rules ("HOW I want things done").
     For WHO you are (archetypes, narrative, comp, negotiation),
     use modes/_profile.md instead. Keeping the two separate keeps
     each one readable.

     The agent reads this file alongside the system instructions;
     your rules here take precedence over the defaults, as long as
     they don't break the Data Contract (your files are never
     touched, and we never auto-submit an application for you).

     Because this is a user-layer file, anything you write here
     survives `node update-system.mjs`. Put customizations HERE,
     not in CLAUDE.md / modes/_shared.md / other system files --
     those get overwritten on update.
     ============================================================ -->

## House Rules

<!-- Rules the agent should always follow. -->

- Talk to Silvio in **Italian** (chat summaries, shortlists, explanations). Reports in `reports/` stay in English so they can be reused.
- Tailored CVs and cover letters are written in the **language of the job posting**: German JD → German, English JD → English, French JD → English unless asked.
- German level: never write "C1" or "fluent/fliessend". Use "German: daily working language since 2022 (fide B1, 2023)" / "Deutsch: tägliche Arbeitssprache seit 2022 (fide B1, 2023)".
- Never name the internal BAZG customs field app (keep it as "internal mobile app for customs officers").
- Notice period: 3 months to the end of a month (Kündigungsfrist: 3 Monate auf Monatsende). Earliest start = end of the month in which notice is given + 3 months.

## Custom Workflows

<!-- Multi-step routines you run often, given a short name. Examples:
     - "weekly review": scan my saved portals, evaluate the new roles,
       then give me a one-paragraph summary of the top 3.
     - "prep <company>": pull the JD, generate STAR stories from
       article-digest.md, and draft 5 likely interview questions. -->

(none yet -- add yours above)

## Output Preferences

- Shortlists: one table with company, role, place, remote/hybrid, salary if known, score, link. Best first.
- Swiss salaries: always say whether a figure is at 100% and whether it includes the 13th salary.

## Off-Limits

<!-- Things the agent must never do for you. Examples:
     - Never auto-fill or submit an application without showing me first.
     - Never edit a system file to customize my setup -- put it here. -->

(none yet -- add yours above)
