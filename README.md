In this project, I have implemented all the components of the MapReduce framework by myself without using an existing distributed computing framework such as Apache Hadoop or Apache Spark.
Have implemented below given openration using gRPC 
Word Count
Inverted Index 
Natural Join 

●	Developed a Master program responsible for coordinating the entire MapReduce job, handling user inputs such as input data location, number of mappers, number of reducers, and output data location.
●	Designed and implemented the Map function, applied to each input split to generate intermediate key-value pairs.
●	Implemented partitioning of intermediate key-value pairs to ensure that all key-value pairs with the same key are sent to the same reducer during shuffling and sorting followed by a reducer implementation to group the values of same keys and generating a desired output.
