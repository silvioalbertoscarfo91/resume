# job-search

Data for [career-ops](https://github.com/career-ops-hq/career-ops) (main CLI). This
folder is the career-ops **data root**: it holds only the user layer (CV, profile,
portals, tracker, reports). The career-ops code is not committed here.

## Use it in a new session

```bash
git clone --depth 1 https://github.com/career-ops-hq/career-ops.git
cd career-ops && npm install --ignore-scripts
echo /absolute/path/to/resume/job-search > .career-ops-data
node doctor.mjs --json      # should say onboardingNeeded: false
```

Then run Claude Code inside `career-ops/` and use the modes (`scan`, paste a job URL, `pdf`, `tracker`...).

## Files

| File | What |
|------|------|
| `cv.md` | Canonical CV, built from the GitHub resume (`../index.html`) |
| `config/profile.yml` | Contacts, targets, CHF 130K floor, location policy |
| `modes/_profile.md` | Archetypes, framing, location and German-language policy |
| `modes/_brief.md` | Compact triage brief |
| `modes/_custom.md` | House rules (Italian chat, JD-language CVs, German wording) |
| `portals.yml` | Swiss companies + search queries |
| `data/pipeline.md` | Inbox of postings to evaluate |
| `data/applications.md` | Application tracker |
