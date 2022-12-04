# Data_Analysis_Slab
Data Analysis,Data predictions and Data engineering

<b> House Price Predictions </b>
My goal was to understand the relationship between house features and how these
variables affect the house price.

about dataset: 
the dataset contain the following columns
Transaction_date	House_Age	dist_metro	stores	latitude	longitude	bedroom	house_size	as the predictor variables 
and prices as the target varaible.
the size of the dataset was 414*9

Analysis:
For the analysis part I have chosen two model linear Regression and the Polynomial Regression. because most of the significant variables were
linear types. I could have used Decision Tree or the Random Forest but these models are not suitable of linear kind of datasets.

<b> Flipkar_Amazon_Analysis </b>
Here I have to match the similar products from the Flipkart dataset with the Amazon dataset. Once
similar products are matched, we have to display the retail price from FK and AMZ side by side.
as,
![image](https://user-images.githubusercontent.com/79563144/205481082-c7edad2c-51a1-4039-b0d4-39ed8e45b293.png)

to achieve the task, I have used modified hamming distance. Modified hamming distance means I have just divided the hamming distance by length of the both strings.
Since the datset contains certain product names which length were very small hence the hammind distance was coming smaller while comparing the real product name and 
smaller product name. hence, modified version of the hamming distance resolved the issue.

