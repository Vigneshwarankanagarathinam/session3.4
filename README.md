session3
Assignment 4
Importance of NameNode: 
•	In HDFS, NameNode is the centerpiece and also known as the Master.
•	NameNode only stores the metadata of HDFS.
•	NameNode does not store the actual data or the dataset but are actually stored in the DataNodes.
•	NameNode can provide us with the list of the blocks and its location for any required file in HDFS and by using this information        NameNode can construct the file from blocks.
•	NameNode is very important in HDFS and when the NameNode crashes, Hadoop cluster cannot be accessed and is considered down(that is file system goes offline).
•	NameNode is a single point of failure in Hadoop cluster.
•	NameNode is usually configured with a lot of memory (RAM of 128GB), because the block locations help in main memory
