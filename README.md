# cltex

remove TeX auxiliary/intermediate files

## Properties

|key|value|
|-:|:-|
|  script:|cltex|
|   short:|remove TeX auxiliary/intermediate files|
|    type:|bash|
|  author:|Wybo Dekker|
|   email:|[wybodekker@me.com](mailto:wybodekker@me.com)|
| version:|0.02|
| license:|GNU General Public License|
|   intro:|cltex removes tex auxiliary/intermediate files for all|
|         |TeX (|.tex, .dtx| and **.ltx**) files in the current|
|         |directory. With the **--all** option, pdf, ps and dvi|
|         |files are also removed. Files are removed from the|
|         |given directory, the current directory by default.With|
|         |the **--recursive** option, files are removed from|
|         |subdirectories, too.|

## Options

|option|description|
|:-|:-|
|-h,--help	|print short help and exit|
|-H,--Help	|print full documentation and exit|
|-V,--version	|print version and exit|
|-v,--verbose	|run verbosely|
|-a,--all	|include pdf, dvi and ps files|
|-d,--dryrun	|do a dry run: show what would be removed|
|-r,--recursive	|remove file recursively|
