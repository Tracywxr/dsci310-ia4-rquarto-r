## DSCI 310 individual assignment on Quarto reproducible reports using R

This is a template repository 
for the individual assignment on Quarto reproducible reports using R
from the DSCI 310 (Trustworthy workflows for data science) course.
Instructions for this assignment can be found on the DSCI 310 course website 
[here](https://ubc-dsci.github.io/dsci-310-student/individual_assignment4).

### Dependencies

To complete this assignment you will need to install:
- GNU Make
- Quarto
- R programming language
- R packages:
  - `knitr`
  - `tidyverse`
  - `tinytex`

### License:
The non-software content of this template repository is licensed under the 
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0) License](https://creativecommons.org/licenses/by-nc-sa/4.0/). 
The software content of this template repository licensed under the [MIT License](https://spdx.org/licenses/MIT.html). See the [license file](LICENSE.md) for more information.

### PDF error
```bash

Rendering PDF
running xelatex - 1
  This is XeTeX, Version 3.141592653-2.6-0.999996 (TeX Live 2024) (preloaded format=xelatex)
   restricted \write18 enabled.
  entering extended mode
  
updating tlmgr

updating existing packages
finding package for scrartcl.cls
ERROR: Your TexLive version is not updated enough to connect to the remote repository and download packages. Please update your installation of TexLive or TinyTex.

Underlying message: Local TeX Live (2024) is older than remote repository (2025).
Cross release updates are only supported with
  update-tlmgr-latest(.sh/.exe) --update
See https://tug.org/texlive/upgrade.html for details.


Stack trace:

Underlying message: Local TeX Live (2024) is older than remote repository (2025).
Cross release updates are only supported with
  update-tlmgr-latest(.sh/.exe) --update
See https://tug.org/texlive/upgrade.html for details.

    at findPackages (file:///Applications/quarto/bin/quarto.js:83966:27)
    at eventLoopTick (ext:core/01_core.js:175:7)
    at async findAndInstallPackages (file:///Applications/quarto/bin/quarto.js:84812:30)
    at async initialCompileLatex (file:///Applications/quarto/bin/quarto.js:84704:39)
    at async generatePdf (file:///Applications/quarto/bin/quarto.js:84647:22)
    at async Object.complete (file:///Applications/quarto/bin/quarto.js:84929:27)
    at async file:///Applications/quarto/bin/quarto.js:78314:31
    at async withTimingAsync (file:///Applications/quarto/bin/quarto.js:16879:25)
    at async Object.complete (file:///Applications/quarto/bin/quarto.js:78307:13)
    at async Object.onPostProcess (file:///Applications/quarto/bin/quarto.js:85808:36)
make: *** [reports/qmd_example.pdf] Error 1
```