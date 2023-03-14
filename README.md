# Flight-routs-visual-analysis
by using FLOW MAP in Power BI 
from  Flight Route Database from Kaggle 

https://www.kaggle.com/datasets/open-flights/flight-route-database

loaded into power Bi and adjusted, but it has airports in thier international codes.

so from nationsonline websits, import tables which contains airports codes related to countries.

IATA 3-Letter Codes of Airports
https://www.nationsonline.org/oneworld/IATA_Codes/airport_code_list.htm

but it doesnt has data in one table, but seprated alphabitically " a table, b tables... etc.."
so, appended all tables to a table, then set a relation between rout table and airport tables.
voila, map is showing origin and destination of every rout.

