# PSI 2 - Let's hope for the best

## Setup (devcontainers)

This method does not require you to setup dependencies, so you don't have to worry about anything. VScode should ask you to open folder in container. Refer to [docs](https://code.visualstudio.com/docs/devcontainers/containers) if you need more help. Note: first build is quite lengthy - it installs entire texlive distribution.

## Setup (locally)

Here's the supported setup. Use devcontainer if you don't want to bother with all the setup:

1. Use VSCode
2. Install [LaTeX Workshop extension](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop)
3. Setup LaTeX (there are many ways to install, refer to [our template recommendations](https://github.com/LIKS/course_work_template_vu_mif_se))

## Working with LaTeX

- You don't work with LaTeX, you just write text and ask Google or Uncle GPT for some specific formatting help

- You don't write PlantUML directly in LaTeX (LaTeX compilation is too long for interactive editing)

- Use LaTeX extension pdf preview feature to check the pdf. Pdf will be regenerated after save. It takes about 10 seconds, so I suggest only checking it when necessary.

- Final project can be built using `make` command.
