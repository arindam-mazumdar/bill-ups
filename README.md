# bill-ups

This code contains the steps of model buliding for predicting late return of the books. 

Questions asked are:
 
 - <b>build a model to predict the likelihood of a late return of any book at checkout time? </b>
 
  The notebook consists of data wrangaling, data visualization and model for predicting possibility of late return.

 - <b>Are there any factors you can find that are connected with late returns? </b>
 
  Yes. I find that distance bewteen the library and the customer's residence is the most important factor in determining the possibility of late return.
 
 - <b>What would you recommend the library do to mitigate the risks you find? </b>
  
  I recommend the libraries to prioratize renting books to the local customers, particularly those customers which lives with in 
  2-3 miles from the library. 
 
 - <b>How would you present your findings to them to get buy-in? </b>
 
On an average 20% of the books return late in these libraries. If they can implement my recommendation of prioratizing local customers who lives in nearby blocks it would reduce the late return to 10%. 
(since, customers living within 3 miles has the probability of late returning of only 10%).   
 So, I would like to convince the Library that if this recommendation is considered it will reduce the late returns by half.

 ### Content of the Notebook:
- #### 1. Data Wrangling
- #### 2. Model Building
- #### 3. Visulaization and Conclusion
----------

 For calculating the distance between the residence of the customers and the libraries we used the co-ordinate location of the addresses from 
 OpenStreetMap data source: https://www.openstreetmap.org/
