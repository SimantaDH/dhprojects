# Simanta Nandi's Digital Humanities Portfolio

This repository holds my portfolio for the MA in Digital Humanities at IIT (ISM) Dhanbad, Department of Humanities and Social Sciences, Session 2026-27. It is a single web page that brings together four assignments, each with a short abstract, a screenshot, a little of the data and links to the full project.

**Live site:** https://simantadh.github.io/DH-IITISM/

## The four assignments

| No. | Project | Website | Repository |
|---|---|---|---|
| 01 | Extraction of Indian Flora and Fauna Elements Using RAG | [Visit](https://simantadh.github.io/rag_flora_fauna/) | [rag_flora_fauna](https://github.com/SimantaDH/rag_flora_fauna) |
| 02 | Bengali Stopwords: The Words We Read Past | [Visit](https://simantadh.github.io/bengalistopwords/#abstract) | [bengalistopwords](https://github.com/SimantaDH/bengalistopwords) |
| 03 | PressReady: An LLM Skill That Formats Research Manuscripts | [Visit](https://simantadh.github.io/skill/) | [skill](https://github.com/SimantaDH/skill) |
| 04 | Synthetic Reading: The Eyes Have It | [Visit](https://simantadh.github.io/syntheticreading/) | [syntheticreading](https://github.com/SimantaDH/syntheticreading) |

In brief:

1. **Flora and fauna by RAG.** I asked a small language model, Gemma 3 4B in AnythingLLM, to list the plants and animals in eight Indian literary texts in English. Only 19 of its 106 rows were fully correct, so I built a checked list of 509 entries by reading the texts myself.
2. **Bengali stop words.** A list of 317 romanised Bengali stop words, each with its Bengali spelling, an English gloss, a grammatical category and a register label. It is released as a Python module and as text, CSV and JSON files.
3. **PressReady.** A modular skill that teaches a language model the manuscript rules of Bloomsbury and Routledge. I turned 99 pages of guidelines into 632 rule statements across eleven Markdown files.
4. **Synthetic reading.** A reading of Ruskin Bond's "The Eyes Have It" in which interpretation comes first and a local model (qwen2.5:7b) only extracts phrases. Four claims were stated in advance and tested against the counts.

## Files in this repository

All files sit at the top level. There are no subfolders.

| File | What it is |
|---|---|
| `index.html` | The whole portfolio page. The styles and the small script are inside this file. |
| `a1-rag-audit.png` | Screenshot for Assignment 01: the audit chart. |
| `a2-bengali-stopwords.png` | Screenshot for Assignment 02: the category chart. |
| `a3-pressready-map.png` | Screenshot for Assignment 03: the map of the skill. |
| `a4-synthetic-reading-figures.png` | Screenshot for Assignment 04: the six result figures. |
| `README.md` | This file. |

The page needs no software, no build step and no outside libraries. It works in light and dark mode and on phones.

## Publishing with GitHub Pages

1. Upload all the files above to the main branch of this repository, at the top level.
2. Open **Settings**, then **Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
4. Choose the **main** branch and the **/ (root)** folder, then click **Save**.
5. Wait a minute or two and open https://simantadh.github.io/DH-IITISM/. If you still see the old version, refresh the page with Ctrl + F5.

To make a change later, edit `index.html` on GitHub (or upload a new copy) and commit it. The site updates by itself after a short wait.

## Adding another assignment

1. In `index.html`, copy one whole `<article class="assignment">` block, from its opening tag to `</article>`.
2. Paste it after the last assignment and change the title, abstract, links and visible work.
3. Set the `data-site` attribute on the new block to the project's website address.
4. Upload any new image to the top level of the repository and point to it by file name, for example `src="a5-new-project.png"`.

The script at the bottom of the page numbers the assignments and rebuilds the "On this page" list each time the page loads, so you do not need to edit the list by hand.

## Licence and credits

My own writing and code here are shared under the [Creative Commons Attribution-NonCommercial 4.0 International licence (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/). The four images are screenshots of my own project websites. Texts that are still in copyright, such as Hansda Sowvendra Shekhar's *The Adivasi Will Not Dance* and Ruskin Bond's "The Eyes Have It", are not included in any of my repositories and are quoted only briefly. PressReady is not affiliated with or endorsed by Bloomsbury Publishing or Taylor & Francis.

The full reference lists are on each project website, and a selected list is at the end of the portfolio page.

I am grateful to my supervisors, **Shanmugapriya T** and **Sourav Ghosh**, for their guidance on all four projects.

## Author

**Simanta Nandi**
MA in Digital Humanities, Department of Humanities and Social Sciences, IIT (ISM) Dhanbad
Email: 25ma0013@iitism.ac.in
Profile: [about.me/simantanandi](https://about.me/simantanandi)
GitHub: [SimantaDH](https://github.com/SimantaDH)
