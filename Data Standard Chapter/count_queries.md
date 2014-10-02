##Queries from Data Standard Chapter
  
####Number of BARCODE records that have the strongly recommended field:
lat\_lon (_320,324_):  
([Entrez](http://www.ncbi.nlm.nih.gov/nuccore/?term=barcode%5Bkeyword%5D+AND+src+lat_lon%5Bprop%5D)) 
`barcode[keyword] AND src lat_lon[prop]`  
collected\_by (_324,568_):  
([Entrez](http://www.ncbi.nlm.nih.gov/nuccore/?term=barcode%5Bkeyword%5D+AND+src+collected_by%5Bprop%5D)) 
`barcode[keyword] AND src collected_by[prop]`  
collection\_date (_333,931_):  
([Entrez](http://www.ncbi.nlm.nih.gov/nuccore/?term=barcode%5Bkeyword%5D+AND+src+collection_date%5Bprop%5D))
`barcode[keyword] AND src collection_date[prop]`  
identified\_by (_124,809_):  
([Entrez](http://www.ncbi.nlm.nih.gov/nuccore/?term=barcode%5Bkeyword%5D+AND+src+identified_by%5Bprop%5D))
`barcode[keyword] AND src identified_by[prop]`  
associated trace file (_308,411_):  
([Entrez](http://www.ncbi.nlm.nih.gov/nuccore/?term=barcode%5Bkeyword%5D+AND+nucleotide+trace%5Bfilter%5D))
`barcode[keyword] AND nucleotide trace[filter]`  

####Number of BARCODE records submitted after November 1, 2009:
Animals (_323,586_):  
(SQL) `SELECT COUNT(*) AS animal_count  
FROM gb  
WHERE submit_date > "2009-10-21"  
AND gene = "COI"`  

Plants (_13,133_):  
(SQL) `SELECT COUNT(*) AS plant_count  
FROM gb  
WHERE submit_date > "2009-10-21"  
AND (gene = "matK" OR gene = 'COI')`  

####Number of public plant records in BOLD:
that are in GenBank, but can be upgraded to BARCODE status (SQL):  
``  
    
that have not yet been submitted to GenBank (SQL):  
``  
  
####Number of BARCODE records in proper DwC triplet format:
(SQL and Python)

####Number of BARCODE records identified down to taxonomic level:
Order(SQL): 
