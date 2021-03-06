# Welcome to ACPYPE! #

_**ACPYPE source code moved to CCPN repository at http://ccpn.svn.sourceforge.net/svnroot/ccpn/branches/stable/ccpn/python/acpype**_

A tool based on Python to use **Antechamber** to generate topologies for chemical compounds and to interface with others python applications like [CCPN](http://www.ccpn.ac.uk) tools or [ARIA](http://aria.pasteur.fr).

**acpype** is pronounced as "_ace + pipe_".

Topologies files to be generated so far:
CNS/XPLOR, GROMACS, CHARMM and AMBER.

Latest version of  **ANTECHAMBER** can be found in [AmberTools 14](http://ambermd.org/#AmberTools).

NB: Topologies generated by **acpype/Antechamber** are based on General Amber Force Field (GAFF) and should be used only with compatible force fields like AMBER and its variants.

Several flavours of AMBER FF are ported already for GROMACS (see [ffAMBER](http://ffamber.cnsm.csulb.edu)) as well as for XPLOR/CNS (see [xplor-nih](http://ambermd.org/xplor-nih.html)) and CHARMM.

Please, read **[ACPYPE Wiki pages](http://code.google.com/p/acpype/w/list)** for more information.

To download ACPYPE, do this:

```
svn checkout http://ccpn.svn.sourceforge.net/svnroot/ccpn/branches/stable/ccpn/python/acpype acpype
```

And learn a bit about SVN so you can always keep your ACPYPE up-to-date.

## It was inspired by and to whom I acknowledge: ##

  * **[amb2gmx.pl](http://ffamber.cnsm.csulb.edu/tools.html)** by Eric Sorin, David Mobley and John Chodera;

  * Elmar Krieger's **[YASARA Autosmiles](http://www.yasara.org/autosmiles.htm)**;

  * **[topolbuild](http://www.gromacs.org/@api/deki/files/93/=topolbuild1_3.tgz)** by Bruce Ray;

  * **[xplo2d](http://xray.bmc.uu.se/hicup/faq.html)** by G.J. Kleywegt.

## If you use ACPYPE, please cite: ##

SOUSA DA SILVA, A. W. & VRANKEN, W. F. ACPYPE - AnteChamber PYthon Parser interfacE. BMC Research Notes 2012, 5:367 doi:10.1186/1756-0500-5-367
http://www.biomedcentral.com/1756-0500/5/367

## For Antechamber, please cite: ##

  1. J. Wang, W. Wang, P.A. Kollman and D.A. Case. "Automatic atom type and bond type perception in molecular mechanical calculations". Journal of Molecular Graphics and Modelling, 25, 247-260 (2006).
  1. [J. Wang, R.M. Wolf, J.W. Caldwell, P.A. Kollman and D.A. Case. "Development and testing of a general AMBER force field". Journal of Computational Chemistry, 25, 1157-1174 (2004)](http://ambermd.org/antechamber/gaff.pdf).