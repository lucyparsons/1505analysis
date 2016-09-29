# 1505: Analysis

This repository contains documents, data, and analysis used for Lucy Parsons
Labs' investigation into the use of civil asset forfeiture by Chicago Police.

Our data archive and visualization can be seen [on our
website](https://lucyparsonslabs.com/fullaudit). The article we wrote in
collaboration with Joel Handley and the Chicago Reader can be seen [on the
Reader's
site](http://www.chicagoreader.com/chicago/police-department-civil-forfeiture-investigation/Content?oid=23728922).

Contact [info@lucyparsonslabs.com](mailto:info@lucyparsonslabs.com) with questions or inquiries. 

# What's Here

This repository contains document that show all expenditures above $5000 by Chicago Police
using asset forfeiture money. It also shows deposits into the asset forfeiture
accounts.

## Expenditures

The `singlepdfs` directory contains a single PDF for every expenditure above
$5000. You can navigate to each individual check more easily using our web
interface. The `preprocess` directory shows some of the preprocessing /
descriptive statistics that we did on this data.

### Columns: 

* **Check number:** CPD's check number
* **Date:** Date of expenditure
* **Amount:** of purchase in USD
* **Purchase:** What was bought
* **Category:** Whether the purchase was routine or for surveillance devices
* **Source:** Link to PDF document for that check displaying further information about the check (stored in `singlepdfs` folder)

## Deposits 

The `deposits` directory contains documents and analysis showing how we calculated the
amount that went IN to CPD's 1505 and 1505 ML accounts.  
