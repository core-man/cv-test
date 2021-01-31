# Jiayuan Yao's Curriculum Vitae

These are the LaTeX sources for my academic CV.

## Preview

Preview my CV:

- [English version](en/cv.pdf)
- [Chinese version (中文版)](cn/cv.pdf)

## Build

To build the CV, you need to have LaTeX installed. The full LaTeX distribution
(e.g., TeXLive on Linux, and MacTeX on macOS) are usually very big (>5 GB),
thus I recommend to install the lightweight [TinyTeX](https://yihui.org/tinytex/)
(< 100MB).

1. 	Install TinyTeX:

		curl -sL "https://yihui.org/tinytex/install-bin-unix.sh" | sh

2. 	Install LaTeX packages needed by the CV template:

        tlmgr install anyfontsize ctex everysel datetime enumitem etaremune fancyhdr \
                        fmtcount geometry hyperref sourcesanspro sourcecodepro xcolor

3. 	Build the CV:

		make

## Acknowledgemnt

The CV templates are modified from https://github.com/leouieda/cv
and https://github.com/seisman/cv.
