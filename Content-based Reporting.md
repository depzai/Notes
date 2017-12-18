#Amazon Content-based Funnel:
*11/30/2017*

###Objective: 
Build a funnel to report on Amazon customer's whose first touch with Audible is a a WFV book. The data will be integrated into the broader Amazon report (WBR hosted in CARI) and also available as a standalone report.

The report will track the following metrics:

- WFV Purchasers (last touch) - non members only
- WFV Free Purchasers (last touch) - non members only
- Customers using a credit to purchase a WFV book
- KU members who download a free WFV companion (non members)
- Free trial starts in those populations (30 days, 90 days, 180 days)
- Trial-to-member conversion for those trials


###Action Needed:
The data needs to be extracted using SQL (done by the BI team) and then stored in a new DMART table (DMART team). 

Then the CARI team will be able to import the data into a CARI object. Ultimately the reporting will be merged with funnel reporting from other sources.

###Responsibilities (RACI)

Responsible: BI

Accountable: BI

Consulted: Product, Marketing

Informed: DMART

###Data Source:

A report already exists in the audible insights portal. The queries can be leveraged to transfer the report into DMART and then CARI.

Queries are available [here](https://audible-insights.corp.amazon.com/report/7/etl.) for WFV and [here]() for KU.




