# Contribution to the Italian Metabolomics Network General Meeting 2023

This repository contains the code and [presentation](https://github.com/mar-garcia/IMN2023/blob/main/IMN2023_slides.pdf) 
of my contribution to the
[Italian Metabolomics Network General Meeting 2023](http://metabonet.it/general_meeting_2023/).  
  
Original files of data showed in the presentation are available 
on MetaboLights ([MTBLS5261](https://www.ebi.ac.uk/metabolights/MTBLS5261)),
whereas the source code is in the file 
[`"code.Rmd"`](https://github.com/mar-garcia/IMN2023/blob/main/code.Rmd) of this repository.

## Abstract

### Boosting annotation confidence in untargeted lipidomics experiments by the use of complementary chemical properties

Liquid chromatography-mass spectrometry is currently the predominant
analytical technique in the field of lipidomics. However, even coupling
high mass resolution spectrometers with extensive reference libraries,
limitations on the annotation phase still persist. In fact, it has been
demonstrated that an unambiguous annotation cannot be obtained even
relying on m/z and fragmentation experiments ([Köfeler et al. Nat
Commun.
2021;12:4771](https://www.nature.com/articles/s41467-021-24984-y)).
Misannotations can have dramatic consequences in the biological
interpretation stage, in particular in systems - as plants or
microorganisms - where it is not uncommon to find nonstandard lipid
classes. Embedding retention time information in the annotation pipeline
represents an important step not only to reduce false annotations, but
also to expand the annotation capacity to those features for which it is
not possible to get the fragmentation patterns. In this contribution we
present an R pipeline which can be used to perform high-confidence
accurate lipid identification, combining various types of complementary
chemical properties. To illustrate the proposed approach we use the
grape lipidome as proof of concept ([Garcia-Aloy et al. Food Chem.
2023;410:135360](https://www.sciencedirect.com/science/article/pii/S0308814622033222)).
The application of this workflow to the analytical data allowed a 60%
reduction of potential erroneous annotations by considering how each
lipid class is ionised, the MS/MS spectras and by the use of retention
time dependencies plots. In the contribution, we will also emphasize the
usefulness of relying on analytical standards to identify class specific
analytical patterns/trends. With the application of the suggested
pipeline to the mentioned dataset we also demonstrate how it is possible
to spot less explored lipid classes or even new potential ones.
