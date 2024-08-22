# The Content Operating System

Select an idea from [[Content Ideas]]

# Step 1: Idea Capture

#### **Idea:** Top Free Monitoring Tools for SREs: Building a Cost-Effective Stack

> [!IDEA]
> Top Free Monitoring Tools for SREs: Building a Cost-Effective Stack
> 


# Step 2: Research

*Be sure to remind yourself of your audience and main topics.*

**Tweets, quotes, books, or articles that you can pull inspiration from or back up your argument with.**

- **Tweets:**
    - 
    - 
- **Quotes:**
    - 
    - 
- **Books:**
    - 
    - 
- **Articles:**
- Github
    - https://github.com/zapier-interviews/interview-ihjrlosangeles-a496cee64dcb4059a3d3fbcfb3cfbda2/tree/project/monitoring
    - 
    

# Step 3: Newsletter Template
Template: [[Teach, Why, Fail, Solutions Newsletter Template]]
1. Select Template - Choose a template from Typeshare or create your own.


https://typeshare.co/isidrohernandez

```
Top Free Monitoring Tools for SREs: Building a Cost-Effective Stack


I'm going to walk you through how to build a free monitoring stack with open-source tools.

It's important to have the ability to have the ability to deploy your own monitoring stack without paying a third party. You want the flexibility of building your monitoring stack anytime, for free, on any platform. This will allow you to control your service reliability and observation fully.

Unfortunately... most people go with the easiest option which is actually the most expensive option in the long run.

## Why isn't everyone doing this?

Here are a few reasons why

- It is easier to set up a 3rd party paid service
    

- It requires less technical knowledge
    

- Paid services have fancy UIs that engineers love
    

- The setup process is not straightforward... at first
    

But don't worry! Its not as hard as it sounds. I would argue that once you set it up once you can do it 1000 times more far more quickly.

Here are the components required. :

### 1. Telemetry - OpenTelemetry Collector

Open Telemetry Colletor in conjunction with OpenTelemetry SDK allows you to instrument your service and _collect_ all logs, metrics, and traces.

### 2. Metrics - Prometheus

Prometheus collects and stores time-series data as metrics from monitoring targets. With the use of PromQL (Prometheus Query Language) for flexible querying and aggregation of collected data.

### 3. Tracing - Jaeger

Jaeger is a distributed tracing system. This allows to easily see traces from your services in a distributed architecture.

- Quickly find the root cause of a bug
    
- Analyze dependencies
    
- Distributed context propagation
    
- Performance Optimization
    

### 4. Logging - ELK Stack

ELK stack allows us to aggregate, enrich, search, and visualize logs.

- Elasticsearch - Distributed Search, Stores, and Indexes Data
    
- Logstash - Collectes logs with a processing pipeline. Ingests logs and transforms and enriches them
    
- Kibana. - Visualizes data and exportation. Provides a _powerful_ web interface for searching with Elasticsearch.
    

### 5. Dashboards - Grafana

Grafana is the best dashboard solution on the market. It allows for custom dashboards that provide the most important and actionable data about your services.

- Common data sources: Prometheus, Elasticsearch, InfluxDB, MySQL, PostgreSQL
    

Grafanas Visualization features are far too many to list here. Keep an eye out for a newsletter on just this topic.

### 6. Alerting - Alert Manager

Arguearbly the most important component of a monitoring stack. This gives you the ability to send alerts based on predefined rules and thresholds relating to your services.

Notification Recievers can include:

- Email
    
- Slack
    
- Pagerduty
    
- OpsGenie
    
- Web Hooks
    

Learning to deploy this stack will empower your team to OWN your monitoring stack!
```

# Step 4: Editing

- [ ]  Have you added appropriate visuals?
- [ ]  Are your sentences concise, grammar corrected, and understandable?
- [ ]  Do you stick to the main topic, reduce going on tangents, and deliver what is promised in the headline?
- [ ]  Go through your draft — add links to relevant resources

# Step 5: Pre-Newsletter CTA

Build a Cost-Effective Stack w/ The Best Free Monitoring Tools  

It's important to have the ability to have the ability to deploy your own monitoring stack without paying a third party. This weeks newsletter will cover free tools for a complete monitoring stack.

