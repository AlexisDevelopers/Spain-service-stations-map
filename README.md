This project consists of creating a report that shows the service stations in Spain on a map, including the prices of their main products and other additional information.

To obtain the data from the service stations, the open data web page of the Spanish government is used. An Excel file called "Fuel prices at Spanish gas stations" is downloaded and unnecessary rows and columns are removed. All the price fields are also eliminated except those corresponding to gasoline 95 E5, gasoline 98 E5, diesel A, and diesel B. Then, these four price columns are "unpivoted" to leave them in two columns: one with the product label corresponding and another with the price. The resulting two column labels are changed to "Product" and "Price" and the "Price" field is assigned a type of "Fixed Decimal Number".

Some additional columns are also removed and the name of the "Label" field is changed to "Supplier". The final fields will be: Province, Town, Zip Code, Address, Longitude, Latitude, Supplier, Hours, Product and Price.

To get the vendor logos, a CSV file called "stations.csv" is used and cleaned to make sure the field names are correct.

Once the data is obtained and cleaned, Power BI is used to visualize it on a map with the prices of the products and the logos of the corresponding suppliers.