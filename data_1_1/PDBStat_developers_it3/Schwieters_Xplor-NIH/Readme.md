Here please find the following:

\<TargetID\>_Xplor-NIH_it1.nef    - NEF files obtained by reading the given
                                  NEF file to Xplor-NIH-native format
                                  writing the data back out.
\<TargetID\>_Xplor-NIH_\<TYPE\>.tbl - NEF restraints in Xplor-NIH
                                  format. \<TYPE\> is distance, dihedral,
                                  rdc_1 or rdc_2.


A refinement calculation was then performed on the coordinates given
in each of the input .cif files. The resulting lowest energy
structures are provided with filename:

   \<TargetID\>_Xplor-NIH_lowest.cif

The Xplor-NIH script which generated this structure is in filename

   \<TargetID\>_Xplor-NIH_refine.py

This script requires Xplor-NIH version 3.1.2

The corresponding Xplor-NIH structure statistics file is in filename

   \<TargetID\>_Xplor-NIH_refine.stats

In these calculations, there was no modification to the NEF data, so
no changed NEF files were written.