1. Metrics
2. Logging
3. Traces
4. Dashboards
5. Alerting

Tomorrow, I'll show my newsletter people how to build your own stack in-house

No need for expensive SaaS monitoring stacks!

If you want to join us, subscribe here: https://termsignal.ck.page/ec5eab6a24

# Step 6: Post-Newsletter CTA

Build a Cost-Effective Stack w/ The Best Free Monitoring Tools  

Owning your monitoring stack is imperative. 

Knowing which tools are effective is imperative. 

Yesterday our newsletter subscribers people learned which tools are the most cost effective without sacrificing quality

Miss the issue?

Grab it below ↓

https://termsignal.ck.page/ec5eab6a24

# Step 7: Thread Template
```
1/7 Top Free Monitoring Tools for SREs: Building a Cost-Effective Stack 🛠️

Let's walk through how to build a free monitoring stack with open-source tools. Control your service reliability and observation fully, without relying on expensive third-party services.

2/7 Why use open-source tools? 🤔
- Full control over your data
- Flexibility to customize and scale
- Cost-effectiveness in the long run
- Deeper understanding of your systems

The setup might seem daunting at first, but the benefits are worth it!

3/7 Components for your free monitoring stack:

1. Telemetry: OpenTelemetry Collector
2. Metrics: Prometheus
3. Tracing: Jaeger
4. Logging: ELK Stack
5. Dashboards: Grafana
6. Alerting: Alert Manager

4/7 OpenTelemetry Collector instruments your service and collects logs, metrics, and traces.

Prometheus stores time-series data as metrics, with PromQL for querying.

Jaeger enables distributed tracing for bug finding, dependency analysis, and performance optimization.

5/7 ELK Stack (Elasticsearch, Logstash, Kibana) aggregates, enriches, searches, and visualizes logs.

Grafana creates custom dashboards with data from various sources like Prometheus, Elasticsearch, MySQL, etc.

6/7 Alert Manager sends notifications based on predefined rules and thresholds. It can alert via:
- Email
- Slack
- PagerDuty
- OpsGenie
- Web Hooks

Crucial for timely incident response!

7/7 Start small, experiment, and gradually build up your stack. Before you know it, you'll have a robust, flexible, and cost-effective monitoring system tailored to your needs. 

Happy monitoring! 🚀 #SRE #Monitoring #OpenSource
```
Write in Hypefury, TweetHunter or your favorite Publishing Tool

# Step 8: Writing -  Short Form

*You will be writing your draft in your favorite writing software (Hypefury, TweetHunter, Hemingway, Google Docs, etc)*

**Style of Post**
```story
Most people are not aware of how much their monitoring stack is costing them. 

Although, third party saas monitoring stacks are easier to setup they can come with significant drawbacks.

Have you ever wondered how much you are giving up by using a SaaS monitoring stack?

Don't worry I'll tell you exactly what tools can help you avoid these pitfalls.

By deploying the following tools to your cloud platform you can fully own the monitoring stack and siginificatly drop the cost of the entire stack. 

- OpenTelemtry Collector - Will store and pass along metrics, logs, and traces
- Prometheus - Stores and Queries metrics 
- Jaeger - Provides tracing for services in a distributed architecture
- ELK - Aggregates, enriches, searches, and visualizes logs
- Grafana Dashboards - Allows you to build custom dashboards to visualize your entire architecture
- AlertManager - Notifies your team of alarms through channels like email and slack

```
- Story (A full-blown story)
- ``
- 
    - **Pain/Attention** — use a personal story or start with a problem
        - 
    - **Agitate** — share how things got worse and what happened to you/someone.
        - 
    - **Intrigue** — show them a new perspective to think about that’s intriguing
        - 
    - **Positive Future** — show the future benefits associated with the intrigue.
        - 
    - **Solution** — bring clarity to how they can achieve a positive future with a solution
        - 
- Observation (What’s something interesting you noticed?)
- Contrarian (What’s a commonly held belief about this that’s wrong?)
- Listicle (What are some tools/books/newsletters/Tweets about this?)
- Analyze (Why did this happen?)
- Past vs Present

***Start writing!***
# Step 9: Start Writing
1. Create New File w. template
2. Write the newsletter