Backlinks:
[[Alerting]]

# Types of Indicators for Monitoring a Webserver

When beginning to instrument a webserver, start by asking:

"Select what kind of Indicators you want to monitor for this service?"

Here's a comprehensive list of indicator types to consider:

1. Availability
2. Response Time (Latency)
3. Error Rate
4. Throughput
5. Saturation
6. Traffic
7. Utilization
   - CPU
   - Memory
   - Disk
   - Network
8. Concurrency
9. Capacity
10. Performance
11. Security
12. Compliance
13. Cost
14. User Experience
15. Business Metrics
16. Dependencies
17. Caching Performance
18. Queue Length
19. Database Performance (if applicable)
20. Content Delivery
21. SSL/TLS Performance
22. DNS Performance
23. Load Balancing Effectiveness (if applicable)
24. API Performance (if applicable)
25. Microservices Health (if applicable)
26. Garbage Collection (for languages like Java)
27. Thread Pool Health
28. Connection Pool Health
29. Session Management
30. Logging Performance

Note: Not all of these may be applicable to every webserver. Select the ones most relevant to your specific use case and architecture.


# Initial Steps for Instrumenting a Webserver

## Step 1: Identify Critical Indicators

Ask: "What are the critical indicators of our webserver's health and performance?"

Common critical indicators for a webserver might include:

1. Availability
   - Is the server responding to requests?

2. Response Time
   - How quickly is the server responding to requests?

3. Error Rate
   - What percentage of requests are resulting in errors?

4. Request Rate
   - How many requests is the server handling per second?

5. Resource Utilization
   - CPU usage
   - Memory usage
   - Disk I/O
   - Network I/O

6. Connection Count
   - How many active connections are being maintained?

7. SSL/TLS Performance
   - Certificate validity
   - Handshake time

Next steps:
- Prioritize these indicators based on their impact on user experience and business objectives
- Determine specific metrics for each indicator
- Identify appropriate thresholds or patterns that indicate problems for each metric