# CATmodel

Danyang Jiang, Haonan Yang, Vincent Brely-Demeules

ETH Zurich

team project for lecture: Introduction to Catastrophe Risk Modelling by Arnaud Mignan

The code amis to build a simple CAT model. It mainly contains two parts: hazard and risk.

## Hazard 

We downloaded the faults data from http://efehrcms.ethz.ch/en/Documentation/specific-hazard-models/europe/overview/active-faults/.
By using the real faults data and simple GMEP function (Bommer 1991), we produce the event table (EventTable.csv), hazrad curve and hazard map.

## Risk

By using the LitPop, we can get the assets matrix. And from the openquake website, 
we choose one fragility curve and calculate the vulnerability curve based on it.
As for the building matrix, we set the quantile for different building type and assign it randomly with certain total number.

Finally we calculate the loss table (EventLossTable.csv), EP curve, and annual accumulate loss (AAL).

## More details

You can find more info in our report.

## Contact us

If you have any questions, just contact us :)

12.05.2022
