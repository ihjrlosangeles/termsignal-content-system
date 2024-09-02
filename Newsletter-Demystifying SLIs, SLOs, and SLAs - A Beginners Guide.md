**Content Emotion:** 
[[Educate Me]]


**Channels:** 
📰 #Newsletter-Content 
🗞 #Blog-Content

---
title: Newsletter-Demystifying SLIs, SLOs, and SLAs - A Beginners Guide
date: YYYY-MM-DD
author: Isidro Hernandez Jr
---

# Introduction
## What I'm Going to Teach
- Briefly describe what the newsletter will cover.

## Why It Matters to the Reader
- Explain why this information is valuable and how it can impact the reader's life or work.

## Why Most People Fail
- Discuss common mistakes or misconceptions that prevent people from succeeding in this area.

# Main Content
## Strong Topical Statement
- Make a compelling statement that captures the essence of your main topic.

## Key Points
- Point 1: Detailed explanation or insight.
- Point 2: Detailed explanation or insight.
- Point 3: Detailed explanation or insight.

# Action Plan
- Step-by-step guide or actionable items that the reader can follow.

# Conclusion
## Recap
- Summarize the key points covered in the newsletter.

## Call to Action
- Encourage the reader to take a specific action based on the content of the newsletter.
---

Most people do not understand SLIs, SLOs, and SLAs. Im going to teach you that today in simple terms so you can speak on the topic with confidence. 


Service Level X are key for making relating to your application or your business. SLX help you with capacity planning, important indicators to monitor, business needs to meet, customer agreements.


90% of engineers ignore these topics because they arent the attractive parts of software development. The other 10% find that these topics are the cornerstone to a reliable and scalable application. 

Service Level Indicators, Objectives, and Agreements are the corner stone of SRE and any growing application. 


SLI: Service Level Indicator
> An SLI is a service level indicator—a carefully defined quantitative measure of some aspect of the level of service that is provided
[[Site Reliability Engineering.pdf#page=62&selection=75,0,79,52|Site Reliability Engineering, page 62]]

Common SLIs include: Request Latency, Error Rate, Requests Per Second, Availability
An indicator is often tied to a metric in a service. 

SLO: Service Level Objective
> An SLO is a service level objective: a target value or range of values for a service level that is measured by an SLI.

[[Site Reliability Engineering.pdf#page=63&selection=55,0,59,41|Site Reliability Engineering, page 63]]

Common SLOs
Availability: 99.9% of requests should be successful (non-5xx responses)
Latency:  95% of file uploads should complete within 4 seconds
Error Rates: 4xx errors should be less than 1% of total requests
Throughput: System should handle at least 50 uploads per second
Resource Utilization: Memory usage should remain below 80% for 99% of the time

SLA: Service Level Agreement
> SLAs are service level agreements: an explicit or implicit contract with your users that includes consequences of meeting (or missing) the SLOs they contain.

[[Site Reliability Engineering.pdf#page=65&selection=7,9,12,8|Site Reliability Engineering, page 65]]

Common SLAs: 
Uptime and Availability: Defines the percentage in times that the service will be operational. 
Example: 99.99 uptime guaranteed.

Performance: Specifies response times or throughput levels
Example: 95% of transactions will be processed within 4 seconds. 


Implementation

To implement these you need a monitoring stack. By using dashboards, alerts, logging, and the proper metrics you can harness the power of SRE. You will be prepared to handle any potential downtime and see an scaling opportunity before its needed. These are the tools needed to always provide a reliable service and to exceed the expectations of your users and stakeholders.

Conclusion
Now you can take this knowledge and implement SLX in your service. Do an audit and find gaps. When you are done you should have a significantly more reliable application. With the advancements in infrastructure today someone can pull the plug of the infrastructure you're application is hosted and your service will automatically recover without the user ever knowing. 