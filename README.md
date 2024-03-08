# PSI 2 - Let's hope for the best

## Setup (devcontainers)

This method does not require you to setup dependencies, so you don't have to worry about anything. VScode should ask you to open folder in container. Refer to [docs](https://code.visualstudio.com/docs/devcontainers/containers) if you need more help. Note: first build is quite lengthy - it installs entire texlive distribution.

## Setup (locally)

Here's the supported setup. Use devcontainer if you don't want to bother with all the setup:

1. Use VSCode
2. Install [LaTeX Workshop extension](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop)
3. Setup LaTeX (there are many ways to install, refer to [our template recommendations](https://github.com/LIKS/course_work_template_vu_mif_se))
4. Ensure that [Inkscape](https://inkscape.org/) is in your PATH

## Working with LaTeX

- You don't work with LaTeX, you just write text and ask Google or Uncle GPT for some specific formatting help

- Use LaTeX extension pdf preview feature to check the pdf. Pdf will be regenerated after save. It takes about 10 seconds, so I suggest only checking it when necessary.

- Final project can be built using `make` command.

- Put references into `bibliografija.bib` file and use `\cite{}` when needed

- Use captions for every figure

Some helpful commands:

```latex
\subsection{}
\subsubsection{}
\subsubsubsection{}
\footnote{}
```

## Working with Draw.io

- We write valid UML with proper understanding of what arrows do what.

- We store diagrams in `lab2diags/` directory using `.drawio.svg` extension

- Use `\includesvg{}` to include svg in latex. Note: if diagram is huge use `\includesvg[width=\textwidth]{}`.
