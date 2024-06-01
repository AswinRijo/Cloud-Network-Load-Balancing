# Cloud-Network-Load-Balancing

Overview
This dataset simulates network traffic data collected from a cloud network environment. It has been generated to model load balancing scenarios where incoming client requests are distributed across multiple servers to ensure optimal performance and reliability. The dataset contains attributes that describe the network traffic, server load, client requests, and various performance metrics.

Data Collection
The data has been synthetically generated to represent realistic network conditions in a cloud environment. It includes traffic from three different networks, identified as Network A, Network B, and Network C. Each network simulates a distinct set of clients and servers, with varying load and performance characteristics.

Purpose
The primary purpose of this dataset is to provide a foundation for developing and testing load balancing algorithms. It aims to assist in understanding how different attributes affect the performance and efficiency of load balancing strategies. The dataset can be used for machine learning tasks such as predicting the best server for handling incoming requests, analyzing traffic patterns, and optimizing load distribution.

Attributes
Timestamp: The precise time when each data point was recorded.
Source_IP: The IP address of the client initiating the request.
Dest_IP: The IP address of the server receiving the request.
Protocol: The type of network protocol used (e.g., HTTP, HTTPS, TCP, UDP).
Request_Size: The size of the incoming request in bytes.
Response_Size: The size of the outgoing response in bytes.
Latency: The time taken to process and respond to a request (in milliseconds).
Server_Load: The current load on the server (percentage of CPU usage).
Active_Connections: The current number of active connections on the server.
Request_Type: The type of request (e.g., GET, POST).
Response_Time: The time taken by the server to generate a response (in milliseconds).
Error_Rate: The rate of errors encountered (0 for no error, 1 for error).
Throughput: The amount of data transferred over a period of time (in MB/s).
Geolocation: The geographical location of the client (e.g., USA, Canada, UK).
Session_ID: A unique identifier for the user session.
Bandwidth_Utilization: The amount of bandwidth being used by the connection (percentage).
Health_Status: The health status of the server (Healthy or Unhealthy).
Queue_Length: The length of the request queue on the server.
Server_Response_Code: The HTTP response code returned by the server (e.g., 200, 404, 500).
Server_Region: The geographical region where the server is located (e.g., NA, EU, APAC).
Load_Balancer_Metrics: Metrics specific to the load balancer (e.g., number of requests handled per second).
Traffic_Type: Classification of traffic (e.g., Web Browsing, File Transfer, Video Streaming, Audio Streaming).
Network_Path: Information about the network path taken by the traffic (e.g., Path A, Path B).
Server_ID: The identifier of the server selected to handle the request.
Scenarios
The dataset is designed to reflect various scenarios encountered in network-based load balancing, such as:

Optimal Server Selection: Predicting the best server to handle incoming requests based on current load and performance metrics.
Traffic Distribution: Understanding how traffic is distributed across different servers and networks.
Performance Optimization: Analyzing response times and throughput to optimize server performance.
Error Handling: Identifying patterns in error rates to improve reliability and fault tolerance.
Usage
Researchers and practitioners can use this dataset to:

Develop and test load balancing algorithms.
Train machine learning models to predict server selection.
Analyze network performance under different load conditions.
Study the impact of various attributes on network efficiency and server reliability.
