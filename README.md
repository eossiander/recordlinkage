# recordlinkage
programs to demonstrate record linkage with machine learning on public health data

This repository includes several programs that illustrate the process I used to create a hospitalization revisit file for Washington State hospitalizations, Washington State linked hospitalization/death files, and a linked birth defects/birth file.

The epi brown bag presentation is in **epiBB.html**; you may view this in a browser by copying the link for the file, then visiting this page: http://htmlpreview.github.io/, and pasting the link into the box provided there.

Other files:
- **BDSSlink_2014.Rnw:** text file showing the SAS and R code I used to link data from the birth defects surveillance system to the birth file.
-  **DIHDmethod.Rnw:** text file with SAS and R code I used to create linked hospitalization/death (DIHD) files.
-  **ExpandedLinks.Rnw:** also includes SAS and R code to create the larger-than-DIHD files that link each year of deaths to additional years of hospitalizations.
-  **DIHDmethod.pdf:** PDF file describing the process of creating the DIHD files
-  **DIHDmethod_detail.pdf:** PDF file including all the details, including the SAS and R code, from DIHDmethod.Rnw.
-  **Revisit.Rnw:** text file with SAS and R code I used to create the hospitalization revisit file, in which each person's hospitaliztions are linked to each other.
-  **revisit.pdf:** same information in a pdf file

 


