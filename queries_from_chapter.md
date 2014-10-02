# Queries from Data Standard Chapter

###Number of BARCODE records submitted after November 1, 2009:
Animals (SQL):  
`SELECT COUNT(*) AS animal_count  
FROM gb  
WHERE submit_date > "2009-10-21"  
AND gene = "COI"`  
    
Plants (SQL):  
`SELECT COUNT(*) AS plant_count  
FROM gb  
WHERE submit_date > "2009-10-21"  
AND (gene = "matK" OR gene = 'COI')`  

###Number of public plant records in BOLD:
that are in GenBank, but can be upgraded to BARCODE status (SQL):  
``  
  
that have not yet been submitted to GenBank (SQL):  
``