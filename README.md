# The Hidden Cost of the Cloud

This was an argumentative essay on the environmental footprint of data centers that I revised in plain text with Markdown, Pandoc, and Git.

## About the essay

I wrote the first version of this essay in 2025 as a computer science student at Loyola University Chicago.
The main purpose was to argue that the energy and water demands of data centers, accelerated by generative AI, have become an environmental threat. Also that a sustainable cloud requires stricter efficiency regulations, more renewable energy, and independently verified environmental reporting.

## Files

| File | Purpose |
| --- | --- |
| `the-hidden-cost-of-the-cloud.md` | The essay in Pandoc Markdown. This plain-text file is the source of truth. |
| `cited-items.json` | Bibliographic data for every cited source, in CSL JSON. |
| `apa.csl` | The APA 7th edition citation style from the Citation Style Language project. |
| `.gitignore` | Keeps generated Word files out of version control. |

## Building the essay

With Pandoc installed, run this from the repository folder:

    pandoc the-hidden-cost-of-the-cloud.md --citeproc -o the-hidden-cost-of-the-cloud.docx

Pandoc reads the title, author, date, abstract, bibliography, and citation style from the metadata block at the top of the Markdown file. It then formats the citations and reference list in APA style.

## How I revised it

I tried to commit each part of the process step by step

- **Conversion and structure.** I converted my original Word document to Markdown with Pandoc and then moved the title and author and abstract into metadata,
- **One sentence per line.** Each sentence sits on its own line
- **Citations as data.** I replaced hard coded citations with citation keys linked to a CSL JSON bibliography this is so the reference list is generated automatically and the citation style can be changed with one line.
- **Quotations.** revised each quote so it is introduced into my own sentence and followed by commentary.
- **Argument and style.** i tried to mark the context, problem, and claim in my introduction and added significance and future research to my conclusion. Also revised a body paragraph for clarity. Did the read aloud also for spelling and grammer.
- **Checking my work.** I generated test Word files with Pandoc to catch formatting problems and fixed them in the Markdown source.

## Skills demonstrated

Version control with Git and GitHub
Document conversion with Pandoc
Citation management 
Writing in Markdown
Structured revision of an academic argument.

## AI Usage

I used Claude to help with Git setup and to suggest some revisions.
Also with the citations when I got stuck.