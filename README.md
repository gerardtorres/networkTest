# networkTest
Pings selected IP. Upon failed ping or high latency run a traceRoute

## Config
failureTresh: This is you expected threshold for latency. Default is 100ms. If ping takes > 100ms, run a trace route.
testIP: Target server. Points to 8.8.8.8 by default. Change if issue is specifc to a service.

## Output
Writes to Output.log. Tail to see latest results.
