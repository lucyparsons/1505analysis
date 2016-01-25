## Splitting Checks into Single PDFs

We use ghostscript to generate single PDFs from the FOIA responses:

```
gs -sDEVICE=pdfwrite -dSAFER -o ../singlepdfs/outname.%d.pdf sinput.pdf
```

Then we use ghostscript to join two pages if the documents corresponding to a given check (purchase orders, etc.) spans multiple pages:

```
gs -dBATCH -dNOPAUSE -q -sDEVICE=pdfwrite -sOutputFile=output.pdf page1.pdf page2.pdf 
```
