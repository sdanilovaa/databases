In this hometask we chose S4S merch business as a model for the DWH. 
At the Data Lake layer we have tree DataBases: products, users and payment&transactions. 
On the Stage layer we upload the data from these DBs, clean it, delete NAs, select needed columns, stucture data. 
Then, we paste the data into the Star Scheme table where we have the fact table of our sales. 
On the star scheme diagram we can see the structure of the DWH we have on our stage layer. 
On the mart layer we need to select top tree latest sales this month. 
In order to do that we need to select sales date, seller, total sale, product name and order by date, descending. 
Then we select 3. 
That is all. 

