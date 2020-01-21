# assignment4-salonimishr
assignment4-salonimishr created by GitHub Classroom
**Assignment_4**

In this assignment, we have to count the UniqueCarrier with Pyspark. The data was same as in assignment 3. For this, there are  
three platforms which are used including Google Colab, Databricks and Docker Toolbox. Google Colab is a very good platform for
Pyspark as it has high volume processing and provides templates. Microsoft's Databricks is almost similar but in this we have to
create cluster for running a job. The same algorithm(mapping, shuffling and reducing) was also run using docker toolbox. Docker 
toolbox is container based technology and containers are just user space of the operating system.In this, the containers running
share the host OS kernel. 

Google Colab was best due to its fast processing. First in Colab, I initialized the pyspark environment and then mounted the google
drive. After this downloaded the data and then used pyspark to count the UniqueCarrier. In Databricks, I uploaded the data and 
performed the same task. At last, I did the task in Docker toolbox by copying the data into the container. Same results were achieved
by three different platforms. In Colab, the dataset is loaded into a RDD but DF and RDD is used to load the data in Databricks and 
Docker toolbox.
