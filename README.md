# Spring Boot Actuator custom metrics published on Dynatrace example

This is an example on how to publish the Spring Boot Actuator custom metrics on Dynatrace using StatsD .

It requires to have a OneAgent on the Host where the application is running and [DynatraceStatsD needs to be enabled](https://www.dynatrace.com/support/help/shortlink/statsd-metric-ingestion#enable-dynatracestatsd).


```
mvn spring-boot:run
```
The published metrics will then be available in you Dynatrace environment. 

Useful links:

* [Spring Boot Actuator](https://docs.spring.io/spring-boot/docs/current/reference/html/production-ready-features.html).
* [Micrometer](https://micrometer.io/).
* [Micrometer/StatsD integration](https://micrometer.io/docs/registry/statsD).
* [DynatraceStatsD](https://www.dynatrace.com/support/help/how-to-use-dynatrace/metrics/metric-ingestion/ingestion-methods/statsd/)
* [Blog: Simplify observability for all your custom metrics (Part 1: StatsD)](https://www.dynatrace.com/news/blog/simplify-observability-for-all-your-custom-metrics-part-1-statsd/)
