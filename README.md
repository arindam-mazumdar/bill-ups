# Predicting Late Return of Books

This code contains the steps of model building for predicting the late return of the books. 

Questions asked are:
 
 - <b>build a model to predict the likelihood of a late return of any book at checkout time? </b>
 
  The notebook consists of data wrangling, data visualization and a model for predicting the possibility of a late return.

 - <b>Are there any factors you can find that are connected with late returns? </b>
 
  Yes. I find that distance between the library and the customer's residence is the most important factor in determining the possibility of a late return.
 The possibility of late return increases by increasing the distance between the library and the customer's residence.
 
 - <b>What would you recommend the library do to mitigate the risks you find? </b>
  
  I recommend the libraries prioritize renting books to the local customers, particularly those customers who live within 2-3 miles of the library. 
 
 - <b>How would you present your findings to them to get buy-in? </b>
 
On average 20% of the books return late in these libraries. If they can implement my recommendation of prioritizing local customers who live in nearby blocks it would reduce the late return to 10%. 
(since customers living within 3 miles have the probability of late returning of only 10%).   
 So, I would like to convince the Library that if this recommendation is considered it will reduce the late returns by half.

 ### Content of the Notebook:
- #### 1. Data Wrangling
- #### 2. Model Building
- #### 3. Visualization and Conclusion

<b>NOTE :</b> It takes around 15-16 minutes for downloading the co-ordinate data. It will be saved in a file. In the next run, you are requested to comment out the "Get co-ordinates" block in the 'Standardizing customer data' section. 

----------

 For calculating the distance between the residence of the customers and the libraries we used the co-ordinate location of the addresses from 
 OpenStreetMap data source: https://www.openstreetmap.org/
