# knplinks

Patient self-check links from **Kingsnorth Neuro Physiotherapy**, Ashford, Kent.

Free, structured screening tools that help patients describe a problem accurately to their GP, and help clinicians route it to the right place first time. Published as static HTML with no tracking, no analytics, no cookies and no form capture.

**Live site:** https://potamv01.github.io/knplinks/

## What's here

| Path | Tool | Audience |
|---|---|---|
| `/index.html` | Landing page listing the available tools | Everyone |
| `/ear-balance/index.html` | Midlife ear and balance screening checklist | GPs, menopause practitioners, patients aged ~40–65 |
| `/social-card.png` | Link preview image used by LinkedIn, Facebook and X | — |

### Midlife ear and balance checklist

A five-minute structured screen for adults with ear fullness, pressure, autophony, dizziness or unsteadiness. It:

- screens red flags first, and refuses to let the classifier override them
- separates **obstructive** Eustachian tube dysfunction from **patulous** Eustachian tube dysfunction, which present similarly but need opposite management
- routes balance symptoms by episode duration and trigger, following the Bárány Society International Classification of Vestibular Disorders
- states when blood tests are worth checking, and is explicit that no supplement treats Eustachian tube dysfunction
- switches between a clinician view and a plain-English patient view of every question
- prints to a clean PDF and produces a copy-and-paste summary for the notes

Built as a single self-contained HTML file. No build step, no dependencies except Google Fonts, works offline once loaded.

## Editing

Each tool is one HTML file with its CSS and JavaScript inline. Open it, edit, commit. There is nothing to compile.

When changing clinical content, update the version number and review date in the footer of the tool, and keep the scope-and-limits and declaration paragraphs intact.

## Sources

Clinical content is drawn from the Bárány Society ICVD consensus documents, ENT UK and NICE referral guidance, the validated ETDQ-7 patient-reported measure, and peer-reviewed literature on patulous Eustachian tube, Ostmann fat pad change with age, and vitamin D status in BPPV recurrence. Full references are listed in the footer of each tool.

## Important

These are screening aids, **not diagnostic tests**. Symptom weightings reflect clinical discriminating value and are not a validated scoring system. Nothing here replaces otoscopy, tympanometry, audiometry, positional testing or clinical examination, and nothing here should delay assessment of a red flag.

No supplement, device or branded product is recommended anywhere in this repository.

## Licence

Code is MIT licensed (see `LICENSE`). Clinical content is free to print, share and use in practice with attribution to Kingsnorth Neuro Physiotherapy.

Contact: 01233 222444 · https://www.knneurophysiotherapy.co.uk/
