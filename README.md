# Analysis-of-IMDB-Dataset-using-AWS-EMR

This project utilizes Spark ran using AWS Elastic Map Reduce (EMR) to provision Spark clusters. We connect to Jupyter Notebooks, which is used to interact with Spark. This is done by first creating an IAM user to access EMR. Once signed into that user a cluster is created on EMR, along with a studio and workspace. The Spark cluster tasks are run on Juypter Notebooks through the workspace. The data is loaded to EMR through AWS S3, from a publicly available S3 bucket.

This project will analyze subset of IMDB's actors, genres, movie actors, and movie ratings data by performing transformations and actions in PySpark. Other dependencies such as pandas and matplotlib will be utilized and our data will be loaded as a pyspark dataframe. Basic data analysis such as deriving unique generes and categories to plotting the genres with the highest average rating to discovering key facts about the data will be explored.
