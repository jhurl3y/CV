### Overview

This is my current up to date CV built with [LaTeX](https://www.latex-project.org/). Although usually used for technical and scientific documentation, [LaTeX](https://www.latex-project.org/) is handy for fitting a lot of information onto one page, hence pretty good for producing a nice CV. Feel free to take the code, modify it, use it as you please.

### Setup

This is how I build a ready to go PDF using the tex files - I am using OSX + VSCode.

1. Download and install LaTeX [here](https://www.latex-project.org/get/).
2. Add the installation to your PATH:
   - Make sure the `/Library/TeX/texbin` path exists.
   - Run `sudo vim /etc/paths` and add `/Library/TeX/texbin` to the end of the file. Make sure to save.
   - Run `echo $PATH` and confirm your changes took effect.
3. Download the following [VSCode extension](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop).
   - Add `"latex-workshop.latex.outDir": "../out/"` to your `settings.json`
   - Restart VSCode.
4. Open `cv.tex`, type `CMD SHIFT P`, and click _LaTeX Workshop: Build LaTeX project_.
5. The output files and pdf will be located in `/out`.
