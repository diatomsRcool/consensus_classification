# consensus_classification
Documentation for the creation of a life-wide consensus classification

FALO
The file ggi_family_dataV11Dec2014.xls was modified for upload into TTT (http://ttt.biodinfo.org/TF/).
To prepare the FALO file for TTT, I removed the data and the extra worksheets. I renamed
the sheet with the names on it "taxon" to comply with the formatting requirements of TTT.
This file was easily uploaded into TTT.

OTT
The file taxonomy.tsv (obtained from Open Tree of Life github repository) was modified using
tsv_to_dwca.py to reformat in dwca and to remove hidden taxa, invalid taxa, and any taxa
below family. This file was uploaded into TTT.