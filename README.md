# Demo Authoring Space with Continuous Deployment

This repository houses an example workflow that allows for continuous deployment of Quarto documents that have been augmented by Quarto Extensions like [`{quarto-webr}`](https://github.com/coatless/quarto-webr) and [`{quarto-pyodide}`](https://github.com/coatless-quarto/pyodide). Feel free to clone or fork the repository!

## Authoring Workspaces

We use [`devcontaienrs`]() to create two authoring workspaces that work with [GitHub Codespaces](). 

### VS Code 

If you are comfortable with VS Code, you can try out the Codespace by clicking on the following button:

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/coatless-quarto/quarto-webr-pyodide-demo?devcontainer_path=.devcontainer%2Fvs-code%2Fdevcontainer.json)

### RStudio

Unfortunately, there isn't an option to offer RStudio directly in GitHub Codespaces. So, the following link will initially use VS Code that will  RStudio augmented instance by clicking: 

[![Open RStudio Authoring Workspace in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/coatless-quarto/quarto-webr-pyodide-demo?devcontainer_path=.devcontainer%2Frstudio%2Fdevcontainer.json)

Unfortunately, there isn't an option to offer RStudio without going through VS Code in GitHub Codespaces. So, the following link will first load the VS Code editor and, then, automatically launch the process. 

Please click on the "Ports" tab and, then, select the global next to the `rserver` process to be taken into a web-based version of RStudio.


**Note:** Codespaces are available to Students and Teachers for free [up to 180 core hours per month](https://docs.github.com/en/education/manage-coursework-with-github-classroom/integrate-github-classroom-with-an-ide/using-github-codespaces-with-github-classroom#about-github-codespaces) through [GitHub Education](https://education.github.com/). Otherwise, you will have [up to 60 core hours and 15 GB free per month](https://github.com/features/codespaces#pricing).

