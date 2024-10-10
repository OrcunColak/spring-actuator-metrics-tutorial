# Read me

The original idea is from  
https://medium.com/@sehgal.mohit06/actuator-in-spring-boot-application-1c8b28c28366

We can directly see metrics or see the metrics using prometheus

# Directly See Metrics

http://localhost:8080/actuator/metrics

# See Metrics Using Prometheus

http://localhost:8080/actuator/prometheus

# CPU Metrics

http://localhost:8080/actuator/metrics/system.cpu.usage
http://localhost:8080/actuator/metrics/process.cpu.usage

It shows metrics data for our application.
Ex: Free disk space, data related to executors pool, cpu usage, data related to jvm threads and memory etc.
These metrics data can be published to monitoring tools like prometheus/grafana, and we can see beautiful graphs showing
cpu usage or showing memory usages of our application.