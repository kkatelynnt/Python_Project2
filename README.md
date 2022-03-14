# Python_Project2
How does gene expression levels of: COL11A1, COL10A1, CLDN8 and MMP11 vary between normal breast tissue of middle eastern women at ages >55 and tumor tissue of middle eastern women at ages >55 who have developed breast cancer?
You will need four files to adequately run the code:

1) Jupyter notebook, uploaded here
2) CSV file (first downloaded as TXT file then translated)
3) FAFSTA files

Information about where the TXT (CSV) file was found:
    https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE29044, there was a series matrix file (txt format) containing complete coverage of the Affymetrix Human Genome U122 Plus 2.0 array. The txt file was then imported to excel where I isolated only the rows containing gene expression profiles for Middle Eastern Women at ages >55 with normal breast tissue and breast cancer tumor tissue. I then saved the txt file as a CSV file. 

Information about where to find FAFSTA files:
  https://www.ncbi.nlm.nih.gov/gene/1301, this is the gene sequence for COL11A1 in homo sapiens (humans)
  https://www.ncbi.nlm.nih.gov/gene/457065, this is the gene sequence for COl11A1 in pan troglodytes (chimpanzees)
  The files are downloaded as 'fns' which is the same as FAFSTA file
