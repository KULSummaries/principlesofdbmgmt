# Samenvatting Principles of Database Management
[![PDF Status](https://www.sharelatex.com/github/repos/KULSummaries/principlesofdbmgmt/builds/latest/badge.svg)](https://www.sharelatex.com/github/repos/KULSummaries/principlesofdbmgmt/builds/latest/output.pdf)

Dit is een samenvatting voor het vak "Principles of Database Management" aan de KUL.


## Downloading the Summary
You can easily download the summary [here](https://www.sharelatex.com/github/repos/KULSummaries/principlesofdbmgmt). Just click the big green button saying "download pdf" and your download will start.

In case you want to build the summary from source you'll need a few things:
* [git](http://www.git-scm.com/)
* [texlive](https://www.tug.org/texlive/)
* ([make](https://www.gnu.org/software/make/))

Linux and OSX users can open a terminal and enter following commands:

``` bash
cd /your/preferred/directory
git clone https://github.com/KULSummaries/principlesofdbmgmt
cd principlesofdbmgmt/
```

In case you have make installed on your system you can now just type:

```bash
make
```

a new folder called "helpFiles" will appear. The summary itself will appear too in the root folder of the project and is named "Summary.pdf".

In case you don't have make installed, you can call texlive directly from the commandline. Following command will create the summary:

``` bash
pdflatex -jobname Summary.pdf main.tex
```

Execute this command twice to make sure all references in the summary are displayed correctly.
