# book-makefile
This repository is a baseline Makefile for driving LaTex and other tools to compile digitial versions of books (PDF, Epub, MS Word)

# Installation / Dependencies
On Windows, install the following (winget)
MiKTeX.MiKTeX
StrawberryPerl.StrawberryPerl
ezwinports.make

After installing MikTeX, run miktex-console.exe . In the Updates tab, proactively check for updates. Failing to do so will cause LaTeX to fail on the first run. Then, go to Settings and select "Always" for "You can choose whether missing packages are to be installed automatically". This will help the runs work without pausing the compilation for package dependencies