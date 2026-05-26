# AI Scientist &mdash; EMNLP 2026 Tutorial

Project site for the EMNLP 2026 cutting-edge tutorial:

**AI Scientist: Language Model Agents for End-to-End Research Workflows**

A three-hour tutorial that organizes the rapidly growing AI Scientist landscape (Biomni, AI-Researcher, AI co-scientist, Kosmos, SciMaster, MiroFlow, OAgents, Tongyi DeepResearch, Karpathy's `autoresearch`, and the recent benchmarks ResearchGym, ResearchClawBench, Scientist-Bench, LAB-Bench, BMMR, LabUtopia) around the **end-to-end research workflow**: foundations, idea generation and grounding, coding and experimentation, analysis and writing, evaluation and reliability, and safety and human oversight.

## Organizers

- [Wanghan Xu](https://black-yt.github.io/) &mdash; Shanghai Jiao Tong University / Stanford
- [Zhenfei Yin](https://yinzhenfei.github.io/) &mdash; University of Oxford
- [Yingcheng Charles Wu](http://charles-wu.com) &mdash; Stanford University
- [Philip Torr](https://eng.ox.ac.uk/people/philip-torr) &mdash; University of Oxford

Contact: `ai-scientist-tutorial@googlegroups.com`

## Local Preview

```bash
python3 -m http.server 4322
# then open http://localhost:4322
```

The site is a static HTML/CSS/JS bundle &mdash; Bootstrap, AOS, and Bootstrap Icons are loaded from a CDN, so no build step is required.

## Structure

```
.
├── index.html
├── assets/
│   ├── css/style.css       # base layout
│   ├── css/site.css        # tutorial-specific overrides
│   ├── js/main.js          # nav, scroll, AOS init
│   └── img/
│       ├── background_san_fancisco.jpg
│       ├── about-bg.jpg
│       ├── organizers/     # organizer headshots / placeholders
│       └── others/         # favicon
```

## Deployment

This site is deployed via GitHub Pages from the `main` branch of
[`yyifan-Onyen/ai_scientist`](https://github.com/yyifan-Onyen/ai_scientist) at
<https://yyifan-onyen.github.io/ai_scientist/>.

Push to `main`, then enable GitHub Pages in the repository settings
(Source: `Deploy from a branch`, Branch: `main`, Folder: `/ (root)`).
