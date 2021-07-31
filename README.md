# spring-boot-elasticsearch

#Set Up Elasticsearch 
Step 1 - Go to Elastic's official website.

Step 2 - Select Elasticsearch in the drop down and then version  and click on the Download button.

Step 3 - It will give you options if you want to download as Zip, TAR, or RPM file. I selected the Zip format as using it on windows.

Step 4 - Unzip the downloaded content and go to the binfolder. There will be a file namedelasticsearch.bat.

Step 5 - Run this file on Windows OS through command prompt and it will start the Elasticsearch engine for you. Once started, it will start listening to port 9200. So the URL will be http://localhost:9200/. Also, port 9300 is exposed as a cluster node. Port 9200 is for REST communication and can be used by Java or any other language and 9300 is for Elasticsearch Cluster Node communication as well, and Java can also connect to this cluster node using the transport protocol.



