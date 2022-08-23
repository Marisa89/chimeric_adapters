
This folder contains the data and scripts used in "Identification and quantification of chimeric sequencing reads in a highly multiplexed RAD-seq protocol" 

Maria Luisa Martin Cerezo 1,2, Rohan Raval 1, Bernardo de Haro Reyes 1, Marek Kucka 3,Yinguang Frank Chan 3 and Jarosław Bryk 1

1-Department of Biology, School of Applied Sciences, University of Huddersfield, Queensgate, Huddersfield, England, United Kingdom 

2-AVIAN Behavioural Genomics and Physiology, IFM Biology (IFM), Linköping University, Linköping, Sweden 

3-Friedrich Meschier Laboratory of the Max Planck Society, Tübingen, Germany 

mlmcerezo@gmail.com, j.bryk@hud.ac.uk

### Log_files_stacks
This folder contains the log files generated for process_radtags. It includes th total number of reads recruited per barcode as well as the number of reads removed due the abscense of Radtag or low quality and the retained number of reads, that is what we will use for further analysis.
Log files have been divided in two folders (Type A and Type B) depending on how the library was prepared, in plates and also in number of mismatches allowed for barcode rescue. 
Log files were generated per multiplexed group.
The number of retained reads was used to generate Chimeras.txt, a table which includes the output off all the different log files.

### Chimeras.txt.

Table including the output of all the log files. Is the only table necessary to run the R scripts. It includes the number of reads retained per barcode combination as well as the number of mismatches allowed for barcode resuce, information about the library, the protocol followed to prepare the library and information about the origin of the reads (sample or chimera).

### 01_chimeras.Rmd
Rmarkdown script to quantify the different types of chimeras and generate the plots.

### 01_chimeras.html
Script and results from 01_chimeras.Rmd

### 02_Statistics_chimeras.Rmd
Rmarkdown script for statistical analysis.

### 02_Statistics_chimeras.html

Script and results from 02_Statistics_chimeras.Rmd

