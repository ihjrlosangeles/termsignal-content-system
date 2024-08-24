# Recap: Steps for Instrumenting a Service and Setting SLOs

1. [[Identify the type of service]]
   - Determine the specific category of service (e.g., web server, database, API service)
   - Understand the service's role in the overall system architecture

2. Select Relevant Indicator Types - [[SLIs]]
   - Choose from categories like Availability, Performance, Throughput, Error Rate, Latency, etc.
   - Focus on indicators most relevant to your service type and user experience

3. Define Specific Service Level Objectives ([[SLO List]])
   - Select specific SLOs from the comprehensive list for each chosen indicator type
   - Ensure SLOs are relevant to your service and measurable

4. Set Thresholds and Conditions for Alarms
   - [[Alert Types]] 
   - Determine baseline performance
   - Set specific threshold levels for each SLO
   - Define alarm conditions (e.g., when to trigger alerts)

5. Implement Monitoring and Alerting
   - Set up systems to track the chosen SLIs (Service Level Indicators)
   - Implement alerting mechanisms based on defined thresholds

6. Review and Iterate
   - Regularly assess the effectiveness of your SLOs and alerting
   - Adjust as necessary based on performance data and changing requirements