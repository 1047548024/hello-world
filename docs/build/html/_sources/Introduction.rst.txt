Introuuction
============
  

purpose
---------
To identify differentially expressed genes given a gene expression file containingtwo cell samples

Product
-------
A web application preferably using the Flask framework (http://flask.pocoo.org/)

Functionality
-------------

Overview
~~~~~~~~

The web application has a simple interface with a single button [Upload and GO]. Ourscientists upload a plain text file containing gene expression levels from twosamples, representing two experimental conditions. Accepting the file, the softwarewill return a table of differentially expressed genes and a scatter plot of thesegenes whose X-axis is control and Y-axis is treatment. If an invalid gene expressionis given, the web application returns a page informing the user to provide thecorrect format.