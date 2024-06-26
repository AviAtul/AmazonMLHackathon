Product length prediction:-
In this hackathon, the goal is to develop a machine learning model that can predict the length dimension of a product. Product length is crucial for packaging and storing products efficiently in the warehouse. Moreover, in many cases, it is an important attribute that customers use to assess the product size before purchasing. However, measuring the length of a product manually can be time-consuming and error-prone, especially for large catalogs with millions of products.

You will have access to the product title, description, bullet points, product type ID, and product length for 2.2 million products to train and test your submissions. Note that there is some noise in the data.

Task

You are required to build a machine learning model that can predict product length from catalog metadata.

Dataset description

The dataset folder contains the following files: 

train.csv: 2249698 x 6
test.csv: 734736 x 5
sample_submission.csv: 734736 x 2

The columns provided in the dataset are as follows:

Column name     Description

PRODUCT_ID	    Represents a unique identification of a product
TITLE	          Represents the title of the product
DESCRIPTION	    Represents the description of the product
BULLET_POINTS	  Represents the bullet points about the product
PRODUCT_TYPE_ID	Represents the product type 
PRODUCT_LENGTH	Represents the length of the product
