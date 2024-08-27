# Comprehensive Key Alarm Types for Site Reliability Engineering (SRE)

## 0. Threshold Alarms
- Static threshold alarms
- Dynamic threshold alarms
- Relative threshold alarms
- Multi-step threshold alarms

Why key for SRE: Threshold alarms are fundamental building blocks for many other alarm types. They provide a simple, efficient way to detect when a metric crosses a predefined limit.

## 1. Service Level Objective (SLO) Alarms
- Error budget consumption alarms (threshold-based on remaining error budget)
- SLO breach prediction alarms (often using trend analysis with thresholds)
- Burn rate alarms (threshold-based on the rate of error budget consumption)

Why key for SRE: SLOs are fundamental to SRE practices, helping balance reliability and innovation. These alarms often use thresholds to determine when SLO-related metrics reach critical levels.

## 2. Anomaly Detection Alarms
- Statistical anomaly detection (uses dynamic thresholds based on statistical models)
- Machine learning-based anomaly detection
- Time series decomposition anomaly detection

Why key for SRE: Helps identify unusual patterns that might indicate emerging issues before they become critical. While not traditional threshold alarms, these often use adaptive thresholds based on historical data.

## 3. Latency-based Alarms
- Percentile-based latency alarms (e.g., 95th, 99th percentile) (uses thresholds on specific percentile values)
- Latency SLO violation alarms (threshold-based on SLO targets)

Why key for SRE: Crucial for maintaining responsiveness and user experience. These typically use threshold alarms on percentile values or averages.

## 4. Error Rate Alarms
- Error percentage alarms (threshold-based on acceptable error rates)
- Error rate spike detection (uses dynamic thresholds or anomaly detection)

Why key for SRE: Directly impacts service reliability and user satisfaction. Often implemented as threshold alarms on error rate metrics.

## 5. Saturation Alarms
- Resource utilization alarms (CPU, memory, disk, network) (classic threshold alarms)
- Queue length or backlog alarms (threshold-based on acceptable queue lengths)

Why key for SRE: Helps prevent system overload and degraded performance. These are typically implemented as threshold alarms on resource usage metrics.

## 6. Traffic Volume Alarms
- Requests per second (RPS) anomaly detection (uses dynamic thresholds or anomaly detection)
- Unexpected traffic pattern alarms (can use threshold alarms or more complex anomaly detection)

Why key for SRE: Crucial for capacity planning and detecting potential DDoS attacks. May use threshold alarms for simple cases or more complex anomaly detection for advanced scenarios.

## 7. Dependency Alarms
- Service dependency health checks (often use threshold alarms on response times or error rates)
- Third-party service integration alarms (can use threshold alarms on integration-specific metrics)

Why key for SRE: Ensures awareness of issues in the broader ecosystem that could impact your service. Often implemented using threshold alarms on dependency-related metrics.

## 8. Canary Analysis Alarms
- Deployment canary health alarms (uses thresholds to compare canary to baseline)
- A/B test performance deviation alarms (threshold-based on acceptable deviations)

Why key for SRE: Supports safe rollouts and feature launches. These often use threshold alarms to determine acceptable deviations between canary/test and baseline metrics.

## 9. Composite Alarms
- Multiple condition alarms (e.g., high latency AND high error rate) (combines multiple threshold alarms)
- Complex boolean logic alarms for system-wide health

Why key for SRE: Allows for more nuanced and accurate alerting based on overall system health. These combine multiple simpler alarms, often threshold-based, into more complex conditions.

## 10. Missing Data Alarms
- Data gap detection alarms (time-based thresholds)
- Heartbeat alarms for critical components (time-based thresholds)

Why key for SRE: Ensures monitoring system itself is functioning correctly and no critical data is missing. These use time-based threshold alarms to detect when data hasn't been received within an expected interval.

## 11. Predictive Alarms
- Capacity forecast alarms (uses thresholds on forecasted values)
- Trend-based prediction alarms (uses thresholds on trend analysis)

Why key for SRE: Enables proactive management of resources and potential issues. These often use threshold alarms on predicted future values or trends.

## 12. Toil Measurement Alarms
- Alarms on increased manual intervention frequency (threshold-based on intervention counts)
- Automation failure alarms (threshold-based on failure rates of automated processes)

Why key for SRE: Helps track and reduce toil, a key SRE principle. These typically use threshold alarms on metrics related to manual work or automation effectiveness.