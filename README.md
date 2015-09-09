# Automatic LaTeX Build System Template
This file is based on the ALBS Template by __Christopher Batten__ - for details please refer to the original [README file](README).

~ Zafar Takhirov

## Motivation
The motivation behind this build is to create a long time support for automated LaTeX build system. The original coyright files ar __not__ to be modified.

This is a template for the Automatic LaTeX Build System. Please refer to
'albs-uguide.txt' for more information on the build system. Writers
should eventually replace the 'README' file with information on their
new project if they are going to generally distribute the LaTeX source
code. It is recommended that the new 'README' file keep a pointer to
'[albs-uguide.md](albs-uguide.md)'. You may also want to keep the version
information around so that you know what version of the build system you are
using.

## Template Setup
For detailed setup guide, please, refer to [albs-uguide.md](albs-uguide.md).

 - Update the project metadata (name, version, etc) in '[configure.ac](configure.ac]'
 - Run 'autoconf' in project's root directory
 - Rename [src/albs.tex](src/albs.tex) to abbreviated form of project name (with .tex)
 - Rename [src/albs.bib](src/albs.bib) to abbreviated form of project name (with .bib)
 - Change \bibliography{} in the toplevel .tex file appropriately


## Build Steps

```shell
mkdir build
cd build
../configure
make
```

## Acknoledgements
* This file is based on the ALBS Template by __Christopher Batten__ - for details please refer to the original [README file](README).
* The table of contents is generated with [DocToc](https://github.com/thlorenz/doctoc)

## Revision history
| Version | Description		                                  |
| :------ | :-------------------------------------------------|
| 1.0.0   | Original template by Christopher Batten is stable |

