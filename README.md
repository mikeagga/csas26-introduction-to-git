## Introduction to Git

Workshop for CSAS 2026 by Michael Agostino

This workshop aims to provide what you need to get started with Git so that you
can use it in your own projects. Git is a complicated and mature command-line
utility, so I cannot cover all of its functionality in my allotted time. For
this reason, I have opted to cover what I deem the most important information
for building a fundamental understanding of Git and empowering participants to
manage their own projects.

Topics to expect
 
- A brief history of Git and its significance.
- Set up
- Configuration
- Core functionality
- A brief overview of how Git works.
- Branching
- GitHub basics

This workshop teaches core concepts through real-world examples and active
participation. Important commands, ideas and best practices will be reinforced
through repetition. 

This workshop is intended for beginners; those with limited experience using Git
in their own projects. Most follow-along instructions will require command line
usage, since Git is a command line utility. I understand that many beginners may
not feel comfortable with the command line. However, I believe a basic
understanding of it is valuable in any computing-related field. Therefore, this
workshop also serves as a starting point for those interested in developing
their command line skills through real examples and usage.

---

## Rendering

This presentation was created using [Quarto](https://quarto.org/) and renders to:
1. Slides using [reveal.js](https://revealjs.com/).
2. PDF as default which is set to [latex](https://www.latex-project.org/).

Use the following to render in all formats:

```bash
quarto render presentation.qmd
```

Use the following to render slides as `.pdf` only:

```bash
quarto render presentation.qmd --to pdf
```

Use the following to render to slides exclusively as `.html` using reveal.js:

```bash
quarto render presentation.qmd --to revealjs
```
