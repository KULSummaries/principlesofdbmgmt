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

Er zal nu een nieuwe map verschijnen genaamd "helpFiles". De samenvatting zelf verschijnen als "Summary.pdf" in de root folder van het project.

Indien je make niet hebt, kan je texlive rechtstreeks aanroepen. Volgend commando zal dan je samenvatting creëren:
``` bash
pdflatex -jobname Summary.pdf main.tex
```

Dit commando zal je tweemaal moeten uitvoeren om alle referenties binnen het document juist te krijgen.
